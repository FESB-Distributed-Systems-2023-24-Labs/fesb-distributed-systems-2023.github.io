# Homework Assignments

## Table of Contents

- [Homework Assignments](#homework-assignments)
  - [Table of Contents](#table-of-contents)
- [Homeworks](#homeworks)
  - [Homework 2](#homework-2)
    - [General (Important)](#general-important)
    - [\[HW2\] Matej Baljak\*](#hw2-matej-baljak)
    - [\[HW2\] Ante Bilić](#hw2-ante-bilić)
    - [\[HW2\] Karlo Čarija](#hw2-karlo-čarija)
    - [\[HW2\] Martin Čelar](#hw2-martin-čelar)
    - [\[HW2\] Bruno Grbavac](#hw2-bruno-grbavac)
    - [\[HW2\] Robert Jukić-Bračulj\*](#hw2-robert-jukić-bračulj)
    - [\[HW2\] Željko Kalajžić](#hw2-željko-kalajžić)
    - [\[HW2\] Damira Mamuzić](#hw2-damira-mamuzić)
    - [\[HW2\] Kruno Manenica](#hw2-kruno-manenica)
    - [\[HW2\] Ante Marušić](#hw2-ante-marušić)
    - [\[HW2\] Luka Nikolac](#hw2-luka-nikolac)
    - [\[HW2\] Sara Pavlović](#hw2-sara-pavlović)
    - [\[HW2\] Roko Ražov](#hw2-roko-ražov)
    - [\[HW2\] Josip Sanader](#hw2-josip-sanader)
    - [\[HW2\] Emilija Sarić](#hw2-emilija-sarić)
    - [\[HW2\] Tihana Slavić](#hw2-tihana-slavić)
    - [\[HW2\] Ivan Stojković](#hw2-ivan-stojković)
    - [\[HW2\] Luka Svaguša](#hw2-luka-svaguša)
    - [\[HW2\] Edita Škec](#hw2-edita-škec)
    - [\[HW2\] Marin Uzinić](#hw2-marin-uzinić)
    - [\[HW2\] Marija Vladimir](#hw2-marija-vladimir)
    - [\[HW2\] Filip Volarević](#hw2-filip-volarević)
    - [\[HW2\] Jere Zambarlin\*](#hw2-jere-zambarlin)

# Homeworks

## Homework 2

### General (Important)

> **IMPORTANT:** This paragraph applies to all students and homeworks

- Write a comment at the top of your controller file where you state:
  - Your name
  - Your task
  - A few senteces explaining what does your program do

Use the following template:

```csharp
/*
 **********************************
 * Author: <Your Name>
 * Project Task: <Your Task (See the list below)>
 **********************************
 * Description:
 *  
 *  <Write a few senteces explaining what does your program do>
 *
 **********************************
 */
```


> **IMPORTANT:** For an example see [Lab 5 - Controller Example](../labs/05.Lab%205%20-%20HTTP%20Programming/Controller%20Example.md) and for help with creating a project and/or a controller see [Lab 5 - Creating a Web API](../labs/05.Lab%205%20-%20HTTP%20Programming/Creating%20a%20Web%20API.md).

> **NOTE:** *Endpoints* are "functions" that are called when a request with specific route is received. In the example above ([Lab 5 - Controller Example](../labs/05.Lab%205%20-%20HTTP%20Programming/Controller%20Example.md)), the *endpoints* are functions `GetStudents()`, `GetStudentByIndexFromRoute()`, `GetStudentByIndexFromQuery`, `GetStudentByIndexFromBody`. Each *endpoint* has its own unique route e.g. `/students`, `/student/{id}`, ...




### [HW2] Matej Baljak\*
- **Project Task:** University
- **Requirements:**
  - Create a controller (`UniversityController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Student name, University name) from *Route*
      - Returns a response with status 200 OK and a text `"Student {Student name} enrolled at {University name} University :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Student name, University name) from *Query*
      - Returns a response with status 200 OK and a text `"Student {Student name} enrolled at {University name} University :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (University name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {University name} University!"`


### [HW2] Ante Bilić
- **Project Task:** Hospital
- **Requirements:**
  - Create a controller (`HospitalController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Patient name, Hospital name) from *Route*
      - Returns a response with status 200 OK and a text `"Patient {Patient name} admitted to {Hospital name} Hospital :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Patient name, Hospital name) from *Query*
      - Returns a response with status 200 OK and a text `"Patient {Patient name} admitted to {Hospital name} Hospital :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Hospital name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Hospital name} Hospital!"`


### [HW2] Karlo Čarija
- **Project Task:** Grocery Shop
- **Requirements:**
  - Create a controller (`GroceryShopController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Grocery name, Grocery Shop name) from *Route*
      - Returns a response with status 200 OK and a text `"Grocery {Grocery name} bought at {Grocery Shop name} Grocery Shop :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Grocery name, Grocery Shop name) from *Query*
      - Returns a response with status 200 OK and a text `"Grocery {Grocery name} bought at {Grocery Shop name} Grocery Shop :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Grocery Shop name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Grocery Shop name} Grocery Shop!"`


### [HW2] Martin Čelar
- **Project Task:** Shoe Shop
- **Requirements:**
  - Create a controller (`ShoeShopController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Shoe Model name, Shoe Shop name) from *Route*
      - Returns a response with status 200 OK and a text `"Shoe Model {Shoe Model name} bought at {Shoe Shop name} Shoe Shop :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Shoe Model name, Shoe Shop name) from *Query*
      - Returns a response with status 200 OK and a text `"Shoe Model {Shoe Model name} bought at {Shoe Shop name} Shoe Shop :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Shoe Shop name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Shoe Shop name} Shoe Shop!"`


### [HW2] Bruno Grbavac
- **Project Task:** Library
- **Requirements:**
  - Create a controller (`LibraryController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Book name, Library name) from *Route*
      - Returns a response with status 200 OK and a text `"Book {Book name} borrowed from {Library name} Library :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Book name, Library name) from *Query*
      - Returns a response with status 200 OK and a text `"Book {Book name} borrowed from {Library name} Library :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Library name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Library name} Library!"`


### [HW2] Robert Jukić-Bračulj\*
- **Project Task:** Pet Shop
- **Requirements:**
  - Create a controller (`PetShopController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Pet name, Pet Shop name) from *Route*
      - Returns a response with status 200 OK and a text `"Pet {Pet name} bought from {Pet Shop name} Pet Shop :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Pet name, Pet Shop name) from *Query*
      - Returns a response with status 200 OK and a text `"Pet {Pet name} bought from {Pet Shop name} Pet Shop :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Pet Shop name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Pet Shop name} Pet Shop!"`


### [HW2] Željko Kalajžić
- **Project Task:** Factory
- **Requirements:**
  - Create a controller (`FactoryController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Car Model name, Factory name) from *Route*
      - Returns a response with status 200 OK and a text `"Car Model {Car Model name} manufactured at {Factory name} Factory :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Car Model name, Factory name) from *Query*
      - Returns a response with status 200 OK and a text `"Car Model {Car Model name} manufactured at {Factory name} Factory :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Factory name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Factory name} Factory!"`


### [HW2] Damira Mamuzić
- **Project Task:** City
- **Requirements:**
  - Create a controller (`CityController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Resident name, City name) from *Route*
      - Returns a response with status 200 OK and a text `"Resident {Resident name} lives in {City name} City :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Resident name, City name) from *Query*
      - Returns a response with status 200 OK and a text `"Resident {Resident name} lives in {City name} City :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (City name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {City name} City!"`


### [HW2] Kruno Manenica
- **Project Task:** Store
- **Requirements:**
  - Create a controller (`StoreController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Laptop Model name, Store name) from *Route*
      - Returns a response with status 200 OK and a text `"Laptop Model {Laptop Model name} serviced at {Store name} Store :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Laptop Model name, Store name) from *Query*
      - Returns a response with status 200 OK and a text `"Laptop Model {Laptop Model name} serviced at {Store name} Store :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Store name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Store name} Store!"`


### [HW2] Ante Marušić
- **Project Task:** Weather Station
- **Requirements:**
  - Create a controller (`WeatherStationController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Temperature name, Weather Station name) from *Route*
      - Returns a response with status 200 OK and a text `"Temperature {Temperature value} reading at {Weather Station name} Weather Station :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Temperature name, Weather Station name) from *Query*
      - Returns a response with status 200 OK and a text `"Temperature {Temperature value} reading at {Weather Station name} Weather Station :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Weather Station name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Weather Station name} Weather Station!"`


### [HW2] Luka Nikolac
- **Project Task:** Airport
- **Requirements:**
  - Create a controller (`AirportController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Plane name, Airport name) from *Route*
      - Returns a response with status 200 OK and a text `"Plane {Plane name} lands at {Airport name} Airport :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Plane name, Airport name) from *Query*
      - Returns a response with status 200 OK and a text `"Plane {Plane name} lands at {Airport name} Airport :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Airport name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Airport name} Airport!"`


### [HW2] Sara Pavlović
- **Project Task:** Shelter
- **Requirements:**
  - Create a controller (`ShelterController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Animal name, Shelter name) from *Route*
      - Returns a response with status 200 OK and a text `"Animal {Animal name} admitted to {Shelter name} Shelter :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Animal name, Shelter name) from *Query*
      - Returns a response with status 200 OK and a text `"Animal {Animal name} admitted to {Shelter name} Shelter :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Shelter name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Shelter name} Shelter!"`


### [HW2] Roko Ražov
- **Project Task:** Port
- **Requirements:**
  - Create a controller (`PortController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Ship name, Port name) from *Route*
      - Returns a response with status 200 OK and a text `"Ship {Ship name} docked at {Port name} Port :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Ship name, Port name) from *Query*
      - Returns a response with status 200 OK and a text `"Ship {Ship name} docked at {Port name} Port :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Port name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Port name} Port!"`


### [HW2] Josip Sanader
- **Project Task:** Company
- **Requirements:**
  - Create a controller (`CompanyController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Employee name, Company name) from *Route*
      - Returns a response with status 200 OK and a text `"Employee {Employee name} employed at {Company name} Company :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Employee name, Company name) from *Query*
      - Returns a response with status 200 OK and a text `"Employee {Employee name} employed at {Company name} Company :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Company name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Company name} Company!"`


### [HW2] Emilija Sarić
- **Project Task:** Bus Destinaton
- **Requirements:**
  - Create a controller (`BusDestinatonController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Driver name, Bus Destinaton name) from *Route*
      - Returns a response with status 200 OK and a text `"Driver {Driver name} drives to {Bus Destinaton name} Bus Destinaton :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Driver name, Bus Destinaton name) from *Query*
      - Returns a response with status 200 OK and a text `"Driver {Driver name} drives to {Bus Destinaton name} Bus Destinaton :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Bus Destinaton name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Bus Destinaton name} Bus Destinaton!"`


### [HW2] Tihana Slavić
- **Project Task:** Taxi Company
- **Requirements:**
  - Create a controller (`TaxiCompanyController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Client name, Taxi Company name) from *Route*
      - Returns a response with status 200 OK and a text `"Client {Client name} booked a ride from {Taxi Company name} Taxi Company :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Client name, Taxi Company name) from *Query*
      - Returns a response with status 200 OK and a text `"Client {Client name} booked a ride from {Taxi Company name} Taxi Company :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Taxi Company name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Taxi Company name} Taxi Company!"`


### [HW2] Ivan Stojković
- **Project Task:** Hotel
- **Requirements:**
  - Create a controller (`HotelController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Person name, Hotel name) from *Route*
      - Returns a response with status 200 OK and a text `"Person {Person name} booked stay at {Hotel name} Hotel :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Person name, Hotel name) from *Query*
      - Returns a response with status 200 OK and a text `"Person {Person name} booked stay at {Hotel name} Hotel :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Hotel name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Hotel name} Hotel!"`


### [HW2] Luka Svaguša
- **Project Task:** Trophy
- **Requirements:**
  - Create a controller (`TrophyController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Sport Club name, Trophy name) from *Route*
      - Returns a response with status 200 OK and a text `"Sport Club {Sport Club name} won this year's {Trophy name} Trophy :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Sport Club name, Trophy name) from *Query*
      - Returns a response with status 200 OK and a text `"Sport Club {Sport Club name} won this year's {Trophy name} Trophy :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Trophy name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Trophy name} Trophy!"`


### [HW2] Edita Škec
- **Project Task:** Sport Club
- **Requirements:**
  - Create a controller (`SportClubController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Player name, Sport Club name) from *Route*
      - Returns a response with status 200 OK and a text `"Player {Player name} transferred to {Sport Club name} Sport Club :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Player name, Sport Club name) from *Query*
      - Returns a response with status 200 OK and a text `"Player {Player name} transferred to {Sport Club name} Sport Club :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Sport Club name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Sport Club name} Sport Club!"`


### [HW2] Marin Uzinić
- **Project Task:** Cinema
- **Requirements:**
  - Create a controller (`CinemaController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Movie name, Cinema name) from *Route*
      - Returns a response with status 200 OK and a text `"Movie {Movie name} played in {Cinema name} Cinema :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Movie name, Cinema name) from *Query*
      - Returns a response with status 200 OK and a text `"Movie {Movie name} played in {Cinema name} Cinema :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Cinema name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Cinema name} Cinema!"`


### [HW2] Marija Vladimir
- **Project Task:** Country
- **Requirements:**
  - Create a controller (`CountryController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Animal name, Country name) from *Route*
      - Returns a response with status 200 OK and a text `"Animal {Animal name} lives in {Country name} Country :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Animal name, Country name) from *Query*
      - Returns a response with status 200 OK and a text `"Animal {Animal name} lives in {Country name} Country :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Country name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Country name} Country!"`


### [HW2] Filip Volarević
- **Project Task:** Newspaper
- **Requirements:**
  - Create a controller (`NewspaperController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Reporter name, Newspaper name) from *Route*
      - Returns a response with status 200 OK and a text `"Reporter {Reporter name} works at {Newspaper name} Newspaper :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Reporter name, Newspaper name) from *Query*
      - Returns a response with status 200 OK and a text `"Reporter {Reporter name} works at {Newspaper name} Newspaper :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Newspaper name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Newspaper name} Newspaper!"`


### [HW2] Jere Zambarlin\*
- **Project Task:** Country
- **Requirements:**
  - Create a controller (`CountryController.cs`) with 3 endpoints (functions)
    - Endpoint 1:
      - Takes *two* parameters (Currency name, Country name) from *Route*
      - Returns a response with status 200 OK and a text `"Currency {Currency name} is used in {Country name} Country :: from route"`
    - Endpoint 2:
      - Takes *two* parameters (Currency name, Country name) from *Query*
      - Returns a response with status 200 OK and a text `"Currency {Currency name} is used in {Country name} Country :: from query"`
    - Endpoint 3:
      - Takes *one* parameter (Country name) from *Body*
      - Returns a response with status 200 OK and a text `"Hello from {Country name} Country!"`

