🏥 Java Hospital Management System

This project is a desktop-based Hospital Management System developed using Java and Object-Oriented Programming concepts. The system is designed to simulate real hospital operations including patient registration, appointment scheduling, billing, medical records, and staff management.

The application demonstrates core OOP principles such as abstraction, inheritance, encapsulation, and polymorphism. Data is stored and retrieved using file handling techniques instead of databases, making it suitable for beginner-level learning and academic purposes. There are several areas that can be improved in future versions, such as UI design, database integration, and advanced validation.
This project represents my learning progress and foundation in software development.

📌 This project focuses on

Clean object-oriented class structure
Encapsulation of data
Inheritance between related entities
Abstraction using abstract classes
Basic polymorphism through method overriding
File handling for persistent storage


🚀 Key features include

Patient record management

Appointment scheduling system

Medical report handling

Billing and charge calculation

Staff and administrator management

File-based persistent data storage


🛠 Technologies used
- Java
- Swing GUI
- NetBeans IDE
- File handling (text files)

📌 System Architecture

This project is built using Object-Oriented Programming principles. The system is designed around real-world hospital entities modeled as Java classes.

🏗 Class Structure

Person (Abstract base class)

Patient

Doctor

MedicalStaff (Abstract)

Administrator

Appointment

Bill & ChargeItem

MedicalRecord

PatientCareRecord

TestReport



🧠 Core Classes Overview

🎯 Person
Base class representing common human details such as name, contact information, and date of birth. It provides shared attributes for all people in the system.

🎯 Patient
Extends Person. Handles patient registration, medical history, insurance details, and hospital records.

🎯 MedicalStaff
Represents hospital staff members. Contains shared properties such as department, salary, and work schedule.

🎯 Doctor
Extends MedicalStaff. Responsible for diagnosis, prescriptions, and appointments.

🎯 Administrator
Handles system management tasks such as reports, billing, and record control.

🎯 Appointment
Manages scheduling and tracking of patient visits.

🎯 MedicalRecord
Stores diagnosis, treatment history, and medical summaries.

🎯 Bill & ChargeItem
Responsible for billing calculations and insurance discounts.




🧠 OOP Concepts Used


🔹 Encapsulation
Each class protects its internal data using private attributes and public getter/setter methods.

🔹 Inheritance
Classes like Patient, Doctor, and Administrator inherit common properties from the base Person class.

🔹 Abstraction
Abstract classes such as Person and MedicalStaff define common behavior while allowing subclasses to implement specific functionality.

🔹 Polymorphism
Different staff types override shared methods like login and duty handling.



🎓 Purpose

This project was developed as a solo first-year academic assignment to strengthen understanding of Java fundamentals, OOP design,  and file handling.

🔮 Future Improvements

- Database integration
- Improved UI design
- Advanced validation
- Error handling
- Role-based authentication
- Reporting dashboards

To run the project
1. Download the ZIP file
2. Extract it
3. Open the project in NetBeans IDE

👨‍💻 Author

Solo first-year academic project

Developed as part of Java OOP learning journey.



📜 License

This project is for educational purposes.

You may use or modify it for learning.
