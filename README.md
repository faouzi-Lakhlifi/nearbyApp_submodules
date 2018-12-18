# Nearby shops App

## Context

This is an app is the result of my attemt at United Remote's  (Formerly Hidden Founders) web coding challenge.
Features

##     Functional spec

The coding challenge is about implementing an app that lists shops nearby.

-     As a User, I can sign up using my email & password
-     As a User, I can sign in using my email & password
-     As a User, I can display the list of shops sorted by distance
-     As a User, I can like a shop, so it can be added to my preferred shops
         (liked shops shouldn’t be displayed on the main page)
-      As a User, I can display the list of preferred shops
-      As a User, I can remove a shop from my preferred shops list

## Getting Started
Technologies :

-         Backend : Java - Spring Boot
-         Frontend : JavaScript - React 16
-         Database : MySQL

### Run the App
#### 1 - Application Data

The challenge provided a MongoDB dump file with 342 shops, that I extracted to jason format and then inserted into MySQL, the sql format of the data is provided in the api sub-module under the name db3.sql.
Create a mysql db called "db-spring-demo" with a "utf8" collation to support key indexes big types (you can change the name in application.properties file in the the api code)

#### 2 - Spring Boot API

You can deploy Spring Boot API with Maven Or with an IDE.

I used IntelliJ IDEA, but other IDEs like STS or Eclipse are fine as well. 

1. Open Projetc (API-SpringBoot) in your IDE
2. Import maven dependencies/rebuild with maven 
3. Run (this will create the tables in the database)
4. Import shops/run query  from "**db3.sql**" form api folder



#### 3 - React Client
In "**Client-SPA-React**" folder start a command prompt
1. npm install (to install dependencies)
2. npm start
