# Introduction
In computerized information systems, data are the basic resource of the organization. Proper organization and management of data are required for an organization to run smoothly. A Database Management System (DBMS) deals with the knowledge of how data is stored and managed on a computerized information system.  

In any organization, accurate and reliable data are required for better decision-making, ensuring privacy of data, and controlling data efficiently.  

**Examples include:**  
- Deposit and/or withdrawal from a bank  
- Hotel, airline, or railway reservation  
- Purchase of items from supermarkets  

In all these cases, a database is accessed.

---

## What is Data?
Data are the known facts or figures that have implicit meaning. It can also be defined as the representation of facts, concepts, or instructions in a formal manner, suitable for understanding and processing.  

Data can be represented in:  
- Alphabets (A-Z, a-z)  
- Digits (0-9)  
- Special characters (+, -, #, $, etc.)  

**Examples:** `25`, `"ajit"`

---

## Information
Information is the processed data on which decisions and actions are based. It can be defined as organized and classified data that provides meaningful values.  

**Example:** `"The age of Ravi is 25"`

---

## File
A file is a collection of related data stored in secondary memory.

---

## File Oriented Approach
The traditional file-oriented approach to information processing means each application has a separate master file and its own set of personal files. In this approach, programs are dependent on files, and files are dependent upon programs.

---

## Disadvantages of File Oriented Approach
1. **Data redundancy and inconsistency**  
   - The same information may be written in several files.  
   - Redundancy leads to higher storage and access costs.  
   - It may cause data inconsistency, e.g., a changed customer address may be reflected in one file but not elsewhere in the system.  

2. **Difficulty in accessing data**  
   - Conventional file processing systems do not allow data to be retrieved in a convenient and efficient manner according to user choice.  

3. **Data isolation**  
   - Data are scattered in various files, possibly in different formats.  
   - Retrieving appropriate data with new application programs becomes difficult.  

4. **Integrity problems**  
   - Developers enforce data validation by adding code in application programs.  
   - When new constraints are added, modifying programs to enforce them is difficult.  

5. **Atomicity**  
   - Ensuring atomicity is difficult when transaction failures occur due to power failure, networking problems, etc.  
   - *Atomicity means either all operations of the transaction are reflected properly in the database or none are.*  

6. **Concurrent access**  
   - File processing systems do not allow multiple transactions to access the same file simultaneously.  

7. **Security problems**  
   - No security is provided in file processing systems to protect data from unauthorized user access.  ## 🏢 How SQL Is Used in Real Companies (Industry View)

In real-world companies, SQL is not used by just one person or one system.  
Instead, **many different users and tools interact with the same database simultaneously**.

## 📊 Database Interactions in a Company

### 👥 Human Users
Multiple people with different roles interact with the database:
- Data Engineers
- Data Analysts
- Data Scientists
- Developers
- Business Analysts

Each of them writes **different SQL queries** to:
- Read data
- Modify data
- Analyze data
- Build reports

---

### 🌐 Applications & Websites
Databases are also connected to:
- Websites
- Mobile applications
- Backend services

These applications:
- Automatically send SQL queries to the database
- Can generate **massive amounts of SQL queries** depending on user traffic
- Interact with the database continuously

---

### 📈 Data Visualization & BI Tools
Companies also use **data visualization tools** such as:
- Power BI
- Tableau
- Dashboards
- Reports for stakeholders and managers

These tools:
- Are directly connected to the database
- Automatically generate SQL queries
- Help decision-makers analyze business performance

---

## 🔁 Summary of Interactions

At any moment, the database receives SQL queries from:
- People
- Applications
- Websites
- Dashboards
- Reporting tools

➡️ This means **hundreds or thousands of SQL queries** may hit the database at the same time.

---

## 🧠 Why We Need a Database Management System (DBMS)

The database itself is just a **container for storing data**.  
It cannot manage requests on its own.

That’s why we need a **Database Management System (DBMS)**.

### 📌 What Is a DBMS?
A **DBMS** is a software that:
- Manages the database
- Handles incoming SQL queries
- Controls access and security
- Decides which query runs first (priority management)

---

### 🔐 Responsibilities of a DBMS
- Executes SQL queries
- Manages concurrent users
- Controls permissions (who can do what)
- Prevents unauthorized access
- Optimizes query execution

➡️ The DBMS acts as the **manager** between users and the database.

---

## 🖥️ The Role of Hardware: Servers

So far, we have:
- **Data** → stored in the database
- **Software** → DBMS managing the database

What’s missing?  
👉 **Hardware**

---

### 🧾 Why Not Use a Personal Computer?
- Personal computers are:
  - Not powerful enough
  - Not always online
  - Not reliable for enterprise systems

---

### 🖧 Servers
Companies use **servers**, which are:
- Very powerful machines
- Always running (24/7)
- Designed to handle heavy workloads

Servers can be:
- **On-premise** (inside the company)
- **Cloud-based** (AWS, Azure, GCP, etc.)

---

## 🧩 Complete Big Picture

Putting everything together:

- **Database** → Stores the data
- **SQL** → Language to talk to the database
- **DBMS** → Manages queries, security, and performance
- **Server** → Physical or cloud machine where everything runs

---

## ✅ Final Understanding

This is how SQL and databases look in real companies:
- Many users and systems send SQL queries
- DBMS manages all interactions
- Server ensures availability and performance
- Database safely stores and organizes data

This architecture is the **foundation of modern data systems**.
