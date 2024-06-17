<!-- Use these horrible HTML tag attributes because Markdown only supports limited HTML/CSS -->
<p align="center">
  <img src="img/germinate-square-name.svg" width="150" alt="Germinate">
</p>


Contact us: [germinate@hutton.ac.uk](mailto:germinate@hutton.ac.uk) or [@germinatehub](https://www.twitter.com/germinatehub) on Twitter


# Session 1: Getting Started and Introduction to Germinate

> We recently provided a training session Germinate which can be found here [YouTube Germinate Training](https://youtu.be/irAvxIOAvL4). It's worth watching this before undertaking this training as it will give you a good foundataion to base these materials on.

## Why use Germinate? 
It's often difficult trying to get a handle on large datasets and what they contain. The complexity and volumes of data are challenging to visualize so tools which help researchers do this are important in trying to get the most out of our data. Traditionally we may have used tools such as a spreadsheet to try and work with data, which is fine, but had its limitations. With datasets getting larger and larger we need tools that can efficiently handle these volumes of data and allow us to explore and interact with it. This is just not possible with spreadsheets.

This is where Germinate can help. Germinate allows you to manage data from your collections in a standard and [FAIR way](https://www.go-fair.org/fair-principles/). It allows you to explore and make your data available to collaborators via intuitive web-based interfaces. It provides tools to export your data in standard formats and tools to maintain datasets used in analysis. This is critical in ensuring reproducability of data analysis and openess.

> Germinate provides a single point of access for all background data on genetic resources collections and is therefore a valuable digital curation resource as well as offering essential continuity on how new data is recorded, archived, and made available to collaborators and communities. 

## What types of data does Germinate store? 

Germinate stores a number of different data types including: passport, phenotypic, field trial, pedigree, genetic, climatic, and geographic location data as well as user‐submitted annotations and images. Germinate is also under continual development and so new datatypes are added from time to time. For example, at the moment we are looking at developng tools to store data from UAV (drone) based imaging and phenotyping. 

## Where is Germinate developed? 

Germinate has been developed by the Information and Computational Sciences Department at the James Hutton Institute [just outside of Dundee in Scotland](https://www.google.com/maps/@56.4582505,-3.0706454,2500m/data=!3m1!1e3). We have been developing Germinate since around 2005 and in recent years there has been a significant improvement on the functionality that Germinate offers its users. For more information on the James Hutton Institute you can [have a look at our webpage](https://www.hutton.ac.uk).

From originally only storing a few markers and germplasm entries we now have databases with hundreds of thousands of plant lines and millions of SNP markers and phenotype data points.

We are also keen to get feedback and hear from users on how we can improve the platform. Originaly Germinate was created to meet the needs of barley and potato work being carried out in Scotland but has now expanded to cover 25 different crops from around the world. 

> [To see all the publicaly available Germinate databases click here](https://germinateplatform.github.io/get-germinate/#databases)

## Does Germinate support standards? 

Germinate is fully compliant with the [Multi‐Crop Passport Descriptors](https://www.bioversityinternational.org/e-library/publications/detail/faobioversity-multi-crop-passport-descriptors-v21-mcpd-v21/) developed by the FAO, the [Dublin Core](https://www.dublincore.org/) and we are developing support for data initiatives such as MIAPPE. Germinate aims and supports making data available using FAIR principles and we are working to include data object identifier (DOI) features and tools for datasets and germplasm. 

## Once my data is in Germinate how do I get it out? 

Germinate offers different formats to download your data from plain text format to formats specific for external analysis programs. One of our main underlying beliefs is that any data you put in – you can get back out again quickly and there are tools to give you an overview of the data that your database contains. We also offer a number of different export formats including Flapjack for graphical genotyping, Helium for pedigree data and HapMap for genotypic data. New export formats can be added based on demand so get in touch with us if there is something that you think can benefit your work.

## Can I install it myself? 

For this training you don't need to install anything, we have you covered!

If you do however want to have a go you can download Germinate from our [GitHub repository](https://github.com/germinateplatform/germinate-vue) or using a handy Docker image to get up and running quickly. You can even use it on your Raspberry Pi! 

If you just want to have a quick play about with the interface you can use one of the [publicly available databases](https://germinateplatform.github.io/get-germinate/#databases) or our [demo database](https://ics.hutton.ac.uk/germinate-demo/) which has examples of all data types using real, but anonomised data and a [fictional plant species](https://en.wikipedia.org/wiki/Cactuar). 



## Now watch this brief introductory video on Germinate

<a href="https://www.youtube.com/watch?v=w8CWSS2Whh4"><img src="https://img.youtube.com/vi/w8CWSS2Whh4/0.jpg" height="300px"></a>

## Setting up a Germinate user account (where required)

It is sometimes necessary to set up a user account to use Germinate databases, especially those that contain data that is not always public. This section will explain how to set up a user account for this training. 

While most Germinate databases are available to the public there may occasionally be the need to protect your database, perhaps while its being created or to share with collaborators for testing before getting ready to make your data public. This is one of Germinate's features and is incredibly useful.

In order to achieve this, Germinate allows you to password protect your installation so that only **authenticated users** can log into the system. This can of course be changed later and all data made public and user authentication removed almost entirely - user accounts are still used by administrators to access special Germinate features for uploading data and cutomising the user interface. 

So how do you access a Germinate database that has password protection. Firstly, you need to navigate to your Germinate page then enter your username and password details then click here to sign in. In this case <a href="">click here</a> to go to our demo database that we are using as part of this training. 

If you **don't have** a username and password, you can click on the "Register" button to register. This button is found when you try and access the training site at [https://ics.hutton.ac.uk/germinate-training](https://ics.hutton.ac.uk/germinate-training). Each Germinate installation may have specific terms and conditions that you need to agree to before you can get access to the data. Read then click to accept these terms and conditions then click next. If you already have another Germinate account that makes things bit simpler – all we need is your email and password. If not then you need to fill in your personal details then click register. 

> Germinate's privacy policy means that we do not provide any of your details to third parties. We only use your email address to send you password reminders and nothing else. You can request that your details are removed from the system by contacting us.

## A bit about passwords
In line with good practice, passwords should meet these minimum criteria:  
 > Passwords should be unguessable. There is an indicator below the password field showing how strong your password is. Try and make your password as strong as possible, choose a few words joined together such as a short phrase that is easy to remember but difficult to guess.

Your details will then be passed to the Germinate administrator for your database who can approve user accounts (in this case it will be automatically approved). In some instances this may take a few hours if accounts are manually checked but for this training you should be good to go now. If you lose your password, don't worry as we can reset that by clicking on the "forgot password?" link from the Germinate front page. A link which allows you to reset your password will then be sent to the email address you used to register on the system – follow this link to create a new password then log in as normal to the system. 

> We cannot remind you of what your password is. For security reasons, the way Germinate handles passwords means that we don't store unencrypted passwords and therefore have no way in knowing what your password was. If you loose your password use the Germinate interfaces "forgot password?" link to create a new secure password for your account.

Now that we have completed this section we can try some tasks to get you using the system.

## Germinate Tasks:
### Click on the questions to reveal the answers or more information.

1. <details><summary>Explore the Germinate homepage and look at the diversity of crops that we have data for and explore other Germinate resources that may be useful.</summary><a href="https://germinateplatform.github.io/get-germinate/">You can access the Germinate homepage here</a></details>

2. <details><summary>Go to the Germinate training database and register for a user account that we will use during this training.</summary>Remember and choose a password that is secure and check you have entered a valid email address.<br>The link to register is <a href="https://ics.hutton.ac.uk/germinate-training">https://ics.hutton.ac.uk/germinate-training</a></details>

3. <details><summary>Log into Germinate and make sure your username and password work.</summary>If you run into any problems then send us an email <a href="mailto:germinate@hutton.ac.uk">germinate@hutton.ac.uk</a> or if you have a demonstrator let them know!</details>

> It may be worth adding a bookmark to the Germinate training page.

Next Steps:  We have learned a bit about Germinate and how to access it, now [lets have a look at the main Germinate user interface in Session 2](session-2.html).


<br/>

> ## About
> This training has been created under the [Templeton World Charity Foundation, Inc.](https://www.templetonworldcharity.org/) Grant ID TWCF0400 *'Safeguarding crop diversity for food security: Pre-breeding complemented with Innovative Finance'* which is managed by the [Crop Trust](https://www.croptrust.org/). This training is free to use and released under a non-restrictive open source licence.

<div class="logos">
  <img src="img/crop-trust.svg" width="300" alt="Crop Trust">
  <img src="img/templeton.svg" width="300" alt="Templeton World Charity Foundation">
  <img src="img/best-crop.svg" width="300" alt="BEST-CROP">
  <img src="img/hutton.svg" width="300" alt="The James Hutton Institute">
</div>