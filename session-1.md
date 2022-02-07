<!-- Use these horrible HTML tag attributes because Markdown only supports limited HTML/CSS -->
<p align="center">
  <img src="img/germinate-square-name.svg" width="300" alt="Crop Trust">
</p>


# Session 1: Getting Started and Introduction to Germinate

## Welcome to Germinate.

We have created a series of Germinate training sessions that can be used to get a handle on how to use Germinate and get hands on training on using the tools and features that Germinate offers. We will use a number of different Germinate instances (databases) throughout this training to highlight concepts. It is incredibly important to stress that where training invovles adding or editing data that **you cannot break anything** by undertaking this training - just go for it, try things, and see how Germinate works!

We have broken down each training session into distinct sections. Most will start with a description of what the session will contain, some will have YouTube videos that explain and demonstrate the concepts we want to convey, some will have have additional information then a series of tasks and answers that will let you get experience in using Germinate using real data.

In each section where there are example files that we are using then we will link to these so you can download to your computer.

This training has been designed for you to carry out at your own pace. Each section is self contained and while we recommend that you carry each out in series, you can do this training at your own pace and come back to sections if you are unsure or just want to try the user excersises again at the end of each section.

## Important Germinate Links
For all information on Germinate take a look at https://germinateplatform.github.io/get-germinate/ which will give you an overview of the project as well as links to where you can access the different publicly available Germinate databases we have and how to access the code that underpins Germinate if you want to contribute to the project.

If you have any questions about Germinate or just want to chat through the benefits and features that it can offer please just drop us an email to germinate@hutton.ac.uk. You can also log bugs and feature requests on our Github page https://github.com/germinateplatform

There are two main Germinate publications that are well worth reading and will give you a bit of background to the project.

> Shaw, P.D., Raubach, S., Hearne, S.J., Dreher, K., Bryan, G., McKenzie, G., Milne, I., Stephen, G. and Marshall, D.F. (2017), Germinate 3: Development of a Common Platform to Support the Distribution of Experimental Data on Crop Wild Relatives. Crop Science, 57: 1259-1273. https://doi.org/10.2135/cropsci2016.09.0814

> Raubach, S, Kilian, B, Dreher, K, et al. From bits to bites: Advancement of the Germinate platform to support genetic resources collections and prebreeding informatics for crop wild relatives. Crop Science. 2021; 61: 1538– 1566. https://doi.org/10.1002/csc2.20248

### So lets get started!

## Introduction to Germinate

#### Why use Germinate? 
It's often difficult trying to get a handle on large datasets and what they contain. The complexity and volumes of data are challenging to visualize so tools which help researchers do this are important in trying to get the most out of our data. Traditionally we may have used tools such as a spreadsheet to try and work with data, which is fine, but had its limitations. With datasets getting larger and larger we need tools that can efficiently handle these volumes of data and allow us to explore and interact with it. This is just not possible with spreadsheets.

This is where Germinate can help. Germinate allows you to manage data from your collections in a standard and <a href="https://www.go-fair.org/fair-principles/">FAIR way</a>. It allows you to explore and make your data available to collaborators via intuitive web-based interfaces. It provides tools to export your data in standard formats and tools to maintain datasets used in analysis. This is critical in ensuring reproducability of data analysis and openess.

> Germinate provides a single point of access for all background data on genetic resources collections and is therefore a valuable digital curation resource as well as offering essential continuity on how new data is recorded, archived, and made available to collaborators and communities. 

### What types of data does Germinate store? 

Germinate stores a number of different data types including: passport, phenotypic, field trial, pedigree, genetic, climatic, and geographic location data as well as user‐submitted annotations and images. Germinate is also under continual development and so new datatypes are added from time to time. For example, at the moment we are looking at developng tools to store data from UAV (drone) based imaging and phenotyping. 

### Where is Germinate developed? 

Germinate has been developed by the Information and Computational Sciences Department at the James Hutton Institute just outside of Dundee in Scotland. We have been developing Germinate since around 2005 and in recent years there has been a significant improvement on the functionality that Germinate offers its users. 

From originally only storing a few markers and germplasm entries we now have databases with hundreds of thousands of plant lines and millions of SNP markers and phenotype data points.

We are also keen to get feedback and hear from users on how we can improve the platform. Originaly Germinate was created to meet the needs of barley and potato work being carried out in Scotland but has now expanded to cover 25 different crops from around the world. 

> <a href="https://germinateplatform.github.io/get-germinate/#databases">To see all the publicaly available Germinate databases click here</a>

### Does Germinate support standards? 

Germinate is fully compliant with the <a href="https://www.bioversityinternational.org/e-library/publications/detail/faobioversity-multi-crop-passport-descriptors-v21-mcpd-v21/">Multi‐Crop Passport Descriptors</a> developed by the FAO and we are developing support for data initiatives such as MIAPPE and Dublin Core. Germinate aims and supports making data available using FAIR principles and we are working to include data object identifier (DOI) features and tools for datasets and germplasm. 

### Once my data is in Germinate how do I get it out? 

Germinate offers different formats to download your data from plain text format to formats specific for external analysis programs. One of our main underlying beliefs is that any data you put in – you can get back out again quickly and there are tools to give you an overview of the data that your database contains. We also offer a number of different export formats including Flapjack for graphical genotyping, Helium for pedigree data and HapMap for genotypic data. New export formats can be added based on demand so get in touch with us if there is something that you think can benefit your work.

### Can I install it myself? 

For this training you don't need to install anything, we have you covered!

If you do however want to have a go you can download Germinate from our <a href="https://github.com/germinateplatform/germinate-vue">GitHub repository</a> or using a handy Docker image to get up and running quickly. You can even use it on your Raspberry Pi! 

If you just want to have a quick play about with the interface you can use one of the <a href="https://germinateplatform.github.io/get-germinate/#databases">publicly available databases</a> or our <a href="https://ics.hutton.ac.uk/germinate-demo/#/">demo database</a> which has examples of all data types using real, but anonomised data and a <a href="https://en.wikipedia.org/wiki/Cactuar">fictional plant species</a>. 

### That’s great how can I get more information? 

Contact us, please get in touch and we can give an extended demo or talk you through using Germinate with your data or how you can help be part of the Germinate community. Contact details are at the top of each of these training sections.

## Now watch this brief introductory video on Germinate

<a href="https://www.youtube.com/watch?v=w8CWSS2Whh4"><img src="https://img.youtube.com/vi/w8CWSS2Whh4/0.jpg" width="25%"></a>

## Setting up a Germinate user account (where required)

It is sometimes necessary to set up a user account to use Germinate databases, especially those that contain data that is not always public. This section will explain how to set up a user account for this training. 

While most Germinate databases are available to the public there may occasionally be the need to protect your database, perhaps while its being created or to share with collaborators for testing before getting ready to make your data public. This is one of Germinate's features and is incredibly useful.

In order to achieve this, Germinate allows you to password protect your installation so that only **authenticated users** can log into the system. This can of course be changed later and all data made public and user authentication removed almost entirely - user accounts are still used by administrators to access special Germinate features for uploading data and cutomising the user interface. 

So how do you access a Germinate database that has password protection. Firstly, you need to navigate to your Germinate page then enter your username and password details then click here to sign in.  In this case <a href="">click here</a> to go to our demo database that we are using as part of this training. 

If you don’t have a username and password, you can click on the "Register" button to register. Each Germinate installation may have specific terms and conditions that you need to agree to before you can get access to the data. Click to accept these terms and conditions then click next. If you already have another Germinate account that makes things bit simpler – all we need is your email and password. If not then you need to fill in your personal details then click register. 

> Germinate privacy policy means that we do not provide any of your details to third parties. We only use your email address to send you password reminders and nothing else.

> Passwords should meet these minimum criteria:  
  Passwords should be unguessable. There is an indicator below the password field showing how strong your password is. Try and make your password as strong as possible, choose a few words joined together such as a short phrase that is easy to remember but difficult to guess.

Your details will then be passed to the Germinate administrator for your database who can approve user accounts, in some instances this may take a few hoursif accounts are manually checked but for this training we will approve your account now. If you lose your password, don’t worry as we can reset that by clicking on the "forgot password?" link from the Germinate front page – a link which allows you to reset your password will then be sent to the email address you used to register on the system – follow this link to create a new password then log in as normal to the system. 

> We cannot tell you what your password is, we just don't know as we only store a hashed version of it. If you loose your password use the Germinate interfaces "forgot password?" link to create a new secture password for your account.

## Tasks:
#### Click on the questions to reveal the answers or more information.

1. <details><summary>Explore the Germinate homepage and look at the diversity of crops that we have data for.</summary><a href="https://germinateplatform.github.io/get-germinate/">You can access the Germinate homepage here</a></details>

2. <details><summary>Go to this link and register for a user account that we will use in this training.</summary>Remember and choose a password that is secure and check you have entered a valid email address</details>

## We have learned a bit about Germinate and how to access it, now lets have a look at the main Germinate user interface in Session 2

<br/>

> ### About
> This training has been created under the <a href="https://www.templetonworldcharity.org/">Templeton World Charity Foundation, Inc.</a> Grant ID TWCF0400 *'Safeguarding crop diversity for food security: Pre-breeding complemented with Innovative Finance'* which is managed by the <a href="https://www.croptrust.org/">Crop Trust</a>. This training is free to use and released under a non-restrictive open source licence.

<table bgcolor="white">
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
