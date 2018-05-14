


# World wide telescope overview:

WWT is a visualization tool for astronomical data. It also helps to compare different astronomical data resources by plotting data on the images or celestial projections.
 
WWT is a collection of tools which works with the astronomical data resources and the  data services.

There are three main categories for the tools is:

•	Image generation and data massaging tools
•	Client tools
•	APIs


As WWT is visualization tool the main component of the tool is to generate images from various data sources in standard projection (TOAST1 projection) used by WWT clients. 

## Image generation and data processing tool:
To create WWT compatible images with certain projections. Tile SDK project is used. This is a stand alone application to create custom data pipeline to generate HTMs2 compatible with WWT. 

## Client tools:
There are two clients available for WWT , windows client and web client.
Windows Client: It is a developed in C# .net technology and contains most of the functionalities which are offered by WWT.
Various data set rendering is available through windows client and more can be explored using different search services embedded within the client. 
It supports tabular data, images and catalog data from various astronomical data sources.
VO support is available through various vo services and vo tables accessible through the client.
User controls different data layers required his/her own viewing.

## Web Client:
It is web based tool, It has subset of features available in windows client.
Web client code has various components associated with it. Core functionality is developed by converting native C# code in javascript using ScriptSharp.
WegGl is used along with HTML5 for canvas rendering on webpage for 2D and 3D effects.

##Application Programming Interfaces:
There are several apis running in the backend of WWT. Primarily, 
Layer Control API:  
Most of the functionalities of WWT can be controlled by  Layer control API.  There are different programming interfaces developed to render data in a various format. User can import the data and render on  WWT using these APIs.

HTML5 WebGL:
This is a javascript API available for any web applications to embed WWT in their own project. It helps to create custom viewing interfaces, load images or data using VO services or to create different tours for educational purpose.

Web Services API:
There are several web services used by WWT to gather data, massage and create WWT compatible data format.


#  Developers Corner
As a developer How to start?

## System Requirements:
 (It varies from version of the code details in git repository with each tool)
Windows 7+ system
.Net Framework 4.0 +
Visual Studio 2010 +
IIS

Working with Windows client:

Clone code form git repository

 Git clone 
https://github.com/WorldWideTelescope/wwt-windows-client

Instructions to set up development environment with latest code:


Things to Note:
??



## Working with web client:

Clone code from following repo

Git clone
https://github.com/WorldWideTelescope/wwt-web-client

It consists of three sub projects, HTML5SDK, Server, Webclient

To Run WebClient successfully make sure to update nuget packages and clean up the “wurfl” files it generates.  If successfully compiled the web client will run on browser with locahost.



Working with Data processing pipeline: 
https://github.com/WorldWideTelescope/wwt-tile-sdk 

How to set up and run this code??
 
 

## Other code:
https://github.com/WorldWideTelescope/worldwide-telescope-pyramid-sdk

What is the relationship between  pyramid sdk and tile-sdk??


