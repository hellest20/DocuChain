# 📄 DocuChain – Decentralized Document Verification System

DocuChain is a **Java-based decentralized document verification platform** that combines the robustness of **Spring Boot** with a **lightweight blockchain implementation**.  
It enables organizations, universities, and individuals to **securely issue, verify, and share documents** (e.g., diplomas, certificates, contracts) without relying on a central authority.

---

## 🚀 Features

- 🔒 **Blockchain-Backed Integrity** – Each document is stored with a unique cryptographic hash, ensuring tamper-proof verification.  
- 🏛 **Decentralized Verification** – No single point of failure; documents can be verified by anyone with access to the blockchain.  
- 🌍 **REST API** – A clean, developer-friendly API built with **Spring Boot** to issue and verify documents.  
- 🗄 **Persistence Layer** – Documents and blockchain data are stored in an embedded **H2 database** (can be swapped for PostgreSQL/MySQL).  
- 📊 **Auditability** – Every transaction is immutable and traceable, allowing for transparent audits.  
- 🧩 **Modular Architecture** – Designed to be extended (e.g., adding consensus mechanisms, JWT authentication, or multi-node support).  

---

## 🛠 Tech Stack

- **Java 21**
- **Spring Boot 3**
- **Spring Data JPA**
- **H2 Database** (default; can be replaced with PostgreSQL/MySQL)
- **Maven** for dependency management
- **JUnit 5** for testing

---

## 📂 Project Structure

