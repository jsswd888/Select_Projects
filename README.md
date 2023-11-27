# Selected Projects

This repository displays some of the selected project's demos, and also included some description writeups regarding to a couple Computer Science courses that I've taken so far. The aim of creating this repository is to help employers better understand:

1. Some projects that I have worked on, in detail, which may or may not on my resume.
2. To better understand the knowledges that I've learned in the University.

Some of the course descriptions may also helpful for fellow UW-Madison students who is intending to take certain courses to understand what will be taught on each of these courses, in more detail. 

## EasyVizAR (Ongoing)
This project aims to created indoor navigation application operated on an Augmented Reality Platform for first responders. My responsibility in this project is signboard creation, which includes C# coding, Unity interactions, etc. 

Due to the nature of this project there is no demo available. Briefly speaking I have created some navigation signboards that displays **Destiination, Direction, Distance**. Distance and Direction are dynamically calculated based on the designated NavMesh Algorithm, and hence users could get clear instruction of where to go. The signboard is created based on **Unity Prefab** and we make sure whenever user paste the signboard they will be able to see the latest direction & distance information.

Next step will be migrate prototype we have on Unity to implement application on **HoloLens**; after that we are expected to conduct some usability experiement and evaluation to find the optimal, user-friendly design.

## Directed Reading Program (Ongoing)
This is one of the latest project that I am independently working on starting Sept. 2023. The program is managed by UW-Madison Dept. of Mathematics, and my mentor is Hyun Jong Kim. The plan is to build up a machine learning model that could possibly give predictions of stock price tendency. Namely, I focused on Nasdaq Index. All the training / validation data comes from Nasdaq's historical price, and the model is trained using LSTM.

The link to this project's repository can be found [here](https://github.com/jsswd888/Stock_Prediction)
The presentation slides (TO BE FINISHED BEFORE DEC. 6) will be available here.

## Senior Software Design Capstone (CS 639)
[Indoor Navigation & Management](https://youtu.be/CVSxbtZ2RQg)
- A dashboard interface of an indoor navigation system; display daily building population flow graphs, population density in the building, etc. Used **Mapbox** for mappings and **react** for the whole dashboard design

## User Interface Design (CS 571)
[BadgerChat](https://www.youtube.com/watch?v=_IhJLxTszGU)
- This is a web application that involved some chatroom features, based on **react**. Detailed description can be found [here](https://github.com/CS571-S23/hw6)

[BadgerChat - Mobile](https://youtu.be/7IMRCvCS_uM)
- The mobile version of the web chatroom application. Provide same functionalities as the one above, except that this one is based on **react-native**. Detailed description can be found [here](https://github.com/CS571-S23/hw10)

## Database Management System Design (CS 564)
[DBMS of Major Global Financial Assets](./project_demos/001_demo_DBMS_of_Major_Global_Financial_Assets.pdf)
- A Database Management system that stores a varities of financial assets' historical price data, enable individual users to register, query price data as wanted, asset comparison feature, etc. 

## Abstract Data Structure (CS 400)
[Student Information Data Management System](https://www.bilibili.com/video/BV1cQ4y1C7gc/)
- This project uses **HashTableMap** data structure for implementation. The System have 4 commands:
  - delStu: delete a student from the system
  - addStu: add a new student into the system
  - updateStu: update certain student's profile in the system
  - print: print all students' key information currently stored in the system

## Data Modeling (STAT 240)
[Resident Election Preferences at City of Madison](./project_demos/002_stat_project_report_sample.pdf)
- A Sample research project that utilizes `tidyverse`, `dplyr`, `leaflet`, etc. libraries to investigate City of Madison residents' voting "habits", such as time slots Madison residents prefer to vote,  changes in the number of people who vote each year, and any other statistical characteristics show in the dataset. 
