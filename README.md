# PythonOceanLessons

Here are a collection of lessons for Oceanography students designed using python notebooks. These were developed with support from a Ocean Observing Institute (OOI) grant from the National Science Foundation (NSF) award to Rutgers University. The lessons were implement for several topics in the Salish Sea Oceanography course at Western Washington University's Huxely Environmental Sciences Department. They are designed for upper division undergraduates in Environment Sciences without any prior coding experiece; however, they may be revised easily for other students with more or lesson oceanographic and/or python scripting experience. Some lessons have prompts at the end for more complex, less guided analysis for students more comfortable in the python scripting environment.

The lessons are created in Jupyter Notebooks for their simplicity of use and to make transitioning between local python compilations and Google Colabs more or less seamless. I recommend working locally on your own machine if possible because Google Colabs file navigation is rather cumbersome, and Colabs can be slow when working with size-able datasets. However, when teaching students remotely, as I learned in 2020/2021, it can be much easier to use Google Colabs to avoid the inevitable issues installing Python on students personal machines. It still will not be easy, but once students are familiar with Colabs and how to navigate Google Drives file structure there are few further issues. The most ideal setting for this work is computer lab with Python packages pre-installed. If teaching remotely scheduling one-on-one time with students to work through technical issues can be really helpful using screen-share.

When working locally I recommend cloning this repository to your personal computer using Git-Hub tools. There are several ways to install Git-Hub and manage repositories, https://github.com/git-guides/install-git, however the easiest use-friendly approach is to use GitHub Desktop, https://desktop.github.com/. Once git is installed you can use a terminal to navigate to the folder you want the repository cloned in and then use "git clone repo-url" command. You may want to personalize this repo to your own purposes and in that case I recommend that you fork the repository which will make it easier to collaborate in the future.

## What's here

This repo contains several folders with a brief description of each below

0. [01_PythonAndColabIntroduction.ipynb](01_PythonAndColabIntroduction.ipynb): This python notebook is a brief introduction to basic python commands and scripting inside Jupyter or Colab notebooks. If students are new to scripting in python I recommend reviewing this notebook with them before using any of the lessons here. There are many other great resources for introducing python as well, e.g. [http://python.berkeley.edu/learn/](http://python.berkeley.edu/learn/), [https://software-carpentry.org/lessons/](https://software-carpentry.org/lessons/). 

1. Lesson_CoastalTransport: Student lesson/activity to illustrate the mechanics of upwelling and downwelling along the U.S. Washington Coastline using observations collected by the Washington OOI endurance array. See the instructor guide, [InstructorGuide](Lesson_CoastalTransport/02_InstructorGuide.md).

2. Lesson_EstuaryCirculation: Student lesson/activity to explore estuary exchange (residual) circulation with model-data from University of Washington's Live Ocean Salish Sea hydrodynamic model. See the instructor guide, [InstructorGuide](Lesson_EstuaryCirculation/04_InstructorGuide.md).

3. Lesson_Waves: Student lesson/activity to investigate the relationship between winds and waves aimed to develop student intuition for local and remote wave generation. These notebooks use observations collected by the National Data Buoy Center. See the instructor guide, [InstructorGuide](Lesson_Waves/03_InstructorGuide.md).

4. Lesson_ErrorMetrics: A brief student lesson/activity to investigate the meaning of error metrics commonly used in scientific literature. See the instructor guide, [InstructorGuide](Lesson_ErrorMetrics/02_InstructorGuide.md).

5. Datasets: Archived datasets used in some of the student lessons. OOI data was downloaded and post-processed. The matlab script for post-processing is including here, [PostProcess.m](Datasets/PostProcess.m)

6. DataTools_RiverDischarge: A set of python notebooks for students to use to see how to download, post-process, and plot river discharge data from U.S. Geological Survey river gauges. See the readme, [README.md](DataTools_RiverDischarge/README.md)

7. Images: Saved images needed for the python notebooks

8. InDevelopment: Scripts that may be developed into lessons in the future

If you have questions or want to get in touch, you can email me.

**Sean C. Crosby**

*sean.crosby (AT) wwu.edu*
