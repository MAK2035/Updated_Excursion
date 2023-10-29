# Excursion App

This project involved modeling the requirements for an excursion booking portal using UML diagrams.
![App_logo](https://github.com/MAK2035/Updated_Excursion/assets/148695360/aaed0e66-ca56-4dcc-90cb-d446d62440ab)


## Overview
The goal was to develop an online travel booking portal for customers to search, compare and book sightseeing excursions and activities. Key capabilities included inventory management, bookings, payments, notifications, support, and analytics.

## UML Diagrams
The following UML diagrams were created to model the system:

## Use Case Diagram
The use case diagram models the key actors and top level functionality of the system.
<img width="627" alt="UseCaseDiagram" src="https://github.com/MAK2035/Updated_Excursion/assets/148695360/55368984-eb35-478f-ba98-087867d22f50">


## Sequence Diagrams
Sequence diagrams capture workflows for major use cases:

* Search excursions
* Compare prices
* Complete booking
* Get booking confirmations

<img width="422" alt="Search_excursion_sequence" src="https://github.com/MAK2035/Updated_Excursion/assets/148695360/8eef4316-df3b-461b-bb10-181df9d12690">

<img width="458" alt="Compare_prices_sequence" src="https://github.com/MAK2035/Updated_Excursion/assets/148695360/23e56139-b048-43a0-8275-54eb2237b1cc">

<img width="431" alt="User_booking_sequence" src="https://github.com/MAK2035/Updated_Excursion/assets/148695360/d4b59400-99af-4f9f-b2f2-b63a1c037941">

<img width="437" alt="Get_confirmation_sequence" src="https://github.com/MAK2035/Updated_Excursion/assets/148695360/e43f0b43-948e-4988-ba78-b3237e2cdd2c">


## Class Diagram
The class diagram shows the main entities and their relationships.

<img width="659" alt="ConceptualClassDiagram" src="https://github.com/MAK2035/Updated_Excursion/assets/148695360/e4b4923f-3862-4ed0-a798-2f1dbbf759d1">


## Limitations
* The UML modeling tool used was functional but had some performance and usability issues that slowed down development. More refined validation and version control capabilities would help with reliability and change tracking.
* The search feature needs to support more flexible date filters and ranges to accommodate different trip lengths.
* Price comparisons are currently limited to 3 excursions. Allowing more would improve decision making.
* Notifications rely on external email/SMS providers. Delivery delays outside of the system's control can impact the user experience.
