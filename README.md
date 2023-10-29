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

## User Requirements 
 -As a user, I want to search for available excursions to easily find and explore excursions based on my preferences, dates, and destination.
- As a user, I want to compare prices across travel products so I can get the best deals.
- As a user, I want to complete bookings and make payments so I can confirm my travel plans.
- As a travel agent, I want to book travel on behalf of clients over the phone or email.
- As an affiliate partner, I want to promote travel offers on my platform and earn commissions. 
- As a business manager, I want to monitor bookings and revenue for the portal.
- As a customer support agent, I want to assist users with booking inquiries and issues

## Software Requirements
1. The system shall allow search based on destination, dates, travelers etc. (Functional)
2. The system shall perform price comparison across multiple suppliers. (Functional)  
3. The system shall integrate payment gateways for accepting user payments. (Integration)*
4. The system shall send real-time booking info to suppliers via APIs. (Integration)
5. The system shall automatically cancel unpaid bookings after timeout. (Functional)
6. The system shall maintain audit logs of all transactions. (Non-functional)  
7. The system shall have fraud analysis capabilities during bookings. (Security)
8. The system shall encrypt sensitive user data during storage and transmission. (Security)*
9. The system shall have provisions to scale-up resources during peak seasons. (Scalability)*
10. The system shall integrate with external systems via APIs and real-time feeds. (Integration)*
11. The system shall maintain 99.9% uptime for uninterrupted bookings. (Availability)*
12. The system shall provide role-based access for porta users. (Security)* 
13. The system shall have capabilities to recover from failures with minimal data loss. (Reliability)*
14. The system shall allow configuring travel promotions and offers. (Functional)  
15. The system shall track and report on performance of affiliate channels. (Reporting)

    * Non-Functional Requirement



## Limitations
* The UML modeling tool used was functional but had some performance and usability issues that slowed down development. More refined validation and version control capabilities would help with reliability and change tracking.
* The search feature needs to support more flexible date filters and ranges to accommodate different trip lengths.
* Price comparisons are currently limited to 3 excursions. Allowing more would improve decision making.
* Notifications rely on external email/SMS providers. Delivery delays outside of the system's control can impact the user experience.
