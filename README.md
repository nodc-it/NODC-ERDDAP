# NODC ERDDAP
This repository is dedicated to the current [NODC's ERDDAP](https://nodc.ogs.it/erddap/index.html) installation (v2.18). 

## A quick walk through
This is how the homepage looks like:
<img width="936" alt="nodc_home_erddap" src="https://user-images.githubusercontent.com/108474725/216566127-7cf3f415-7d5a-4464-9e12-f8aed2db6852.png">

Let’s now search the database for specific data. Let’s search for temperture data in the Adriatic Sea from 2021.
- Type in search box: temperature “Adritic Sea” 2021. 
This is a full text search, just like Google, use white spaces in between words and double quotes “” around phrases.
<img width="945" alt="search_e2m3a" src="https://user-images.githubusercontent.com/108474725/216638165-98b46e62-2d97-4916-8edb-7f9ae650bee9.png">

### Dataset information
Within the search results you have access to information about each dataset to help you decide which dataset is useful for your application.
The listing (pictured above) gives access to a lot of information about the dataset. In a browser, try the following:
 
- Mouse over the question mark ? under Summary to get an overview of the dataset.
- Click “Background info” to get more complete information from the data provider about the dataset. Now go back to the search results page.
- Click the "M" under “ISO,Metadata” to see all of the dataset metadata. A lot of information is displayed.

These standardised variables are important for the dataset to be able to be “read” by other end-users and machines.

### Subsetting data
Click "data":
<img width="1152" alt="subsetting" src="https://user-images.githubusercontent.com/108474725/216644596-c00e7f6b-c26a-4748-8c3b-33cdbdc67d1c.png">

### Create a graph
ERRDAP also provides a graph function for your datasets. Click "graph":
<img width="697" alt="graph" src="https://user-images.githubusercontent.com/108474725/216645374-db60fbc9-e770-4e58-8001-b9dc647f8141.png">

### Google dataset search
Open google dataset search: [https://datasetsearch.research.google.com/](https://datasetsearch.research.google.com/)
Search for the dataset id of the dataset: <span style="color:green;"> E2M3A_TS </span>
<img width="927" alt="google" src="https://user-images.githubusercontent.com/108474725/216638997-d5f1bc34-8f02-465e-87dc-1cdbad9cf554.png">

## Key points: 
- Searching an ERDDAP data catalog can be done using a web page
- Constraints can be added to a dataset search
- ERDDAP is a tool and many repositories can have an ERDDAP server, which means that there are many erddap servers around.
- You can search 2 types of data, also called protocols: tabledap & griddap
- A dataset in ERDDAP can be downloaded in many different file types, based on what you need.
- You can subset a dataset based on constraining the variables.

