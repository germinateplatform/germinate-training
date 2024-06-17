<!-- Use these horrible HTML tag attributes because Markdown only supports limited HTML/CSS -->
<p align="center">
  <img src="img/germinate-square-name.svg" width="300" alt="Germinate">
</p>

Contact us: [germinate@hutton.ac.uk](mailto:germinate@hutton.ac.uk) or [@germinatehub](https://www.twitter.com/germinatehub) on Twitter

# Session 9: Searching for data

If you ever find yourself searching for a germplasm, a marker, a trait, or a location but you don't know the exact name, then the Germinate-wide search is where you'll find it. Simply type in a name-fragment into the search box at the top of the page and hit enter. Alternatively, first navigate to the search page using the main menu.

<img src="session-9/search-interface.png" style="max-width: 100%;" alt="Search feature location on the web interface">

The search page will open and let you define what you're looking for. You can either search all data types or for any type individually. A click on the button starts the search and the results will be grouped into data type specific tables. So, if you're searching for a location name, you will see germplasm collected at this location as well as trials conducted at a location. Searching for a germplasm identifier will show the germplasm passport data as well as all trials and compound data recorded for this germplasm.

Let's look at some examples. Searching for `mexico` will return germplasm collected in Mexico as well as location information from Mexico.

> Important: Germinate will automatically include wildcards at the beginning and end of search strings if you select the **Contains** option. If you need to use a wildcard you only need to use it when it is contained **within** a search term. So for example you don't need to use '%ken%' but 'k%n' is valid. When using the **Contains** search option Germinate will automatically add % to the beginning and end of a search term.

<img src="session-9/search-example-location.png" style="max-width: 100%;" alt="Example of a search: Locations"> 

Searching for a germplasm name returns all information related to this germplasm. In this case, there is passport data, trials data, compound data and pedigree data.

<img src="session-9/search-example-germplasm.png" style="max-width: 100%;" alt="Example of a search: Germplasm"> 

Clicking on any of the result sections will expand it and show all search results for the selected data type. If we click on the "**Trials data**" section, we can see all the trials data points relating to germplasm `CACTUAR-2`.

<img src="session-9/search-example-germplasm-expanded.png" style="max-width: 100%;" alt="Example of a search: Germplasm expanded"> 

You don't have to search for the name of something, the search term can be anything. For example, searching for a specific treatment will return data points from trials with that treatment, searching for `wild` will return everything that contains the term `wild` as seen below.

<img src="session-9/search-example-wild.png" style="max-width: 100%;" alt="Example of a search: 'Wild''"> 

Note that you may have to switch the comparison operator from `Equal` to `Contains` or even `Between` to fulfil your search needs.

## Tasks

1. <details><summary>Try searching using some terms. For example try searching for Kenya - how many germplasm entries were collected in Kenya? </summary>Answer: There are 8 plant lines that are located in Kenya.</details>
2. <details><summary>We mentioned wildcards earlier. Wildcards can be used to search where you are unsure of something. Instead of entering 'Kenya' into the search try 'ken' and have a look to see why the data returned is different. Now try 'k%n' and again try and work out why the results returned are different. make sure you select the 'Contains' search option when you are doing this.</summary>Answer: 'Kenya' will only return matches that contain the word 'Kenya' in it. 'ken' gets expanded to '%ken%' which is for anything that contains those characters which also includes a site in Uzbekistan. 'k%n' is anything that has a 'k' then something then an 'n' which is much more common and includes a wide variety of different matches in Germinate.</details>
3. <details><summary>What germplasm exists in a location called 'Nairobi'?</summary>Answer: There are 4 lines that are assigned to a location called 'Nairobi'. To do this just enter the search term then choose the 'Location data' results tab.</details>



> Thanks for taking the time to complete this traning. We hope that this will allow you to have more confidence in using Germinate, know a bit more about what it does and provide you with foundations on which you can go on to explore it further, perhaps with your own datasets!

Next Steps:  We will add new tutorials on using Germinate including working with real data from projects over the coming months. In the meantime if you have any questions please contact us [germinate@hutton.ac.uk](mailto:germinate@hutton.ac.uk) and feel free to play about with the training database to explore Germinate and the tools that it offers.


> ## About
> This training has been created under the [Templeton World Charity Foundation, Inc.](https://www.templetonworldcharity.org/) Grant ID TWCF0400 *'Safeguarding crop diversity for food security: Pre-breeding complemented with Innovative Finance'* which is managed by the [Crop Trust](https://www.croptrust.org/). This training is free to use and released under a non-restrictive open source licence.

<div class="logos">
  <img src="img/crop-trust.svg" width="300" alt="Crop Trust">
  <img src="img/templeton.svg" width="300" alt="Templeton World Charity Foundation">
  <img src="img/best-crop.svg" width="300" alt="BEST-CROP">
  <img src="img/hutton.svg" width="300" alt="The James Hutton Institute">
</div>