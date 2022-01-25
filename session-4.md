<!-- Use these horrible HTML tag attributes because Markdown only supports limited HTML/CSS -->
<p align="center">
  <img src="img/germinate-square-name.svg" width="300" alt="Crop Trust">
</p>


# Session 4: Experiments, Datasets and other Data Resources

Germinate can hold large amounts of experimental data (millions of datapoints). These can include data from phenotypic trials, genotypic SNP (or other indexed polymorphism) data, chemical compound information and climate measurements. Germinate currently supports 3 levels of granularity for data. Individual data points (level 3) make up datasets (level 2). Datasets are assigned to experiments (level 1). So an experiment cotains one more more datasets and a dataset contains one or more datapoints. Figure 1 shows the hierarchey of data levels in Germinate.

<img src="session-4/4.png" width="45%">

***Figure 1 Germinate data levels***

Experiments are the overarching level of granularity. A dataset can only be assiged to one dataset. Experiments are accessed by clicking on the ***Experiments*** menu item on the left hand side Germinate menu.

<img src="session-4/4_1.png">

Using the Germinate Demo database we can see that there are 5 different experiments we have access to. If you look closely under the **Dataset types** column you will see that some of them have icons and numbers. The icons shows particular data types; climate, field trials, genotype and chemical compound data types. The number next to each icon shows the number of datasets in the experiment of that type. Take for example the **GWAS data** experiment. This has 2 field trial and 2 gentoype datasets contained within its experiment container. If you are not sure what each icon represents just hover your mouse over it and the description will be displayed in a popup.

Datasets allow experimental data recorded at the same time to be grouped together. An example would be all the trials data for a specific site in a specific year. An experiment allows the grouping of datasets into a logical unit so for example, all the trials data across multiple sites and years. These grouping allow data which is logically related to one another to be grouped together for easy searching and analysis.

Datasets are the smallest grouping of data in Germinate and represent a single unit of data like a single field trial. The datasets page shows all datasets stored in Germinate. Clicking on the dataset name will take you to the corresponding data export pages. The icon buttons at the right side of the table will reveal information about collaborators, dataset attributes and download options. 

Experiments group together coherent datasets into meaningful combinations. This way, field trials data can be linked to the corresponding climate data as well as any genotypic data that is linked to it. The dataset type column shows what types of datasets are contained in this experiment. 

Sometimes there is data that cannot be stored in Germinate directly. In those cases, the data can still be uploaded in any format and made available as direct downloads. This means that all your data is still available in a single location. 





## Tasks:

1. <details><summary>How many datasets are available in Germinate?</summary>Answer: There are <strong>7</strong> datasets available in the demo version of Germinate.

2. <details><summary>Of the datasets how many are genotypic datasets?</summary>Answer: <strong>2</strong></details>

