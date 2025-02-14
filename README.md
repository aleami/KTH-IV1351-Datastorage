## KTH-IV1351-Datastorage
<hr>

## 🎵 Music School Database Project README

**📘 Project Overview**

This repository contains the Music School Database project for the KTH IV1351 Data Storage course. The project models a database for managing music school operations, including lessons, instructors, students, instruments, and pricing.

**📁 Repository Structure**

- _Task 1:_ Conceptual Model Design (see attached diagram below)

- _Task 2:_ SQL Implementation for Database Schema and Queries

- _Task 3:_ SQL Implementation for Data Manipulation and Testing

**🛠️ Technologies Used**

- SQL: Used for implementing database schema, queries, and data manipulation for Tasks 2 and 3 using **Astah**

**🤝 Collaboration**

_This project was completed in collaboration with two other students._

**📊 Conceptual Model Diagram**
_The provided diagram models the following entities and relationships:_

- _Person:_ Parent entity with attributes like personNumber (unique), name, contact details, etc.

- _Instructor:_ Inherits from Person; can teach specified instruments.

- _Student:_ Inherits from Person; may rent instruments and participate in lessons.

- _Instrument:_ Contains type, brand, availability, and renting price.

- _RentInstrument:_ Represents instrument rentals by students.

- _Lesson:_ General lesson entity with date; subtypes include Ensemble, Group, and Individual lessons.

- _PriceScheme:_ Defines pricing based on lesson type and skill level.

- _Key constraints include:_

  - Max 2 instruments per student.

  - Lease up to 12 months.

  - All attributes are NOT NULL unless specified.

**📈 Task 1: Conceptual Model**
<img width="900" alt="Conceptual Model" src="https://github.com/user-attachments/assets/d173ed8f-f27c-411f-8ad7-b8bc1782bf5c" />
