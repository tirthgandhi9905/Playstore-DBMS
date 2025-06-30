# 📱 Playstore DBMS Project

This repository contains the **complete database design and implementation** of a Playstore-style platform, developed as part of our **Database Management Systems (DBMS)** course project.

The project models real-world entities such as apps, books, developers, users, purchases, and promotional offers—mirroring the architecture and data flow of the Google Play Store.

---

## 📂 Repository Structure

| Section                 | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `ER-Diagram/`          | Entity-Relationship diagram (`Playstore_ER.png`)                            |
| `Relational-Schema/`   | List of relations with attributes, primary keys, and foreign keys           |
| `FD-Sets/`             | Minimal set of functional dependencies for each relation                    |
| `BCNF-Proofs/`         | Step-by-step BCNF normalization and proofs                                  |
| `SQL-Scripts/`         | SQL DDL script including table creation and constraint definitions          |
| `Triggers/`            | SQL triggers enforcing logical consistency (e.g., for downloads, ratings)   |

---

## 🚀 Key Features

- ✅ **Normalized Schema**: All relations are in **Boyce-Codd Normal Form (BCNF)**
- ✅ **Referential Integrity**: Foreign key constraints maintain consistency across entities
- ✅ **Logical Triggers**: Ensures valid operations like app downloads, purchases, and reviews
- ✅ **Scalable Design**: Structured for potential expansion in future applications
- ✅ **Real-World Entities**: Includes apps, users, developers, books, offers, and purchases

---

## 💻 Tech Stack

- **PostgreSQL** for schema implementation, constraints, and triggers
- **SQL** (DDL, Triggers, Normalization proofs)
- **Dia Software** for ER diagram design
- **Git & GitHub** for version control and collaboration

---

## 📸 ER Diagram Preview

![ER Diagram](ER-Diagram/Playstore_ER.png)

---

## ⚙️ How to Use

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/tirthgandhi9905/Playstore-DBMS.git
   cd Playstore-DBMS
