Hospital Management System

Overview

The Hospital Management System is a C++ program designed to streamline the management of hospital resources, including patients, doctors, beds, and emergency situations. It incorporates object-oriented programming concepts to ensure modularity, reusability, and scalability.

Features

1. Role-Based Menus

Owner Menu: Add and view doctors, display all patients, and check bed statuses.

Doctor Menu: Search and view patient details.

Receptionist Menu: Add patients, assign emergency priorities, and view emergency patients.

Patient Menu: View personal details by ID.

2. Patient Management

Add Patients: Receptionists can add new patients, capturing essential details such as name, age, disease, assigned doctor, and bed allocation.

Search Patients: Search by ID or name for quick access to patient records.

3. Doctor Management

Up to 4 doctors can be registered with their details (ID, name, age, phone number).

4. Bed Management

Tracks the availability of 20 hospital beds.

Beds are assigned automatically when a new patient is added.

Beds can be released when a patient is discharged.

5. Emergency Queue

Implements a min-heap to manage emergency patients based on their priority levels.

View the list of emergency patients in order of urgency.

Programming Concepts Used

1. Object-Oriented Programming (OOP)

Classes and Objects:

Classes: Patient, Doctor, Hospital

Encapsulation bundles data and methods.

Constructors: Parameterized constructors for initializing objects.

Composition: Hospital contains Doctor objects and manages a linked list of Patient objects.

2. Data Structures

Linked List: Used for managing the list of patients.

Array: Stores doctor information, bed statuses, and the min-heap for emergencies.

3. Control Flow

Loops (for, while) and conditional statements (if-else, switch) manage program logic.

4. Min-Heap Implementation

Heapify-Up: Maintains the heap property for emergency patient priorities.

Benefits

Efficiency: Automates bed assignments and priority management.

Modularity: Role-based menus ensure clear separation of responsibilities.

Scalability: Easily extendable to support additional features or roles.

User-Friendly: Simple console-based interface for seamless interaction.

Potential Improvements

Add a graphical user interface (GUI) for better usability.

Enhance data security by implementing file storage with encryption.

Introduce automated memory management to prevent potential memory leaks.

Conclusion

The Hospital Management System demonstrates the effective use of C++ programming concepts to create a functional and organized application. It efficiently handles hospital operations, ensuring better resource allocation and patient care.
