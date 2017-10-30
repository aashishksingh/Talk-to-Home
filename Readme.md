

Introduction

Home Automation Technologies are one of the big gamers in the tech markets these days. With advent of efficient Artificial Intelligence, Machine Learning coupled with Internet-of-Things, it has made some big tech giants to invest hefty amounts in this field.

While with our project we do not use any AI/ML techniques [ but quite easily adaptable to it ], for the sake of brevity, we have projected the IoT side of such technologies.

Talk-to-Home provides an interface to the smart devices (end-points) in the home. It is a lightweight, user-friendly and super-responsive way to to talk to your home, bringing it to life. After all, what is better than a home who knows you the best?

Design and Concept

Frontend

The webpage provides the Smart Home interface as a web service. It currently involves a Dashboard, gauges, surveillance feed. But it is quite easily updatable to customized interfaced, handling the interface for different home devices, interfaces, areas, etc. Hence Account feature is added to the dashboard. 

Single-Face-All-In-Place allows the user to access all the smart devices without navigating a lot. Such a hassle-free interface enables seamless human-to-machine communication. Simple technologies like HTML,CSS,JavaScript and jQuery are used.

Backend

All the dynamic features are basically handled by JavaScript and jQuery, but the real power comes from the sensor service APIs. Each sensor service is hosted on a seperate server, whose links are being provided to fetch the data after every 4 seconds dynamically. jQuery is used to fire such queries to the server and changed the specific tag contents in on webpage. The sensor data is simulated on the sensor service APIs using the occupancy dataset available on https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+
Usage

This document is present as a readme file and the source code for the latest version v1.0.9 are available on GitHub https://github.com/aashishksingh/Talk-to-Home.


Contributors:

Aashish K Singh @ sk.aashish95@gmail.com
Suraj @ hrishabhsuraj52@gmail.com
