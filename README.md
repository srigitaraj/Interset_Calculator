💰 Smart Interest Calculator – Java System Design
📌 Overview

This project is a Java-based Smart Interest Calculator that goes beyond traditional formulas.
Unlike generic interest calculators, this system incorporates tenure, age, and gender to determine more personalized interest rates, simulating how banks or financial institutions offer differential interest rates to various customer categories.

The project emphasizes System Design + OOP concepts to showcase:

Scalable architecture

Clean code principles

Real-world use case alignment (banking/finance domain)

✨ Key Features

📍 Calculates interest based on Principal, Tenure, Age, and Gender

📍 Dynamic interest rate adjustment (e.g., senior citizens or women may get higher interest rates)

📍 Both Simple & Compound Interest modes supported

📍 OOP-driven architecture – clear separation of model, service, and controller

📍 Easily extendable to other financial schemes (loans, FD, RD, etc.)

🏗️ System Design Highlights

The application follows a Layered + Modular Design approach:

Model Layer – Encapsulates customer details (age, gender, tenure, principal).

Service Layer – Business logic to compute interest dynamically.

Controller Layer – Handles input/output interaction.

Utility Layer – Validations & formatting.

Design Principle Used:

Encapsulation (data hiding in models)

Abstraction (services expose only necessary operations)

Open-Closed Principle (system can be extended without modifying core logic)

⚙️ Tech Stack

Language: Java (JDK 8+)

Design Style: System Design + OOP

Build Tool: Maven/Gradle (optional)

IDE: IntelliJ IDEA / Eclipse / VS Code
