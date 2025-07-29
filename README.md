**Abstract:**

The Library Management System aims to streamline the management of library operations by providing a digital solution for book cataloging, member registration, borrowing and return tracking, and fine management. The system will leverage MySQL as the database management system to ensure efficient data storage and retrieval, supporting both administrators (librarians) and end-users (library members). It will enhance the efficiency of book tracking, minimize manual efforts, and provide insightful reports for better decision-making.



**Problem Statement:**

Libraries face challenges in managing their book inventories, tracking member borrowing history, and handling overdue fines efficiently. A well-structured system is required to automate these processes, ensure data accuracy, and provide quick access to necessary records. The proposed system aims to address these challenges by offering a structured database-driven solution with easy-to-use interfaces.

**Data Requirements:**

- *Books*: Book ID, title, author, genre, ISBN, publication year, and availability status.
- *Members*: Member ID, name, email, phone number, membership type, and registration date.
- *Transactions*: Records of issued books, issue dates, due dates, and return dates.
- *Fines*: Overdue penalties calculated based on return delays.

**Functional Requirements:**

Book Management:

- Add, update, and delete book records.
- Search books by various criteria.

Member Management:

- Register new members and manage their details.
- View borrowing history and outstanding dues.

Borrowing & Returns:

- Issue and return books with automated due date tracking.
- Automatic fine calculation for overdue returns.

Reporting and Analytics:

- Generate reports on book availability, member activity, and fines collected.
- Provide insights into popular books and borrowing trends.



**Requirement Gathering and Design:**

Stakeholders:

- Librarians (Administrators)
- Library Members (Students, Faculty)

System Design Approach:

- A relational database model using Oracle SQL to store and manage library data efficiently.
- Frontend interface to allow users to search books and manage their accounts.
- Role-based access to ensure security and prevent unauthorized operations.
- Proposed Deliverables:
- Entity-Relationship Diagram (ERD) to visualize data relationships.
- Functional workflow and wireframe designs for UI/UX.
- SQL scripts for creating and managing the database.



**Conclusion:**

The Library Management System will optimize library operations by offering a centralized digital solution to manage books and members efficiently. The project will focus on ensuring data accuracy, improving accessibility, and automating routine tasks to reduce manual workload.

***ER Tables***

<img width="576" height="376" alt="Aspose Words ef69923d-1570-4884-b897-ad0e1d3e339b 001" src="https://github.com/user-attachments/assets/d6643db0-0f6f-480d-8c39-b7a267109a4b" />

**Normalised Tables**

<img width="495" height="407" alt="Aspose Words ef69923d-1570-4884-b897-ad0e1d3e339b 002" src="https://github.com/user-attachments/assets/a2a7cf4b-ed7c-4db9-a665-264d0b05eda6" />
