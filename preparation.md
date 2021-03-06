---
layout: default
title: Preparation
nav_order: 3
---

# Preparation
Preparation for this workshop will take about 60 to 90 minutes, depending on your experience with the tools used during this session.  
**To get the most of the workshop**, it is ***very important*** that you complete the OpenRefine and Jupyter Notebook setup, and at least work through some of the introductory modules. 

## OpenRefine
For this workshop, you will need [OpenRefine](https://openrefine.org/) and a web browser. Follow the [instructions](https://librarycarpentry.org/lc-open-refine/setup.html) provided by the Library Carpentry to install OpenRefine on your system (whether it is Windows, Mac, or Linux).
- **NOTE**: When opening OpenRefine for the first time in a Mac, you may need to open your security preferences and permit OpenRefine to run. See [Apple Support's Open a Mac app from an unidentified developer](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unidentified-developer-mh40616/mac)


Once you have installed OpenRefine, please complete **modules 1-4** of the [Library Carpentry OpenRefine lesson](https://librarycarpentry.org/lc-open-refine/) to familiarize yourself with basic OpenRefine operations.

To save time during the workshop, please create the demonstration projects ahead of time.

### Project 1: Soul of Reason metadata
1. Download the [Soul of Reason metadata](assets/files/SoR_metadata.csv)
2. On the OpenRefine home screen, select the `Create Project` tab, upload the CSV, and click "Next"
3. On the preview screen, ensure that:
	* `Character encoding` is set to UTF-8
	* `Columns are separated by` is set to comma
	* `Trim leading & trailing whitespace...` is checked
	* `Parse next 1 line(s) as column headers` is checked
	* `Use character " to enclose cells...` is checked
	* `Store blank rows` is checked
	* `Store blank cells as nulls` is checked
4. Click `Create Project`

![Configuration for creating the metadata project](assets/img/SoR_metadata_create.png)

### Project 2: Soul of Reason transcript
1. Download the [Soul of Reason transcript](assets/files/RG_9_8_184_01.draft.en.txt)
2. On the OpenRefine home screen, select the `Create Project` tab, upload the txt file, and click "Next"
3. On the preview screen, ensure that:
	* `Parse data as` is set to Line-based text files
	* `Character encoding` is set to UTF-8
	* `Store blank rows` is *unchecked*
	* `Store blank cells as nulls` is checked
	* *Note that you can import multiple text files into a single OpenRefine project; make sure to check ???Store file source??? when creating the project so that you can retain from which file data originates.*
4. Click `Create Project`

![Configuration for creating the transcript text project](assets/img/OpenRefine_SoR_create.png)

### Project 3: OCR text file
1. Download the [OCR text file](assets/files/25515893.txt) of ???Some Comments on Correggio in Connection with His Pictures in Dresden??? by Bernard Berenson. *Article downloadable from [JSTOR](https://www.jstor.org/stable/25515893)*
2. On the OpenRefine home screen, select the `Create Project` tab, upload the txt file, and click "Next"
3. On the preview screen, ensure that:
	* `Parse data as` is set to Line-based text files
	* `Character encoding` is set to UTF-8
	* `Store blank rows` is *unchecked*
	* `Store blank cells as nulls` is checked
4. Click `Create Project`

![Configuration for creating the OCR text project](assets/img/25515893_txt_create.png)

If you prefer, you may also open pre-made OpenRefine projects provided at the links below:

* Soul of Reason metadata OpenRefine project ([SoR_metadata](assets/files/SoR_metadata.openrefine.tar.gz))
* Soul of Reason transcript OpenRefine project ([RG_9_8_184_01-draft-en-txt](assets/files/RG_9_8_184_01-draft-en-txt.openrefine.tar.gz))
* OCR text file of ???Some Comments on Correggio in Connection with His Pictures in Dresden??? by Bernard Berenson OpenRefine project ([25515893-txt](assets/files/25515893-txt.openrefine.tar.gz))

Download the tar.gz files and load them in the `Import` tab on OpenRefine's home screen:

![OpenRefine import tab](assets/img/OpenRefine_import.png)

## Jupyter Notebooks & Python
For our exploration of programmatic approaches to text analysis with Python, we'll be using [Jupyter Notebook](https://jupyter.org/), and the very excellent [Constellate](https://constellate.org/) tutorials. To ensure that you have the base knowledge required for success in this workshop, it is: 
- *Required* that you complete the [Getting Started with Jupyter Notebooks](https://ithaka.github.io/tdm-notebooks/getting-started-with-jupyter.html) lesson, 
- *strongly recommended* that you work through the [Python Basics 1](https://ithaka.github.io/tdm-notebooks/python-basics-1.html) lesson. 

---


When you have completed the pre-workshop tasks, proceed to the [introductory presentation](introduction) to explore the key concepts. 

<!--

# Workshop preparation 

Preparation for this tutorial consists of two steps: [Getting the data](#get-the-data) and [Getting the software](#get-the-software). Follow the steps below. 
  
## Get the data

You will have an opportunity to download the data during the workshop; however, if you would like to do so ahead of time, it can be downloaded [here](https://github.com/scds/intro-tableau/raw/main/data/humdata_GHGEmissionsGES.xlsx).

## Get the software
This hands-on workshop uses [**Tableau**](https://www.tableau.com/), a software application for data visualization. We ask that you download Tableau in advance of the workshop to be able to participate in it to the fullest extent.

You have three options for downloading Tableau:
1. [Tableau Public](https://public.tableau.com/en-us/s/) (limited version)
2. A 14-day trial of [Tableau Desktop](https://www.tableau.com/products/trial)
3. A 1-year instructor or student license for [Tableau Desktop for academic purposes](https://www.tableau.com/academic/teaching) 

The three options will be discussed further during the workshop; for now, we recommend Tableau Public or the 14-day trial of Tableau Desktop. Please contact the [Sherman Centre](mailto:scds@mcmaster.ca) if you have any difficulties downloading or opening the software.

-->
