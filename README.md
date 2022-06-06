# Hydro-JULES Summer/Winter School
## DataLabs Sessions

Welcome to the Hydro-JULES Summer/Winter DataLab sessions. Please go to [Hydro-JULES school webpage](https://hydro-jules.org/hydro-jules-school) to find more infomration on the school and the sessions. In this GitHub repository you will find all the resources used during these sessions. The DataLabs sessions will be held in the DataLabs room in the [Gather.Town](https://gather.town/). During the DataLab sessions, there will have live presentations, practical demostrations and tutor avaialble to answer questions. If you miss the live sessions, there are a number of video presentations placed around the DataLabs room in Gather.Town, which you can follow instead; these video presentations are also linked within the specific training notebooks provided in this GitHub repository. 

In this document we provide a step-by-step guide to:
1. [Overview and introduction to DataLabs](#overview_datalabs)
2. [Importing the GitHub repository into DataLabs](#importing_repository)
3. [Introduction to the repository notebooks](#introduction_notebooks)

<a id="overview_datalabs"></a>
### 1. Overview and introduction to DataLabs
[DataLabs](https://datalab-docs.datalabs.ceh.ac.uk/index.html) is a NERC funded UKCEH based cloud based collaborative environment for developing data pipelines and analytical methods, that provides us with a secure area to collaborate with your colleagues around the world. To use the DataLabs platform, you would need to first get an account with DataLabs and also request access for the HydroJules project on DataLabs (instructions provided with the Hydro-JULES school registration????). After you have your username and password, please follow the steps given below to set up your very own DataLabs lab. 

1. Please go to the webpage https://datalab.datalabs.ceh.ac.uk/, and click on the “Log In” button shown with the red arrow.
![image](https://user-images.githubusercontent.com/41617337/171423203-7822c5ff-629f-48e8-99ea-2fc41f43de34.png)

2. Please log in to the ceh-datalab-app (shown with the red arrow) with your created username and password. 
![image](https://user-images.githubusercontent.com/41617337/171423345-e9a5f243-8794-42ed-8ab2-779ce26203fd.png)

3. Click on “Open” tab for the HydroJules Project shown with the red arrow.
![image](https://user-images.githubusercontent.com/41617337/171425909-f4f1dceb-4011-4637-b4a6-727e0241934f.png)

4.	Please click on “Notebooks” tab (shown with the red arrow), in the left hand side panel under “Analysis” section.
![image](https://user-images.githubusercontent.com/41617337/171426012-f1dfef7b-d77b-419f-89e0-61b5bf14f180.png)

5. Please click on the “Create Notebooks” tab, on the right side of the webpage, shown with the red arrow. This will actually create a JupyterLab for you, which can host multiple notebooks. Fill in the options as per step 6 below.
![image](https://user-images.githubusercontent.com/41617337/171426195-6d032164-9c57-4eb5-b043-5e05f20dcaf0.png)

6. Fill in the following information in the pop up, scroll down if required. 
  * Display Name – anything that you like
  * Type – select “JupyterLab” option
  * URL Name – any word (ideally similar to the Display Name without any space, dashes or underscore)
  * Data Store to Mount – select “initialhj” option
  * Description – a few words describing the JupyterLab
  * Sharing Status – select “Private” option
  * Assets – please leave empty or do not select any option

    Then click on the “Create” tab at the bottom, shown with the red arrow. 
![image](https://user-images.githubusercontent.com/41617337/171426272-0db9bfb9-a567-4375-b746-29d992f9581c.png)
    
7. You should then see a new lab in your “Notebooks” page, with a blue “Requested” tab, shown with the red arrow. Please wait, this should turn into a green “Ready” tab in a few minutes (you may need to refresh your browser window).
![image](https://user-images.githubusercontent.com/41617337/171426411-7fee9428-57bb-4a28-a6b7-b860b487080e.png)

8. Please click on the “Open” tab (shown with the red arrow), associated with your newly created lab. 
![image](https://user-images.githubusercontent.com/41617337/171426514-f3339f82-3846-4ad3-b8f3-fbaf6ccb8e3c.png)

9. This opens a new browser tab with your JupyterLab (shown with a red arrow). Sometimes you may see a “Build Recommended” pop up. If it appears, please click on the “Build” button shown with another red arrow. 
![image](https://user-images.githubusercontent.com/41617337/171426657-8956dc63-3631-4686-83e7-13b28aa8e0f3.png)

<a id="importing_repository"></a>
### 2. Importing the GitHub repository into DataLabs

10. Please click on the gitclone icon shown with the red arrow. 

11. Please add the following link address "[git@github.com:hydro-jules/school.git](git@github.com:hydro-jules/school.git)" (Hydro-JULES School GitHub repository) to the "Clone a repo" pop up, and then press the clone button (shown with red arrows). 

12.	 Now you can see all the 7 files in your lab’s left hand panel. You can double click on any notebook to launch it. The suggested order for use of these notebooks is:
1)	netCDF-examples.ipynb - this notebook walks through the structure of a netCDF format data file, and shows how to access data, and plot it, using the netCDF4 library
2)	cfpython_examples.ipynb - this notebook demonstrates how to use the CF-Python library, which has a number of useful additional features for use with “CF compliant” netCDF files.
3)	exercise_answers – this notebook contains some answers to questions set in the cfpython_examples notebook
4)	unifhy_demo.ipynb - this notebook walks through running a simple set of hydrological models using the Hydro-JULES modelling framework
5)	unifhy_exercise1.ipynb – this contains an exercise on using the modelling framework
6)	unifhy_exercise2.ipynb – another exercise on the modelling framework
7)	modelvsobserved_examples.ipynb – this notebook demonstrates how to compare observed station data (in csv format) against modelled gridded dataset (in netCDF format). 

<a id="introduction_notebooks"></a>
### 3. Introduction to the repository notebooks
