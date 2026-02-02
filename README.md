# 🏦 FinTech API Automation Framework

## 📌 Project Overview

This repository contains an **end-to-end API Automation Testing Framework** developed for a **FinTech Digital Wallet & Payments platform**.  
The framework is designed to validate **critical financial workflows and security controls** exposed through REST APIs using industry-standard automation practices.

The automation solution focuses on ensuring:
- Functional correctness of APIs
- Secure handling of authentication and authorization
- Stability of wallet and payment operations
- Reliability of transaction processing

The framework closely mirrors **real-world MNC / Big-4 QA projects** and is suitable for **enterprise-scale automation**, **CI/CD pipelines**, and **interview demonstrations**.

---

## 🎯 Objectives

- Automate validation of FinTech APIs covering core banking use cases
- Ensure secure JWT-based authentication and authorization
- Validate positive, negative, regression, and security scenarios
- Provide detailed execution visibility through professional HTML reports
- Enable seamless CI/CD execution using Jenkins

---

## 🧩 Application Under Test (AUT)

**Domain:** FinTech / Banking / Payments  

The Digital Wallet platform provides APIs to:

- Authenticate users securely using **JWT tokens**
- Retrieve real-time wallet balance
- Transfer funds between accounts with business validations
- Fetch transaction history with filtering options
- Prevent invalid, duplicate, and unauthorized transactions
- Enforce security against common API threats

---

## 🛠 Technology Stack

| Purpose | Technology |
|------|-----------|
| Programming Language | Java 11 |
| API Automation | Rest Assured |
| Test Framework | TestNG |
| Build Tool | Maven |
| Reporting | Extent Reports (HTML – Dark Theme) |
| CI/CD | Jenkins |
| Version Control | GitHub |

---

## 🧪 Testing Scope

The framework automates testing for the following API areas:

### 🔐 Authentication
- Valid and invalid login
- Empty and malformed requests
- Injection attempts
- Token expiry and authorization handling

### 💰 Wallet
- Wallet balance retrieval
- Unauthorized and invalid token access
- Balance consistency across multiple calls
- Response time validation

### 🔄 Fund Transfer
- Valid fund transfers
- Zero, negative, and excessive amount validation
- Insufficient balance handling
- Same account and duplicate transaction prevention
- Invalid beneficiary account validation

### 📜 Transactions
- Transaction history retrieval
- Empty transaction scenarios
- Date-based filtering
- Invalid date handling
- Large data set validation
- Unauthorized access prevention

### 🔐 Security
- Header tampering
- Invalid HTTP methods
- XSS and malicious payload validation

---

## 🧪 Types of Testing Performed

- Functional Testing  
- Negative Testing  
- Security Testing  
- Regression Testing  
- Basic Non-Functional Testing (Response Time)

---

## 📊 Reporting & Execution Visibility

- Generates **Extent HTML Reports (Dark Theme)**
- Includes:
  - Test case execution status
  - Execution time
  - Failure evidence (dummy screenshots/logs)
  - Overall build status
  - Production deployment recommendation


