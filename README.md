# 🚀 API Automation Framework using Rest Assured (Java)

### 👨‍💻 Author: **Shashikant Rai**
A **powerful, scalable, and CI/CD-ready API Automation Framework** built using **Rest Assured + Java** for testing **Restful Booker CRUD APIs**.

---

## 📌 Project Highlights

✅ End-to-End REST API Automation  
✅ Hybrid Framework Design  
✅ CI/CD Enabled with Jenkins  
✅ Parallel Test Execution  
✅ Allure Advanced Reporting  
✅ Integration Testing Included  
✅ Clean Code + Maintainable Structure

---

## ▶️ Run the Test Suite

```bash
mvn test -Dsurefire.suiteXmlFiles=testng.xml
````

📸 **Execution Preview** <img width="1130" src="https://github.com/PramodDutta/APIAutomationRestAssured/assets/1409610/69f398b3-8798-4fba-a091-3b1e321dcc7d">

---

## 🛠️ Tech Stack

| 🔧 Tool             | 📘 Description      |
| ------------------- | ------------------- |
| ☕ Java              | JDK > 22            |
| 🧪 Rest Assured     | API Automation      |
| 📦 Maven            | Build Tool          |
| ✅ TestNG            | Test Execution      |
| 📊 Apache POI       | Data Handling       |
| 🧠 AssertJ          | Advanced Assertions |
| 🔁 Jackson + GSON   | Serialization       |
| 📝 Log4j            | Logging             |
| 📈 Allure           | Reporting           |
| 🧱 Hybrid Framework | Scalable Design     |
| 🤖 Jenkins          | CI/CD               |

---

## 🗂️ Framework Architecture

📸 **Framework Components**
![Framework](https://github.com/PramodDutta/APIAutomationFramworkATB6x/assets/1409610/98bbc62d-7837-4bdc-900b-b214c675af6d)

---

## 🔁 CI/CD Execution (Jenkins)

📸 **Pipeline Execution** <img width="1262" src="https://github.com/PramodDutta/APIAutomationRestAssured/assets/1409610/2d58bf82-0ffb-4fcb-a2d9-cf26920fa7b5">

---

## ⚙️ Maven Configuration (pom.xml)

```xml
<build>
  <plugins>
    <plugin>
      <groupId>org.apache.maven.plugins</groupId>
      <artifactId>maven-surefire-plugin</artifactId>
      <version>3.3.0</version>
      <configuration>
        <suiteXmlFiles>
          <suiteXmlFile>${suiteXmlFile}</suiteXmlFile>
        </suiteXmlFiles>
      </configuration>
    </plugin>
  </plugins>
</build>
```

### ▶️ Run Using:

```bash
mvn clean test -DsuiteXmlFile=testng.xml
```

---

## ⚡ Parallel Execution

```xml
<suite name="All Test Suite" parallel="methods" thread-count="2">
```

✅ Faster test execution
✅ Optimized resource usage

---

## 🔗 Integration Test Execution

```bash
mvn clean test -DsuiteXmlFile=testng-integration.xml
```

Includes:

* ✅ Token Creation
* ✅ Booking Creation
* ✅ Update Booking
* ✅ Delete Booking

---

## 📊 Allure Reporting

### ▶️ Serve Allure Report

```bash
allure serve allure-results/
```

📸 **Allure Dashboard**
![Allure](https://github.com/PramodDutta/APIAutomationFramworkATB6x/assets/1409610/79ba2093-a1b7-4b36-ba16-9a6827af7afe)

---

## 🧾 Allure Setup Guide

### 1️⃣ Install Allure (Mac)

```bash
brew install allure
```

### 2️⃣ Add Dependency

```xml
<dependency>
  <groupId>io.qameta.allure</groupId>
  <artifactId>allure-testng</artifactId>
  <version>2.13.0</version>
</dependency>
```

### 3️⃣ Add Allure Plugin

```xml
<plugin>
  <groupId>io.qameta.allure</groupId>
  <artifactId>allure-maven</artifactId>
  <version>2.10.0</version>
  <configuration>
    <reportVersion>2.13.0</reportVersion>
  </configuration>
</plugin>
```

### 4️⃣ Generate Report

```bash
mvn clean test
allure generate target/allure-results --clean -o allure-report
allure open allure-report
```

---

## 🧪 POSTMAN Assignment Scenarios

### ✅ CRUD Operations with Authorization

1️⃣ Create ➝ Update ➝ Get ➝ Verify
2️⃣ Create ➝ Delete ➝ Verify Not Found
3️⃣ Get Existing ➝ Update ➝ Verify
4️⃣ Create ➝ Delete
5️⃣ Invalid Payload Validation
6️⃣ Update on Deleted ID

### ✅ Single Request Validation

* ✔️ Status Code
* ✔️ Headers
* ✔️ Response Body

---

## 📦 Create Postman Collection

* ✅ Restful Booker CRUD
* ✅ Test Scripts from Snippets
* ✅ Hardcoded Integration Scenarios

---

## 🌟 Why Use This Framework?

✅ Clean Architecture
✅ CI/CD Ready
✅ Parallel Execution
✅ Advanced Assertions
✅ Real-World API Scenarios
✅ Reporting with Dashboards

---

📩 **Connect With Me**

* 🔗 LinkedIn
* 🌐 Portfolio
* 🎥 YouTube – Automation & AI Testing

---