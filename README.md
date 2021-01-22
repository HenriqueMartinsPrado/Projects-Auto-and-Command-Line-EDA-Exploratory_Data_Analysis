## PROJECT AUTO AND COMMAND LINE EXPLORATORY DATA ANALYSIS (EDA)

### Table of Contents

1. [Installations](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [How to Interact with my project / Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## 1. Installations <a name="installation"></a>
There some libraries that you should install to run this python code shared in jupyter notebook. They are:

	1. pandas
	2. numpy
	2. pandas_profiling
	3. sweetviz
	4. autoviz
	5. matplotlib
	6. seaborn
		
<p align="justify">You can install all of them using pip install <librarie_name> or you can add one more cell in jupyer notebook e write !pip install <librarie_name>
All module used in this project can be see below. They were extracted from the libraries mentioned above.</p>

	import pandas as pd
	import numpy as np
	import pandas_profiling
	import sweetviz as sv
	from autoviz.AutoViz_Class import AutoViz_Class
	import matplotlib.pylab as plt
	import seaborn as sns
	
Beisdes, only to complement, I developed the project using python version 3.8.5. You check the python version with this command:

	!python --version	

## 2. Project Motivation<a name="motivation"></a>

<p align="justify">The motivation to develop this project was to create ways to provide a quick overview of a data set through command lines developed with the Python language and the pandas_profiling and sweetviz libraries. These approaches allow for speed gains in the understanding and preparation of data within a pipeline and in the wake of projects. Also, the libraries used allow reports to be generated so that they can be shared with all team members involved in the data project and provide a dissemination of knowledge.</p>

## 3. File Descriptions<a name="files"></a>

This project consists of the files below:

    ├── dataset																
	│   ├── craigslistVehicles.csv
	│   ├──	EDA - Pandas Profiling - Carros OLX.html	
	│   ├──	EDA - Sweetviz - Carros OLX.html
    │   ├── Dataset_Carros_OLX.csv           			
    │   └── kaggle   														# Folder where were stored datasets from Kaggle.
    │       ├── go.html                      			
    │       └── master.html                  			
    │
	├── plots             													# Plots generated from EDA reports      			
	│   ├── BarPlots Average_Fare_by_Embarked_(Ascending).png
	│   ├── BarPlots Average_Fare_by_Parch_(Ascending).png
	│   ├── BarPlots Average_Fare_by_Pclass_(Ascending).png
	│   ├── BarPlots Average_Fare_by_Sex_(Ascending).png
	│   ├── BarPlots Average_Fare_by_SibSp_(Ascending).png
	│   ├── BarPlots Average_Fare_by_Survived_(Ascending).png
	│   ├── BarPlots Average_{each_conti}_by_{cats[k]}_(Ascending).png
	│   ├── BoxPlots.png
	│   ├── DistPlot.png
	│   ├── DistPlots.png
	│   ├── HeatMap.png
	│   ├── PairScatterPlots.png
	│   ├── PairWiseScatterPlots.png
	│   ├── PivotPlots.png
	│   ├── ScatterPlots.png
	│
    ├── Auto-EDA.ipynb														# EDA using pandas_profling and also sweetviz	
	│
    ├── Command_Analise_EDA.ipynb											# EDA using command line using python language as well

<ul>		
	<li><p align="justify">Web_Scraping_OLX_Carros: In this file you will find all code developed in python such as the organization and use of the phases to create the web scraping.</p>
	<li><p align="justify">Exploratory Data Analysis (EDA) files: Here, you will find the files generated using two approaches of exploratory data analysis. They are: EDA - Dados de Anúncio dos carros da OLX.html and EDA - Sweetviz - Dados de Anúncio dos carros da OLX.html</p>
	<li><p align="justify">Folder Output: This folder contains the result of the web scraping where the data is saved in the file dataset.csv. In the img folder, the images of each car extracted from the captured ads can be found.</p>
	<li>Report of Web_Scraping_OLX_Carros: In this file, you can check the code developed as well as a report.
</ul>

## 4. How to Interact with my project / Results<a name="results"></a>

<p align="justify">To interact with this project, just open the jupyter notebook called Web_Scraping_OLX_Carros.ipynb and run the cell with the codes created. A table will be generated with the columns: Value, Title, Mileage, Exchange, Fuel and Location.</p>

## 5. Licensing, Authors, Acknowledgements, etc.<a name="licensing"></a>

<ul>
	<li><p align="justify">https://www.alura.com.br/conteudo/web-scraping-data-science-python</p>
</ul>
