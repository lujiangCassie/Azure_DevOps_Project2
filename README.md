# Overview

This project will build a dedicated process from scratch to create a scaffolding that assist to perform a continuouse Integration and continuous delivery pipeline through Github and Azure. The goal is to achieve an automation process on housing price rediction on Azure.

## Project Plan
It is import to design a detailed project plan before coding and taking actions.

* A link to a Trello board for the project
  https://trello.com/b/LcKVGRBW/lus-trello-board
  
* A link to a spreadsheet that includes the original and final project plan>
  https://docs.google.com/spreadsheets/d/17jC6264wwhcETUfqlSMgWxw9DYxIN03CNhU1PkU_r2w/edit#gid=1348135932

  

## Instructions

Azure cloud CLI(connect cloud to code and github)  --->  GitHub (Git Sctions for CI)  --->  Azure Pipeline (CD)  --->  Azure Web App

Deploy the app in Azure Cloud Shell

In Azure Cloud Shell, clone the repo:

Set up SSH Key in github account and then git clone git@github.com:lujiangCassie/Azure_DevOps_Project2.git.

![Github_Connect_Cloud](https://github.com/lujiangCassie/Azure_DevOps_Project2/assets/127454188/829e166b-1932-4a5b-a4b9-406cf412653a)

Create virtual environment and activate it.
Install dependencies in the virtual environment and run tests: make all

![CI_Makeall](https://github.com/lujiangCassie/Azure_DevOps_Project2/assets/127454188/76f89841-1efc-4e88-b779-da96bff3ff08)

Set up Git Actions and modify pythonapp.yml file. Then verify lint and test

![Git_Actions](https://github.com/lujiangCassie/Azure_DevOps_Project2/assets/127454188/c673897d-57fd-4366-9d71-e35068f79dda)

Deploy Web App on Azure and check it in browser. Then set up Azure Pipeline

![Azure_webapp_browser](https://github.com/lujiangCassie/Azure_DevOps_Project2/assets/127454188/1e1ec7b3-2c83-4261-ab67-53d9b0ba5d30)

![Azure_Pipeline](https://github.com/lujiangCassie/Azure_DevOps_Project2/assets/127454188/1a154881-34cb-4028-b1d5-ad71a2c98485)


Check predictions result

![Make_predict_Azure_app](https://github.com/lujiangCassie/Azure_DevOps_Project2/assets/127454188/06b3060d-766b-44d4-9fa0-d3bc228ea3db)

Check Web App logs:

![webapp-logs](https://github.com/lujiangCassie/Azure_DevOps_Project2/assets/127454188/a6127794-8e7c-4c7d-99e1-27542724bd2a)

Carry out load test through locust

command: pip install locust

![locust_2](https://github.com/lujiangCassie/Azure_DevOps_Project2/assets/127454188/68aa9154-bddd-4518-9f6f-5dbbea080616)

![locust_1](https://github.com/lujiangCassie/Azure_DevOps_Project2/assets/127454188/2010cc9c-de74-41ff-8a75-318707c719c5)














