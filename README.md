# Gradio-project
**Introduction**

This article is to briefly walkthrough how to build and deploy a churn prediction app with Gradio, a platform that allows you to easily create and share interactive web apps with machine learning models.

Process Description

first you have to set up your environment.

Then importation of needed libraries.

Getting train and test set by splitting data and encoding them

Creating pipelines

Developing interface

Simple Interface design and app launching code



Installation
To setup and run this project you need to have Python3 installed on your system. Then you can clone this repo. At the repo's root, use the code from below which applies:

+ Windows:

   python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  
  
+ Linux & MacOs:

  python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt
  
NB: For MacOs users, please install Xcode if you have an issue.

You can then run the app (still at the repository root)
