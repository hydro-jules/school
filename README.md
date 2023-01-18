# Hydro-JULES Summer/Winter School
## DataLabs Sessions

Welcome to the Hydro-JULES Summer/Winter DataLab sessions. Please go to [Hydro-JULES school webpage](https://hydro-jules.org/hydro-jules-school) to find more infomration on the school and the sessions. In this GitHub repository you will find all the resources used during these sessions. The DataLabs sessions will be held in the DataLabs room in the [Gather.Town](https://gather.town/). During the DataLab sessions, there will have live presentations, practical demostrations and tutor avaialble to answer questions. If you miss the live sessions, there are a number of video presentations placed around the DataLabs room in Gather.Town, which you can follow instead; these video presentations are also linked within the specific training notebooks provided in this GitHub repository.

The GitHub repository and the associated instructions in the README.md are written for the training sessions on DataLabs during the Hydro-JULES Summer/Winter School. However, please note that this GitHub repository is freely available to use, even after the Hydro-JULES Summer/Winter School is completed and without the DataLabs access. This repository can be cloned to your own local/remote workspace and you can continue the training sessions. To be able to work on your own wokspace, please make sure you have all the required python packages installed (please see the [following](https://ncas-cms.github.io/cf-python/installation.html#operating-systems) operating system requirements for cf-python package). You would also need to have access to the datasets used in the notebooks. Please contact [Matt Fry](mailto:mfry@ceh.ac.uk) or [Amulya Chevuturi](mailto:amuche@ceh.ac.uk) to get a copy of the required input data. Please do remember to change the path of the input data in the notebooks, when you use this repository on your own workspace.  

In this document we provide a step-by-step guide to:

i. [Overview and introduction to DataLabs](#overview_datalabs)

ii. [Importing the GitHub repository into DataLabs](#importing_repository)

iii. [Introduction to the repository notebooks](#introduction_notebooks)

<a id="overview_datalabs"></a>
### i. Overview and introduction to DataLabs
[DataLabs](https://datalab-docs.datalabs.ceh.ac.uk/index.html) is a NERC funded UKCEH based cloud based collaborative environment for developing data pipelines and analytical methods, that provides us with a secure area to collaborate with your colleagues around the world. You can refer to this [video](https://www.youtube.com/watch?v=n68X8J4gj6Q) by Matt Fry, which has a brief introduction to DataLabs.

To use the DataLabs platform, you would need to first get an account with DataLabs and also request access for the HydroJules project on DataLabs (instructions provided in an email sent out before the Hydro-JULES school). After you have your username and password, please follow the steps given below to set up your very own DataLabs lab. 

1. Please go to the webpage https://datalab.datalabs.ceh.ac.uk/, and click on the “Log In” button shown with the red arrow.
![image](https://user-images.githubusercontent.com/41617337/171423203-7822c5ff-629f-48e8-99ea-2fc41f43de34.png)

2. Please log in to the ceh-datalab-webpage (shown with the red arrow) with your created username and password. 
![image](https://user-images.githubusercontent.com/41617337/171423345-e9a5f243-8794-42ed-8ab2-779ce26203fd.png)

3. Click on “Open” tab for the HydroJules Project shown with the red arrow.
![image](https://user-images.githubusercontent.com/41617337/171425909-f4f1dceb-4011-4637-b4a6-727e0241934f.png)

4.	Please click on “Notebooks” tab (shown with the red arrow), in the left hand side panel under “Analysis” section.
![image](https://user-images.githubusercontent.com/41617337/171426012-f1dfef7b-d77b-419f-89e0-61b5bf14f180.png)

5. Please click on the “Create Notebooks” tab, on the right side of the webpage, shown with the red arrow. This will actually create a JupyterLab for you, which can host multiple notebooks. Fill in the options as per step 6 below.
![image](https://user-images.githubusercontent.com/41617337/171426195-6d032164-9c57-4eb5-b043-5e05f20dcaf0.png)

6. Fill in the following information in the pop up, scroll down if required. 
  * *Display Name* – anything that you like
  * *Type* – select “JupyterLab” option
  * *URL Name* – any word (ideally similar to the Display Name without any space, dashes or underscore)
  * *Data Store* to Mount – select “initialhj” option
  * *Description* – a few words describing the JupyterLab
  * *Sharing Status* – select “Private” option
  * *Assets* – please leave empty or do not select any option

   Then click on the “Create” tab at the bottom, shown with the red arrow. 
![image](https://user-images.githubusercontent.com/41617337/171426272-0db9bfb9-a567-4375-b746-29d992f9581c.png)
    
7. You should then see a new lab in your “Notebooks” page, with a blue “Requested” tab, shown with the red arrow. Please wait, this should turn into a green “Ready” tab in a few minutes (you may need to refresh your browser window).
![image](https://user-images.githubusercontent.com/41617337/171426411-7fee9428-57bb-4a28-a6b7-b860b487080e.png)

8. Please click on the “Open” tab (shown with the red arrow), associated with your newly created lab. 
![image](https://user-images.githubusercontent.com/41617337/171426514-f3339f82-3846-4ad3-b8f3-fbaf6ccb8e3c.png)

9. This opens a new browser tab with your JupyterLab (shown with a red arrow). Sometimes you may see a “Build Recommended” pop up. If it appears, please click on the “Build” button shown with another red arrow. 
![image](https://user-images.githubusercontent.com/41617337/171426657-8956dc63-3631-4686-83e7-13b28aa8e0f3.png)

<a id="importing_repository"></a>
### ii. Importing the GitHub repository into DataLabs

10. Once you are in your JupyterLab in the new browser, please scroll completely down (red downward arrow) in the "Launcher" section (left facing red arrow).
![image](https://user-images.githubusercontent.com/41617337/175516809-f444be36-e2e2-443c-8b54-5e29d4393270.png)

11. After you scroll down you can see a "Terminal" tab (red box) in the "Other" section (red arrow) of the launcher. Please double click on the "Terminal" tab.
![image](https://user-images.githubusercontent.com/41617337/175516964-c99b9a3d-3848-429a-9e76-9eae99355c4b.png)

12. This opens up a new "Terminal" (first red arrow) in your launcher section with a command line prompt (second red arrow)
![image](https://user-images.githubusercontent.com/41617337/175517233-fc44b2a9-e255-4925-966e-9a21b4d09cb1.png)

13. In the terminal, please type or copy and paste (using CTRL C + CTRL V) the following commands (followed by return/enter key). The commands are underlined with red lines in the image below. Please exchange {NAME} in the first command with your jupterlab URL name you created from step 6. You can also find this {NAME} in your JupyterLab web browser address, i.e. the word before the "/lab" (shown using the red box). PLease use the following command with the curly brackets {} for {NAME}.
  * **cd /data/notebooks/jupyterlab-{NAME}/**
  * **ls**
  * **git clone --recursive https://github.com/hydro-jules/school.git**
  * **ls**

If the all the commands are successful, the result of the last command should show a "school" directory below the command prompt (shown with a red circle).
![image](https://user-images.githubusercontent.com/41617337/175517437-28e5f87a-7ec3-4fc4-9f36-8f63ffbb1009.png)

14. The previous step imports the Hydro-JULES School GitHub repository to your DataLabs JupyterLab. You will also see a "school" directory apprear in the File Browser panel on the left of your screen (shown with a rectangle box). After the "school" directory shows up in your File Browser panel, please go ahead and close the "Terminal 1" by clicking on the cross button next to it (shown with a red circle). 
![image](https://user-images.githubusercontent.com/41617337/175517581-4d2c39ba-eeb3-4216-9d9f-65b84f1ee3da.png)

15. If you double-click on the "school" directory, in the File Browser panel, you will see the "python" directory and a "README.md" file which is the current file you are reading. 
![image](https://user-images.githubusercontent.com/41617337/172142823-38926187-eb87-4df6-b805-4eaf2dab7ecd.png)

16. Within the "python" directory, you find the following three directories:
  * **cf-python** – this directory contains notebooks that have exercises to read, analyse and visualize netCDF4 file using the [cf-python](https://ncas-cms.github.io/cf-python/) python module
  * **netcdf4** – this directory contains notebook that has exercises to read, analyse and visualize netCDF4 file using the [netCDF4](https://unidata.github.io/netcdf4-python/) python module
  * **unifhy** – this directory contains training material for learning how to use [unifhy](https://unifhy-org.github.io/unifhy/) python package.  
![image](https://user-images.githubusercontent.com/41617337/172142939-9b5fa103-1262-4bb4-bf5e-6883843bf061.png)

<a id="introduction_notebooks"></a>
### iii. Introduction to the repository notebooks

17. All of the training notebooks are available with the three directories mentioned in point 14. You can navigate the directories by double clicking on the directory name on the left hand side panel (red arrow) and you can go back with the back button of your browser (red square) or clicking on any of the directories in the path (red rectangle). 
![image](https://user-images.githubusercontent.com/41617337/172347607-b380d7e5-4305-44e0-b7fd-6febdf16f7e3.png)

18. Following are brief introductions of the training notebooks available:
  * **netCDF-examples.ipynb** – this notebook shows examples of reading in a netCDF file with the netCDF4 python module and discusses in detail the variables and metadata associated with a file having three dimensions (time, latitude and longitude). It shows different methods of analysing and plotting the netCDF data. A brief introduction to this notebook is given in this [video](https://youtu.be/PktTVnQcQy4) by Matt Fry. 
  * **cfpython_examples.ipynb** – this notebook shows examples of reading in a netCDF file with the cf-python python module and discusses in detail the variables and metadata associated with a file having three dimensions (time, latitude and longitude). It shows different methods of analysing and plotting the netCDF data. The notebook also has some exercises at the end (with hints) for user self-evaluation. A brief introduction to this notebook is given in this [video](https://youtu.be/dGif03kApJE) by Amulya Chevuturi.
  * **model-vs-observed_examples.ipynb** – this notebook shows examples of how to compare model output against observed data with the model output in netCDF format and the observed data in csv format. It discusses reading different formats of datasets into numpy array and plotting the datasets for comparison. The notebook also has some exercises at the end (with hints) for user self-evaluation. A brief introduction to this notebook is given in this [video](https://youtu.be/kqez7RtCKdk) by Amulya Chevuturi.
  * **exercise_answers.ipynb** - this notebook has answers to the exercise questions given in the previous two notebooks.
  * **unifhy directory** - this is the training module for unifhy model. The directory contain data, notebooks and outputs along with its own README.md.

19. Please note that to be able to run these notebooks successfully on DataLabs, you need to make sure that the environment (or kernel) is set to "*hj-38-nompi*" (shown using a red circle in the image below). The "*hj-38-nompi*" environment/kernel has all the required python packages for the training notebooks already installed. The environment/kernel is usually automatically set to "*hj-38-nompi*" when you open any notebook (generally for the netCDF4 and cf-python notebooks).  
![image](https://user-images.githubusercontent.com/41617337/179184129-ed5519b5-2bd1-48a5-ab40-9e029322ca97.png)
However, if your environment is set to any other (generally for the unifhy notebooks), shown as an example using a red circle in the image below, please click on it (red circle), which gives you a drop down menu (red square), which on selection has multiple environment/kernel options; please select the "*hj-38-nompi*" option (right-handed arrow) and click on "select button" (left-handed arrow).
![image](https://user-images.githubusercontent.com/41617337/179184288-df56922e-ae4a-43e7-ae19-3b3e5f86cb7f.png)

20. More details about running a Jupyter Notebook is provided through the images below: 
![image](https://user-images.githubusercontent.com/41617337/172341097-105faf92-0db0-44fe-ba97-b4c58149b0d5.png)
![image](https://user-images.githubusercontent.com/41617337/172341255-8c41f3d4-ff8d-415f-8006-74e432fe3f0d.png)
![image](https://user-images.githubusercontent.com/41617337/172341422-35863117-60b0-41ae-9829-8b8ef6a74453.png)
