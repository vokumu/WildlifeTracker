# Douglas Fir Wildlife Tracker
---
## Project Description
This is a simple application that allows Rangers to track wildlife sightings in Douglas Fir forest. Two main categories of animals are tracked the safe and endangered species.
# ScreenShort
![img.png](img.png)
![img.png](img.png)
## Application Link
[link](https://wildlifetrackervicky.herokuapp.com//)

## Author Information
[Victoria Okumu](https://github.com/vokumu)
# Setup Instructions
To start using this project use the following:
1. Make sure you installed java application

2. install the following java requirements JUnit, intellij, SDK, JDK.

3. git clone

4. Navigate into the hero-squad directory - cd Wildlife-tracker-project /Navigate into the src/main/java/App.java and click run in intellij.

5. Go to your browser and type localhost:4567
# Database Setup
To set up the database:
* Run psql in the project terminal.
* Type the command: CREATE DATABASE wildlife_tracker;
* Navigate into the database by typing the command: \c wildlife_tracking;
* Create the required tables by running the following commands:
* CREATE TABLE rangers (id serial PRIMARY KEY, name VARCHAR, badge_number INT,phone_number int);
* CREATE TABLE animals(id serial PRIMARY KEY,name varchar,type VARCHAR);
* CREATE TABLE endangeredAnimals(id serial PRIMARY KEY,name varchar, health VARCHAR, age VARCHAR;
* CREATE TABLE locations (id serial PRIMARY KEY,name VARCHAR);
* CREATE TABLE sightings (id serial PRIMARY KEY,animal_id INT, rangerName varchar, location VARCHAR);
  Create a test database by typing the command: CREATE DATABASE wildlife_tracking_test WITH TEMPLATE wildlife_tracking;

## Technologies Used
* JDK
* Junit
* Java
* SDK
* IntellijIDEA
* Bootstrap
* Gradle
* maven
* Spark
* CSS
# Contact Information
- Email <victoriawasonga@gmail.com>

# Copyright  & License
## Copyright
        *AngularJs
        *Bootstrap


## License
[MIT](LICENSE)
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
