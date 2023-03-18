## Project Descripiton
This app is designed to provide a user-friendly system for airport employees to track flights and assist customers with finding available flights and relevant details such as airline, meal plans, and space left on a flight.

The app includes a PostgreSQL database schema and an official C++ API libpqxx that allows airport employees to interact with the database. The API's user interface includes a list of commands that airport employees can use to retrieve information about flights, update flight information, and insert new information such as creating new flights, adding passengers, and adding cargo.

Overall, this app aims to improve the customer experience at the airport by enabling airport employees to more easily and efficiently track flights and assist customers with finding available flights and relevant details.

## Database Schema 

<img width="468" alt="image" src="https://user-images.githubusercontent.com/46549862/226073560-4f9ad6f8-52a4-4c39-84e2-654639995b05.png">

## Implemented Function

![image](https://user-images.githubusercontent.com/46549862/226073244-1c4e9ad0-737b-432b-9b8c-89481a380668.png)

## To build
Required packages: postgresql postgresql-contrib libpq-dev libpqxx-dev

# Ubuntu 
make new (to create database, will need further action aside from make)
make run

## Functionality
help - lists all commands
exit - exits the application

