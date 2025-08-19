
# Java OOP Projects: Car Rental System & Employee Payroll System

## 1. Car Rental System

A console-based car rental management application implementing core OOP principles.

### Features
- **Car Management**:
  - Add cars with details (ID, brand, model, price)
  - Track availability status
- **Customer Management**:
  - Register new customers
  - Maintain customer records
- **Rental Operations**:
  - Rent available cars to customers
  - Calculate rental costs based on duration
  - Process car returns
- **Interactive Menu**:
  - User-friendly console interface
  - Input validation for operations

### Key OOP Concepts Implemented
- Encapsulation (private fields with getters)
- Composition (Rental class combines Car and Customer)
- Collections Framework (ArrayList for data storage)
- Exception handling through input validation

### How to Run
1. Compile: `javac Main.java`
2. Execute: `java Main`
3. Follow the menu prompts

### Sample Data
The system comes pre-loaded with sample cars:
- Toyota Camry ($60/day)
- Honda Accord ($80/day)
- Mahindra Thar ($150/day)

## 2. Employee Payroll System

An abstract class-based payroll management system handling different employee types.

### Features
- **Employee Types**:
  - Full-time employees (monthly salary)
  - Part-time employees (hourly wage)
- **Payroll Operations**:
  - Add/remove employees
  - Calculate salaries polymorphically
  - Display all employee details
- **Abstract Class Implementation**:
  - Base Employee class with abstract calculateSalary()
  - Specialized child classes for each employee type

### Key OOP Concepts Implemented
- Abstraction (abstract Employee class)
- Polymorphism (salary calculation)
- Inheritance (FullTimeEmployee/PartTimeEmployee extend Employee)
- ArrayList for employee storage

### How to Run
1. Compile: `javac Main.java`
2. Execute: `java Main`
3. System displays initial and modified employee lists

### Sample Data
Pre-configured with:
- 3 full-time employees
- 2 part-time employees

### Project Structure   
Java-OOP-Projects/
├── CarRentalSystem/
│ ├── Main.java # Entry point
│ ├── Car.java # Car entity
│ ├── Customer.java # Customer entity
│ └── Rental.java # Rental transaction
│
└── EmployeePayroll/
├── Main.java # Entry point
├── Employee.java # Abstract base class
├── FullTimeEmployee.java # Full-time implementation
└── PartTimeEmployee.java # Part-time implementation


## Technical Stack
- Core Java
- OOP Principles
- Collections Framework
- Console I/O

## Author
Pratibha Maurya
<br>
pratibhacse20@gmail.com
<br>
https://github.com/Pratibha-Maurya23
