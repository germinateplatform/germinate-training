<!-- Use these horrible HTML tag attributes because Markdown only supports limited HTML/CSS -->
<p align="center">
  <img src="img/germinate-square-name.svg" width="300" alt="Germinate">
</p>

<table bgcolor="white" align="center">
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <img src="img/crop-trust.svg" width="300" alt="Crop Trust">
      </td>
      <td align="center" valign="middle">
        <img src="img/templeton.svg" width="300" alt="Templeton World Charity Foundation">
      </td>
      <td align="center" valign="middle">
        <img src="img/hutton.svg" width="300" alt="The James Hutton Institute">
      </td>
    </tr>
  </tbody>
</table>


# Session 3: Working with Germplasm

This tutorial will show you how to work with germplasm entries held in Germinate.

All data that Germinate holds is related back to the underlying germplasm (this is one of our core concepts and the foundataion for tools like Germinate) and so being able to effectively work with germplasm and utislise the tools that we offer is important in becoming proficient with Germinate.

# Before we start

### Getting help 

If you’re ever stuck while using Germinate, use the help button which can alwas be found in the top right hand side of the Germinate interface.

<img src="session-3/help.png" style="max-width: 100%;">

This help provides more information about the current page or functionality. This feature will explain the interface components or the content of the page in more detail. If they help icon is greyed out then additional help information is not available for this page. This screenshot shows the type of information that we hold for the germplasm page in Germinate.

<img src="session-3/help2.png" style="max-width: 100%;">

Refer back to help if you are having problems but we are also there to help you so drop us an email on <a href="mailto:germinate@hutton.ac.uk">germinate@hutton.ac.uk</a> with any problems you may encounter.

# So lets get started!

We will use the Germinate demo database in this instance. The demo database contains real data but we have anonomised it and assigned a fictional plant species, the [Cactaur](https://en.wikipedia.org/wiki/Cactuar). We have done this because all projects are different and Germinate supports more data types than projects generally contain. The demo database has all data types we support along with all features available to users to try out in a safe environment.

***Rememeber you can't break anything use the Germinate Demo database to play about with features.***

Firstly we are going to visit this link: https://ics.hutton.ac.uk/germinate-demo then once there click on the "Data" menu item on the left hand menu then on the "Germplasm" menu item.

You should now see something like this:

<img src="session-3/germplasm1.png" style="max-width: 100%;">

This page shows all the germplasm (accession or samples) that Germinate contains for the chosen database. This is where you can come to browse the accessions and search for germplasm that may be of interest.

## Showing and hiding columns 

Tables within Germinate show **lots** of information. Sometimes, you will only be interested in a specific part of this information and hiding table columns is one way to allow you to focus better. Use the dropdown button in the top left of any table to select the columns you wish to show or hide. These settings are remembered for your session, so they will be remembered *until* you close your browser. If you make a change it only applies to your session so nobody else will see your changes. 

This example shows how you add or remove columns from the Germinate Germplasm page. Click on the show/hide columns option within the table options. This option can be found at the top left hand side of the table beside help and filter options.

<img src="session-3/germplasm-column-dropdown.png" style="max-width: 100%;">

Now that you have selected this you can choose which columns to show and hide. Its easy, just click on them to toggle on and off. If you accidentally turn off something you want to see just go back and enable it again. Look at this screenshot, notice how the columns are different?

<img src="session-3/germplasm-column-hiding.png" style="max-width: 100%;">

## Selecting how many entries to show 

Another way to change how data is displayed in tables is changing the number of rows that are shown at a time. By default, Germinate only shows a small number of rows the reduce the amount of scrolling required to take in all the information. To show more rows per page, select a different value from the dropdown menu in the top right of the table. The display will refresh and now show the requested number of rows. Have a play about with this and see which looks best on your monitor screen. Like the table columns this setting remains until you close your browser.

<img src="session-3/germplasm-page-size.png" style="max-width: 100%;">

## Sorting and filtering the germplasm table 

All tables within Germinate can be sorted or filtered by any of the columns you see. Sorting happens by clicking on a table header and another click on the same column inverts the sorting direction. This image shows the table header. If you look at the diamond icon next to Germplasm name in the table header you will see how the table is sorted. If the light coloured half is on the top it means the column is sorted alphabetically and on the lower (like here) its reverse alphabetical ordering.  Try clicking on some of the table headers to see what effect the sorting has on the table. The table sorting sorts data across the entire database and not just the lines that are in the current table page.

<img src="session-3/germplasm-sorting.png" style="max-width: 100%;">


Filtering is a very useful tool when searching for specific data points. In this example, we are looking at the germplasm table. The filtering dialog is opened by clicking the filter button in the top left of the table. 

<img src="session-3/germplasm-filter-empty.png" style="max-width: 100%;">

Here, search criteria for each column can be defined and combined allowing simple searches as well as complex queries. To search for germplasm whose name matches a specific text pattern select the ***Germplasm name*** column from the dropdown and then enter the text you want to search for/. Be sure to change the match type from ***Equal*** to contains then enter the following into the search box.

>cactuar-9%

Now the ***%*** might appear confusing buy the ***%*** sign is the standard wildcard for SQL (database) queries and means that the query will look for everthing starting with ***cactuar-9*** then anything after it. It can be thought of like the * character in the Windows operating system.

<img src="session-3/germplasm-filter-search.png" style="max-width: 100%;">

This filter can be combined with a search for germplasm from a specific country resulting in only germplasm with the combination of species and country of origin to be displayed in the resulting table. This example shows us building up a layered query by including only germplasm with the pattern ***cactuar-9%*** from ***Country*** that is equal to ***Brazil*** and finally only those matches where the collection site for the accession was ***greater than 500m***. 

<img src="session-3/germplasm-filter-multiple.png" style="max-width: 100%;">

Now press ***OK*** and the database returns 4 records that match these criteria.

<img src="session-3/germplasm-filter-result.png" style="max-width: 100%;">

If we click on the ***Germplasm name*** we get a page that shows all the information we know about that particular entry. We will cover this in more detail later in this training but have a look and see what types of data Germinate holds for entry ***CACTUAR-914***.

The passport page of a germplasm is where all information available for this germplasm is aggregated in a single location. Meta-data, pedigrees, location information, images, and data availability are all easily accessible from here. 

<img src="session-3/germplasm-passport.png" style="max-width: 100%;">

## Accessions Plants/Plots and Samples 

Germplasm in Germinate is stored at different levels: ‘Accession’, ‘Plant/Plot’ and ‘Sample’ called ‘entity types’. Plant/plot level material is usually derived from accession germplasm and samples can be taken from either plant/plot or accession level. This level of information can be seen in the main germplasm table by making sure you have the ***Entity type*** column turned on. We will look at this in more detail when we look at exporting data from Germinate.

With the table filtering active, sort the table by collection date in ascending order. What is the first germplasm in the table? 

Using the marking mechanism, mark the first four germplasm in the table. 

Navigate to the passport page of X, what is Y? 

## Tasks:

1. <details><summary>Go to the main Germplasm list page and try showing and hiding columns.</summary>You can navigate to the page by clicking <a href="https://ics.hutton.ac.uk/germinate-demo/#/data/germplasm">here</a> then selecting table options from the top left hand side of the germplasm table.</details>

2. <details><summary>Using the germplasm table filtering, search for germplasm collected in Morocco.</summary>If you want to try using the wildcard <strong>%</strong> try changing the search from <strong>Equal</strong> to <strong>Contains</strong> and your search term to mo<strong>%</strong>. Do you get the same results? Why are there other results in the search now?</details>

3. <details><summary>With the table filtering active, sort the table by collection date in ascending order. What is the first germplasm in the table?</summary></details> 

4. <details><summary>Navigate to the passport page for the line whose country of collection is <strong>Kenya</strong> where the collection site is above <strong>1500m</strong> and the accesion biological status is equal to <strong>Natural</strong>. What datasets does this line appear in?</summary>There are 3 datasets that this line appears in. Datasets "Sample Phenotype Data",  "Sample Compound Data" and "Sample Genotype Data Subset 2."</details>

> ### About
> This training has been created under the [Templeton World Charity Foundation, Inc.](https://www.templetonworldcharity.org/) Grant ID TWCF0400 *'Safeguarding crop diversity for food security: Pre-breeding complemented with Innovative Finance'* which is managed by the [Crop Trust](https://www.croptrust.org/). This training is free to use and released under a non-restrictive open source licence.