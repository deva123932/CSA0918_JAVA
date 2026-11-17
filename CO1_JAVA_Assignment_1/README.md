
# Campus Smart-Parking System
### Programming in Java – CO1 Assignment 1

## 1. Project Overview

The Campus Smart-Parking System is an object-oriented Java application designed to manage parking facilities within a university campus.

The system manages multiple parking floors, parking slots, vehicle categories, parking tickets, user eligibility and parking fee calculations.

It supports two-wheelers, cars and electric vehicles. Students and staff with valid monthly passes are eligible for free parking, while visitors are charged the applicable parking fees.

The application is designed to be modular, reusable and extensible to support additional vehicle categories and changing parking requirements.

## 2. Problem Statement

University campuses require an efficient parking management system to handle multiple vehicles and limited parking spaces.

Manual parking management can lead to inefficient slot allocation, difficulty tracking vehicle entry and exit, ticket management problems and incorrect fee calculations.

The proposed system addresses these problems by providing an object-oriented solution that automates parking slot allocation, ticket generation, vehicle tracking, parking fee calculation and slot release.

## 3. Project Objectives

- Design an object-oriented model for a campus parking facility.
- Identify and implement appropriate Java classes and objects.
- Represent parking floors and slots using suitable data structures.
- Implement automatic parking slot allocation and release.
- Generate unique parking tickets.
- Record vehicle entry and exit times.
- Calculate parking fees based on vehicle type and parking duration.
- Support monthly passes for students and staff.
- Implement separate charging fees for electric vehicles.
- Apply inheritance, polymorphism and abstraction.
- Implement encapsulation using packages and access modifiers.
- Test and validate the complete parking management system.
- Extend the original design to support new vehicle categories and pricing rules.

## 4. Functional Requirements

The system must provide the following functionalities:

1. Manage multiple parking floors and numbered parking slots.
2. Register and identify vehicles using registration numbers.
3. Support cars, two-wheelers and electric vehicles.
4. Identify students, staff and visitors.
5. Allocate suitable available parking slots.
6. Generate unique parking ticket numbers.
7. Record vehicle entry time.
8. Release parking slots when vehicles exit.
9. Calculate parking fees according to vehicle type and duration.
10. Provide free parking for eligible students and staff with valid monthly passes.
11. Calculate separate electric vehicle charging fees.
12. Handle unavailable parking slots and invalid operations.

## 5. Object-Oriented Programming Requirements

The application demonstrates the following Java concepts:

- **Classes and Objects:** Represent vehicles, users, parking slots, tickets and parking facilities.
- **Constructors:** Initialise objects using default, parameterized and overloaded constructors.
- **Static Members:** Maintain shared information such as ticket counters.
- **Inheritance:** Create vehicle and user hierarchies.
- **Method Overriding:** Implement specialised vehicle behaviour.
- **Polymorphism:** Demonstrate method overloading and runtime method dispatch.
- **Abstraction:** Use abstract classes and interfaces.
- **Encapsulation:** Protect data using private fields, getters and setters.
- **Packages:** Organise the application into logical modules.
- **Object Class Methods:** Override equals(), hashCode() and toString() where appropriate.

## 6. System Components

The application is organised around the following components:

| Component | Responsibility |
|---|---|
| ParkingFacility | Manages parking floors and slot allocation |
| Vehicle | Maintains common vehicle information |
| Car | Represents cars and their parking rates |
| TwoWheeler | Represents two-wheelers |
| ElectricVehicle | Represents electric vehicles |
| ParkingSlot | Maintains slot information and availability |
| ParkingTicket | Stores ticket and entry information |
| User | Represents parking facility users |
| Student | Represents student users |
| Staff | Represents staff users |
| Visitor | Represents visitor users |
| Chargeable | Defines the electric vehicle charging capability |

## 7. Assignment Task Structure

The work is organised into the following tasks:

| Task | Description |
|---|---|
| Task 1 | Problem analysis and identification of objects |
| Task 2 | Data representation using Java data types and arrays |
| Task 3 | Control logic, slot allocation and fee calculation |
| Task 4 | Classes, objects and constructors |
| Task 5 | Static members and object life cycle |
| Task 6 | Inheritance hierarchy |
| Task 7 | Method overriding and Object class methods |
| Task 8 | Compile-time and runtime polymorphism |
| Task 9 | Abstract classes and interfaces |
| Task 10 | Packages, access modifiers and encapsulation |
| Task 11 | Complete implementation, testing and validation |
| Task 12 | Design adaptation for new requirements |

## 8. Extended System Requirements

The design is further extended to accommodate the following changes:

- Introduce e-bikes with a flat parking fee.
- Introduce delivery vans.
- Apply double the car parking rate to delivery vans between 9 AM and 5 PM.
- Support one-day parking passes for visitors.
- Expand the parking facility to five floors.
- Support different numbers of parking slots on each floor.
- Evaluate the existing design and implement suitable modifications.

## 9. Technologies and Tools

- Programming Language: Java
- Development Environment: VS Code / IntelliJ IDEA / Eclipse
- Java Development Kit (JDK)
- Version Control: Git
- Source Code Hosting: GitHub
- Documentation: Microsoft Word / PDF

## 10. Repository Structure

```text
CO1_Java_Assignment1/
│
├── Task01_Problem_Analysis/
├── Task02_Data_Representation/
├── Task03_Control_Logic/
├── Task04_Classes_Objects_Constructors/
├── Task05_Static_Members_Object_Lifecycle/
├── Task06_Inheritance_Hierarchy/
├── Task07_Method_Overriding/
├── Task08_Polymorphism/
├── Task09_Abstraction/
├── Task10_Packages_Encapsulation/
├── Task11_Implementation_Testing/
├── Task12_Design_Challenge/
└── README.md
```

## 11. Testing and Validation

The application is tested using different scenarios:

- Normal vehicle entry and exit.
- Successful parking slot allocation.
- Parking facility with no available slots.
- Releasing an occupied parking slot.
- Attempting to release an already-free slot.
- Invalid floor and slot numbers.
- Duplicate vehicle registration numbers.
- Parking fee calculation.
- Monthly pass validation.
- Electric vehicle charging fee calculation.
- Additional vehicle categories.
- Updated parking fee rules.

Program outputs, test results and execution screenshots are maintained in the respective task folders.

## 12. Expected Deliverables

The completed assignment repository contains:

- Individual task documentation.
- Java source code for the required programs.
- Completed code exercises.
- Complete Smart-Parking System implementation.
- UML class diagrams.
- Algorithmic pseudocode.
- Alternative concept explanations.
- Time and space complexity analysis.
- Test cases and execution results.
- Output screenshots.
- Final consolidated assignment report.
- Project README documentation.

## 13. Project Outcome

The Campus Smart-Parking System demonstrates how Java fundamentals and object-oriented programming principles can be applied to solve a practical parking management problem.

The design focuses on modularity, reusability, data protection, maintainability and extensibility. It provides a foundation for managing parking facilities and adapting to future vehicle categories and parking policies.

## 14. Student Information

**Student Name:** M. Venkata Vasu Deva Reddy

**Register Number:** 192424182

**Department:** B.Tech- Artificial Intelligence and Data Science

**Subject:** Programming in Java

**Assignment:** CO1 – Assignment 1

**GitHub Repository:** https://github.com/deva123932/CSA0918_JAVA.git

---

**Project:** Campus Smart-Parking System  
**Language:** Java  
**Repository:** CO1 Java Assignment 1
