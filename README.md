## Introduction
This page is the official website of the Strawberry Digital Images (StrawDI) data set, which contains 8000 images of strawberries taken in different plantations in the province of Huelva, Spain. The images were taken throughout the strawberry harvesting period under different conditions of brightness, angle and distance. 

The capture device used was a Samsung Galaxy S7 Edge smartphone attached to an extendable arm. The images have a 4032 x 3024 resolution and are stored in JPEG format.

### Contributors
- [Isaac Pérez](mailto:isaac.perez@dci.uhu.es)
- [Diego Marin](mailto:diego.marin@diesia.uhu.es)
- [Estefanía Cortés-Ancos](estefania.cortes@diesia.uhu.es)
- [Manuel Emilio Gegúndez Arias](gegundez@uhu.es)

## StrawDI_Db1
From the total set of images that make up the StrawDI data set, 3100 images have been selected at random. For each of these images a ground truth labelled image has been manually generated containing the individual segmentation of all the strawberries appearing in the image.

To reduce the computational demands on the models, the images have been rescaled to 1008 x 756 and stored in PNG format. This set of images constitutes the __StrawDI_Db1__ database. This database is divided into train (2800 images), validation (100 images) and test (200 images) subsets.

### Labeling Policy
The image labelling process has been validated by three blind reviews of the data with four reviewers, thus guaranteeing the quality of the segmentations. The criterion followed in the labelling process consists of creating as accurate a mask as possible for each of the strawberries appearing in the image, including extreme cases such as strawberries that are almost imperceptible due to distance, occlusions, being at the edges of the image or still unripe.

### Examples
Below are examples of our high quality pixel annotations. Overlayed colors encode individual instances of strawberries. 

Original image             |  Original image with annotations
:-------------------------:|:-------------------------:
![](https://github.com/strawDI/strawDI.github.io/blob/master/2647.png)  |  ![](https://github.com/strawDI/strawDI.github.io/blob/master/2647m.png)
![](https://github.com/strawDI/strawDI.github.io/blob/master/2663.png)  |  ![](https://github.com/strawDI/strawDI.github.io/blob/master/2663m.png)
![](https://github.com/strawDI/strawDI.github.io/blob/master/2780.png)  |  ![](https://github.com/strawDI/strawDI.github.io/blob/master/2780m.png)
![](https://github.com/strawDI/strawDI.github.io/blob/master/404.png)  |  ![](https://github.com/strawDI/strawDI.github.io/blob/master/404m.png)
![](https://github.com/strawDI/strawDI.github.io/blob/master/544.png)  |  ![](https://github.com/strawDI/strawDI.github.io/blob/master/544m.png)


## Using the database
Please include the following acknowledgment…
```
Kindly provided by the StrawDI Team (see https://strawdi.github.io/).
```
…as well as a reference to the following papers:

`Unpublished`

To inform us of a publication using StrawDI_Db1, or to give us any other feedback, please contact [Isaac Pérez](mailto:isaac.perez@dci.uhu.es) or [Diego Marin](mailto:diego.marin@diesia.uhu.es).

## Download
To download the database: [StrawDI_Db1](https://strawdi.github.io/)

## License
This dataset is made freely available to academic and non-academic entities for non-commercial purposes such as academic research, teaching, scientific publications, or personal experimentation. Permission is granted to use the data given that you agree:

1. That the dataset comes “AS IS”, without express or implied warranty. Although every effort has been made to ensure accuracy, we (Isaac Perez-Borrero, Diego Marin, Manuel E. Gegundez-Arias and Estefanía Cortés-Ancos) do not accept any responsibility for errors or omissions.
2. That you include a reference to the StrawDI_Db1 Dataset in any work that makes use of the dataset. For research papers, cite our preferred publication as listed on [Using the database](#using-the-database) Section.
3. That you do not distribute this dataset or modified versions. It is permissible to distribute derivative works in as far as they are abstract representations of this dataset (such as models trained on it or additional annotations that do not directly include any of our data) and do not allow to recover the dataset or something similar in character.
4. That you may not use the dataset or any derivative work for commercial purposes as, for example, licensing or selling the data, or using the data with a purpose to procure a commercial gain.
5. That all rights not expressly granted to you are reserved by us (Isaac Perez-Borrero, Diego Marin, Manuel E. Gegundez-Arias and Estefanía Cortés-Ancos).

---------------------------------------------------------------------------------------------------
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/strawDI/strawDI.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
