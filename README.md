# Secure Data Exchange, Boolean Data Modelling, and Database Normalization

## 1. Project Overview

This coursework explores key concepts related to secure data exchange, Boolean logic for data modelling, and database normalization in computer systems. The project analyzes how data is structured, processed, and protected in modern computing environments.

The study focuses on three main areas:
1. The role of encoding formats and protocols in secure data exchange
2. The use of Boolean logic and set operations as tools for data modelling
3. The importance of database normalization for efficient data storage and management
   
Through theoretical explanations, diagrams, and practical examples, the project demonstrates how these concepts contribute to building secure, reliable, and efficient information systems.

## 2. Objectives of the Coursework

The main objectives of this project are:
1. To examine how encoding formats support secure and reliable data exchange
2. To demonstrate the use of Boolean logic and set operations in data modelling
3. To analyze the importance of cryptography in protecting data
4. To understand how database normalization improves data storage and processing

## 3. Alignment with Module Learning Outcomes

This coursework aligns with the assessed module learning outcomes in the following ways:

1. Demonstrates the use of Boolean logic and set operations as tools for modelling relationships between datasets.
2. Analyzes the role of cryptography and encoding techniques in maintaining data confidentiality and integrity.
3. Examines how data storage structures and database design influence the efficiency and reliability of computer systems.

##4. Report Structure

The report is organized into several sections that progressively explore the concepts covered in this coursework.

### Section 1: Introduction
Introduces the topic of secure data exchange and explains the objectives of the study.

### Section 2: Encoding Formats and Secure Data Exchange
Explains different encoding formats used in computer systems and their role in enabling reliable communication between systems.

### Section 3: Boolean Logic and Data Modelling
Explores how Boolean logic and set theory are used to represent relationships between datasets and support logical decision-making processes.

### Section 4: Database Normalization
Discusses the importance of organizing data efficiently using normalization techniques such as:
First Normal Form (1NF)
Second Normal Form (2NF)
Third Normal Form (3NF)

### Section 5: Analysis and Evaluation
Provides a critical evaluation of the discussed concepts and their impact on modern computer systems.

### Section 6: Conclusion
Summarizes the key findings and emphasizes the importance of secure data exchange, logical data modelling, and efficient data storage.

## 5. Figures Included in the Report
The report contains several figures to visually explain important concepts.

<img width="806" height="419" alt="image" src="https://github.com/user-attachments/assets/83fdde1b-2054-47b9-be5a-21501760f151" />
Figure 1: Encoding Process

<img width="923" height="950" alt="image" src="https://github.com/user-attachments/assets/7cc36539-57b6-4a30-b70a-566a79978d30" />
Figure 2: Table of comparison of encoding formats

<img width="831" height="565" alt="image" src="https://github.com/user-attachments/assets/f3f38b09-13de-4edd-aa21-dcc0de4e7148" />
Figure 3: Encoding and TLS in HTTPS Data Transmission

<img width="767" height="721" alt="image" src="https://github.com/user-attachments/assets/a1389667-0890-47ea-9a45-186bdc6e8771" />
Figure 4: Universal Set Representation of Students

<img width="923" height="235" alt="image" src="https://github.com/user-attachments/assets/63446185-384b-420a-b92c-733be2b76cf9" />
Figure 5: Figure of Boolean Logic

<img width="871" height="450" alt="image" src="https://github.com/user-attachments/assets/e3bcd2a9-bddb-4a83-a78f-9a2dd41ddb66" />
Figure 6: Permutation Figure

<img width="922" height="447" alt="image" src="https://github.com/user-attachments/assets/f554c192-0387-48d8-9186-5e5fa5c721e6" />
Figure 7: ER Diagram


## 6. Code Implementation
### 1. Database
```
CREATE DATABASE coursework;
USE coursework;
```

### 2. Unnormalized Table
```
CREATE TABLE StudentClub (
    StudentID INT,
    StudentName VARCHAR(50),
    Email VARCHAR(50),
    ClubName VARCHAR(50),
    ClubRoom VARCHAR(20),
    ClubMentor VARCHAR(50),
    JoinDate DATE
);
```

## 7. Code Implementation Result

### 1. 1NF 
<img width="928" height="318" alt="image" src="https://github.com/user-attachments/assets/fa6b454c-382d-481b-9718-a8ada96ec7b4" />

### 2. 2NF
<img width="918" height="359" alt="image" src="https://github.com/user-attachments/assets/75b004dc-1f80-4900-af52-64ae51ec7d1e" />
<img width="918" height="327" alt="image" src="https://github.com/user-attachments/assets/9fdc8bc1-8a4d-458f-9877-04e67d0e840d" />
<img width="929" height="524" alt="image" src="https://github.com/user-attachments/assets/8cf5dec7-796d-47b3-aa62-35b7d8debedd" />

### 3. The Student Table
<img width="938" height="519" alt="image" src="https://github.com/user-attachments/assets/f7eeb2bb-c0a4-4fb5-bdc6-f89e0daa26d6" />

### 4. The Club Table
<img width="938" height="403" alt="image" src="https://github.com/user-attachments/assets/e64ef2d4-6a7c-440a-9058-3f84e69b313a" />

### 5. JOIN Operation Name
<img width="939" height="697" alt="image" src="https://github.com/user-attachments/assets/c7dd3e5e-5fe8-476e-8e57-f5a5448f8246" />

### 6. JOIN Operation Table
<img width="937" height="689" alt="image" src="https://github.com/user-attachments/assets/2a3f1885-02a1-470a-9c4e-a92e04c8ab84" />

## 7. Limitations

Some limitations of the study include:
1. The project focuses mainly on conceptual analysis rather than full system implementation.
2. Real-world database systems may involve additional complexities beyond the examples discussed.

## 8. Conclusion
The coursework looks at the most important ideas. Those ideas includes sharing data safely, using math logics and designing databases. The encoding formats are described firstly. These includes ASCII, Base64, URL Encoding and Hexadecimal. These help different computers to communicate. Moreover, they do this without errors. However, these formats do not keep data secret on their own. Rules like TLS must be used to fix this. The coursework also showed the use of math and logic. It helps to solve problems. Moreover, three simple steps help to make the table normalized. This made the system faster. A strong system needs three things. Those are the right data formats, clear logic and clean tables. These work together to keep information safe and correct. It also makes the system efficient.
