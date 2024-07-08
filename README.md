# Hydro-JULES Summer School 2024

Welcome to the Hydro-JULES Summer School multi-dimensional data workshops. This series of three workshops cover the basics of accessing and using multi-dimensional data. Summaries of the three workshops are provided below, along with links to the Python Jupyter Notebooks that we will be going through with you. 

<details>
    <summary>If you are not attending the Summer School, please click here to read this message.</summary>
These notebooks were provided as part of the Hydro-JULES summer school. This guidance was written for taking the participants through these notebooks using the JASMIN Notebook Service, where they would have access to the data. You are very welcome to go through these notebooks in your own time. These workshops are based on several excellent tutorials, which you will find links to.
    
[JULES](https://jules.jchmr.org/) is a community land surface model that is used both as a standalone model and as the land surface component in the Met Office Unified Model. JULES has been developed by a wide community of UK researchers, coordinated by UKMO and UKCEH. By allowing different land surface processes (surface energy balance, hydrological cycle, carbon cycle, dynamic vegetation, etc.) to interact with each other, JULES provides a framework to assess the impact of modifying a particular process on the ecosystem as a whole, e.g. the impact of climate change on hydrology, and to study potential feedbacks.
</details>


## The high-level objectives of these linked workshops are to:
- Provide overviews of key Python packages related to processing of multi-dimensional data.
- Introduce you to the Climate and Forecast (CF) Metadata Conventions.
- Introduce you to cloud object storage and related Python packages.
- Provide practice with practical applications of these standards and packages.

During workshops 4 and 5, we will be talking you through the associated notebooks. In the 6th workshop, you will have opportunity to work through a series of exercises in a notebook and ask further questions. We will be using Zoom to deliver these workshops, you will have been emailed joining links for each of the workshops. We look forward to meeting you.

If during the Summer School workshops you require assistance, please contact [Kit Macleod](mailto:kitmac@ceh.ac.uk) or [Amulya Chevuturi](mailto:amuche@ceh.ac.uk). 

To help get you set up for these three workshops, we provide:

i. [Overview and introduction to using notebooks on JASMIN](#overview-and-introduction-to-using-notebooks-on-jasmin)

ii. [Introduction to the workshop notebooks](#introduction-to-the-workshop-notebooks)


## Overview and introduction to using notebooks on JASMIN
[JASMIN](https://jasmin.ac.uk/) provides storage and compute facilities to enable data-intensive environmental science. It provides support for a wide range of data-intensive analysis workflows. It is designed and operated by the [Science and Technology Facilities Council (STFC)](https://www.ukri.org/councils/stfc/) on behalf of the [Natural Environment Research Council [(NERC)](https://www.ukri.org/councils/nerc/). 

We will be using [Jupyter notebooks](https://jupyter.org/) on the [JASMIN Notebook Service](https://notebooks.jasmin.ac.uk/) JASMIN provide [guidance](https://help.jasmin.ac.uk/docs/interactive-computing/jasmin-notebooks-service/) on what is a Jupyter Notebook, the [Jaspy Software Environments](https://help.jasmin.ac.uk/docs/software-on-jasmin/jaspy-envs/) they provide, how to use the Notebook Service, and links to further learning resources.

<details>
 <summary>To begin working with this repository during the Hydro-JULES Summer School training sessions, please click here.</summary>
    
 * Log in to [JASMIN Notebook Service](https://notebooks.jasmin.ac.uk/)    
 * In your JASMIN home directory click on the "Git" tab on your JupyterLab, and select "Clone a Repository" option.
 * In the subsequent window put in the GitHub repository address https://github.com/hydro-jules/school.git and tick the download repository option, before selecting the "clone" option.
 * It takes up to a few minutes for the repository to clone and once successful, you have a directory named "school" in your File Browser navigator on the left.
 * To run any of the notebooks within the repository, please use the kernel option *Python 3 + Jaspy Kernel*. 
</details>

## Introduction to the Hydro-JULES Summer School (HJSS) workshops notebooks

**HJSS Workshop 4:** Working with multi-dimensional data (netCDF). Introduces NetCDF and using Python packages to access, analyse, and visualise NetCDF files. [Link](https://github.com/hydro-jules/school/tree/main/HJSS_Workshop-4)

**HJSS Workshop 5:** Introduces object storage and the Zarr data format. [Link](https://github.com/hydro-jules/school/tree/main/HJSS_Workshop-5)

**HJSS Workshop 6:** Provides a series of practical applications and the opportunity to ask further questions. [Link](https://github.com/hydro-jules/school/tree/main/HJSS_Workshop-6)
