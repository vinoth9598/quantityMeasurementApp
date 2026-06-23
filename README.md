Quantity Measurement App

A Java-based application that supports measuring, comparing, converting, and performing arithmetic operations on different quantities such as Length, Weight, Volume, and Temperature. The application follows Test-Driven Development (TDD), Object-Oriented Design principles, and evolves through multiple use cases using GitFlow branching.
Project Overview

  The Quantity Measurement App provides:

  Unit Equality Comparison
  Unit Conversion
  Arithmetic Operations
  Multiple Measurement Types
  Generic Quantity Architecture
  N-Tier Architecture
  Database Persistence using JDBC
  
dev/
├── UC1-Feet-Equality.md
├── UC2-Feet-Inch-Equality.md
├── UC3-Generic-Quantity-Class.md
├── UC4-Extended-Unit-Support.md
├── UC5-Unit-Conversion-Support.md
├── UC6-Length-Addition.md
├── UC7-Explicit-Target-Unit-Addition.md
├── UC8-Standalone-LengthUnit-Refactor.md
├── UC9-Weight-Measurement-Support.md
├── UC10-Generic-Quantity-Architecture.md
├── UC11-Volume-Measurement-Support.md
├── UC12-Subtraction-Division-Operations.md
├── UC13-Centralized-Arithmetic-Logic.md
├── UC14-Temperature-Support.md
├── UC15-N-Tier-Architecture-Refactor.md
└── UC16-Database-Layer-JDBC.md

Branch: feature/UC1-feet-equality
Objective

Implement equality comparison between two measurements in Feet.

Requirements
Create Feet class.
Support value comparison.
Two feet values with same length should be equal.
