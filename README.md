Pharmacy Management System(PMS):
1. Introduction:
The Pharmacy Management System is a digital solution designed to handle pharmaceutical inventory and sales. It allows administrators to track stock and provides customers with a platform to view and purchase medicines through an automated billing process.
2. Objective:
To design a secure, automated pharmacy management system that handles real-time stock updates, automated billing with discount logic, and secure admin access for inventory oversight.  
3. Problem Statement:
The "What": This project addresses the inefficiency of manual record-keeping in small-to-medium pharmacies.  
The "Why": Manual systems often lead to errors in stock counts and missed expiration dates. This system ensures that medicines like ORS, Nuberol, and Hydralin are monitored for expiry and that stock levels are updated instantly after every sale.  
4. Methodology:
Approach: The system uses a modular structure in C, utilizing functions such as adminLogin(), customerOrder(), and listMedicines().  
Data Handling: Parallel arrays are used to store data for 50 medicines, including prices (e.g., Panadol at 36 PKR) and quantities.
Libraries: The project utilizes standard C libraries including <stdio.h> for input/output and <string.h> for data manipulation.  
5. Project Scope:
Inclusions: Real-time stock reduction, admin-secured history logs, and a 20% discount trigger for orders exceeding 5 items.  
Exclusions: This version does not include a GUI (Graphical User Interface) or an external SQL database integration.  
Assumptions: We assume a distributed environment for customer interactions and that customers have email access for bill processing.  
6. Feasibility Study:
Risks Involved: Data loss may occur if the program is closed without file saving; this will be managed by implementing a persistent logging system.  
Resource Requirements: A computer with a C compiler (GCC/MinGW) and standard terminal access.  
7. Solution Application Areas:
Target Domain: Local pharmacies and small clinics.  
Benefit: It provides a faster, more accurate way to handle customer billing and monitor total stock value (currently supporting values up to 50 unique items).  
8. Tools/Technology:
Hardware: Standard PC.  
Software: C Language, Dev-C++ or VS Code IDE.  
9. Expertise of the Team Members:
The team members have completed relevant coursework in Structured Programming and have a shared interest in automation and healthcare technology.  
10. Milestones:
Tasks
Description

System Architecture 
 Defining arrays for 50 medicine IDs and names.

Admin Module 
 Implementing secure login and stock history viewing.

Customer Module 
 Developing the ordering system and discount logic.

Testing & Q/A
 Verification of billing accuracy and expiry alerts.


11. References:
1. Kernighan, Brian and Ritchie, Dennis. “The C Programming Language”. New York: Prentice Hall, 1988.  
2. “C Standard Library Documentation”. 2024. ISO/IEC. Viewed December 2025. https://en.cppreference.com/w/c.  
3. “SMI University Project Proposal Guidelines”. 2025. Department of Computer Science. SMI University, Karachi.
