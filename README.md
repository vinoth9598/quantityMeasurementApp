# Quantity Measurement App

## Overview

Quantity Measurement App is a Java-based application developed using Test-Driven Development (TDD) principles. The application supports comparison, conversion, and arithmetic operations for various measurement types such as Length, Weight, Volume, and Temperature.

The project evolves feature-by-feature through Git branches, with each branch representing a specific use case implementation.

---

## Technologies Used

* Java
* JUnit 5
* JDBC
* MySQL
* Maven
* Git Flow

---

## Branches and Features

### UC1 - Feet Equality

**Branch:** `feature/UC1-feet-equality`

Implemented equality comparison between two feet measurements.

**Example:**

* 5 ft == 5 ft → True

---

### UC2 - Feet Inch Equality

**Branch:** `feature/UC2-feet-inch-equality`

Added comparison between feet and inch measurements through unit conversion.

**Example:**

* 1 ft == 12 in → True

---

### UC3 - Generic Quantity Class

**Branch:** `feature/uc3-generic-quantity-class`

Introduced a reusable Quantity class to represent measurement values and units.

---

### UC4 - Extended Unit Support

**Branch:** `feature/UC4-extended-unit-support`

Added support for additional length units.

Supported Units:

* Feet
* Inch
* Yard
* Centimeter

---

### UC5 - Unit Conversion Support

**Branch:** `feature/UC5-unit-conversion-support`

Implemented conversion logic between supported units.

Features:

* Standard conversion formulas
* Cross-unit comparison

---

### UC6 - Length Addition

**Branch:** `feature/uc6-length-addition`

Added arithmetic addition for length measurements.

**Example:**

* 1 ft + 12 in = 2 ft

---

### UC7 - Explicit Target Unit Addition

**Branch:** `feature/UC7-explicit-target-unit-addition`

Allows addition results to be returned in a specified target unit.

**Example:**

* 1 ft + 12 in = 24 in

---

### UC8 - Standalone Length Unit Refactor

**Branch:** `feature/uc8-standalone-lengthunit-refactor`

Refactored length unit handling into dedicated classes for better maintainability.

---

### UC9 - Weight Measurement Support

**Branch:** `feature/UC9-weight-measurement-support`

Added weight measurement functionality.

Supported Units:

* Gram
* Kilogram
* Ton

Features:

* Equality comparison
* Unit conversion

---

### UC10 - Generic Quantity Architecture

**Branch:** `feature/UC10-generic-quantity-architecture`

Introduced a scalable architecture for handling multiple measurement categories.

---

### UC11 - Volume Measurement Support

**Branch:** `feature/UC11-volume-measurement-support`

Added volume measurement functionality.

Supported Units:

* Liter
* Milliliter
* Gallon

Features:

* Conversion
* Equality comparison

---

### UC12 - Subtraction and Division Operations

**Branch:** `feature/UC12-subtraction-division-operations`

Added advanced arithmetic operations.

Features:

* Subtraction
* Division

---

### UC13 - Centralized Arithmetic Logic

**Branch:** `feature/UC13-centralized-arithmetic-logic`

Centralized arithmetic calculations into a common calculation engine.

Benefits:

* Reduced code duplication
* Improved maintainability

---

### UC14 - Temperature Support

**Branch:** `feature/UC14-temperature-support-with-optional-arithmetic`

Added temperature measurements.

Supported Units:

* Celsius
* Fahrenheit
* Kelvin

Features:

* Temperature conversion
* Equality comparison
* Optional arithmetic operations

---

### UC15 - N-Tier Architecture Refactor

**Branch:** `feature/UC15-N-Tier-Architectures-refactor`

Refactored the application into N-Tier Architecture.

Layers:

* Presentation Layer
* Business Layer
* Data Access Layer

Benefits:

* Separation of concerns
* Better scalability
* Easier testing

---

### UC16 - Database Layer JDBC

**Branch:** `feature/uc16-database-layer-jdbc`

Implemented JDBC-based persistence layer.

Features:

* Database connectivity
* CRUD operations
* Repository pattern

---

## Project Features Summary

### Length Measurements

* Feet
* Inch
* Yard
* Centimeter

### Weight Measurements

* Gram
* Kilogram
* Ton

### Volume Measurements

* Liter
* Milliliter
* Gallon

### Temperature Measurements

* Celsius
* Fahrenheit
* Kelvin

### Supported Operations

* Equality Comparison
* Unit Conversion
* Addition
* Subtraction
* Division

---

## Project Structure

```text
src
├── model
├── service
├── repository
├── presentation
├── database
└── test
```

---

## Run the Project

```bash
git clone <repository-url>
cd quantity-measurement-app
mvn clean test
```

---

## Future Enhancements

* Spring Boot Integration
* REST API Development
* Hibernate/JPA Support
* Docker Deployment
* Cloud Database Support

---

## Author

Quantity Measurement App developed using Java and TDD methodology to demonstrate object-oriented design, unit conversion, arithmetic operations, architecture refactoring, and database integration.
