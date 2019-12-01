# GitHub Trending Repository Android Application 
> This project is an Android Mobile application in which we can view the trending github repositories.

## Table of contents
* [General info](#general-info)
* [Dependencies](#dependencies)
* [Setup](#setup)
* [Files and usages](#files-and-usages)
* [Features](#features)
* [Contact](#contact)

## General info
This application is a solution for the assignment given by Gojek tech. The main feature is to shows the trending repositories in Github. It is in MVP architecture. This Application supports minSDK version of 19 and above.It contains both Kotlin and Java file types. It contains basic UI tests using Espresso. In current implementation the language for trending repository is *kotlin* (  can be changed in code level)

## Dependencies
* RXJava2 - version 2.1.1
* Retrofit2 - version 2.6.1
* Dagger2- version 2.24
* Glide - version 4.9.0 
* Material design - version 1.0.0
* Okhttp - version 4.1.0
* JUnit - version 1.1.1
* Expresso - version 3.2.0

## Setup  
This project was developed inAndroid Studio 3.5.2 (Windows 10 OS). Clone the project and open in Android studio (version 3.5.2 preferred, if not change the version in build.gradle file in sync with the version you are using). Run the app in Android studio given a device is connected or in virtual device

## Files and usages
* `androidgitrepositorylib` - This is the library created to make service calls exclusively to fetch trending github repositories. It has the response Models , Contract that is used , service and its facade class.
* `daggerInjection` - This module takes care of Component and Module required for dependency injection
* `utils` - This module contains the utility files that is used in the appication.
* `TrendingRepositoryHomePageActivity`TrendingRepositoryHomePageActivity - This is the Launcher activity (Homepage) of our app.
* `TrendingRepositoryPresenterImpl`TrendingRepositoryPresenterImpl - This is the presenter class used for all the business logics and modification
* `TrendingRepositoryView`TrendingRepositoryView - This interface helps us in updating the UI.
* `TrendingHomePageActivityEspressoTest`TrendingHomePageActivityEspressoTest - This contains basicc UI test using espresso

## Features
List of features ready
* View trending repositories in Github
* Sort by Name
* Sort by Stars
* Swipe to refresh
* Expand on click to view details

## Contact
Created by [akshayshankarek@gmail.com - feel free to contact me!
