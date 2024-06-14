# Software Requirements Specification (SRS) Document

## 1. Introduction
### 1.1 Purpose
The purpose of this document is to outline the requirements for the development of an Energy Usage Analysis System. This system will allow users to upload their energy usage data from Central Maine Power (CMP), visualize monthly usage differences, calculate costs, and generate reports for better energy management.

### 1.2 Scope
The Energy Usage Analysis System will provide a web-based platform where users can:
- Authenticate and securely log in to their accounts.
- Upload energy usage data files provided by Central Maine Power (CMP).
- Parse and analyze the uploaded data to visualize monthly usage differences.
- Calculate costs based on the usage data.
- Generate detailed reports summarizing usage patterns and potential cost savings opportunities.

### 1.3 Definitions, Acronyms, and Abbreviations
- **CMP**: Central Maine Power, the utility company providing energy usage data.
- **SRS**: Software Requirements Specification, this document outlining system requirements.

### 1.4 References
- [CMP Official Website](https://www.cmpco.com/)
- [PlantUML Documentation](https://plantuml.com/)

### 1.5 Overview
This SRS document covers functional and non-functional requirements, constraints, and user interface specifications for the Energy Usage Analysis System.

## 2. Overall Description
### 2.1 Product Perspective
The Energy Usage Analysis System is a standalone web application that interacts with users through a web browser. It will integrate with CMP's data files and provide visualizations and reports based on parsed data.

### 2.2 Product Functions
#### 2.2.1 User Management
- **Login**: Users can authenticate using their credentials.
- **Registration**: New users can create accounts.

#### 2.2.2 Data Management
- **Upload Data**: Users can upload CMP-provided usage data files.
- **Parse Data**: System will parse uploaded data to extract relevant information.

#### 2.2.3 Visualization and Analysis
- **Visualize Data**: Display monthly usage differences through charts and graphs.
- **Calculate Costs**: Estimate costs based on energy usage data.

#### 2.2.4 Reporting
- **Generate Reports**: Automatically generate reports summarizing usage patterns and cost breakdowns.

### 2.3 User Classes and Characteristics
- **End Users**: Residential or commercial customers of CMP interested in analyzing their energy usage data.
- **Administrators**: System administrators responsible for user management and system maintenance.

### 2.4 Operating Environment
- **Web Browser Compatibility**: The system shall be compatible with modern web browsers (Chrome, Firefox, Safari).
- **Backend Requirements**: Node.js or Python-based server environment with suitable libraries for file handling and data processing.
- **Database**: MongoDB or PostgreSQL for data storage.

## 3. System Features
### 3.1 Login and Authentication
- Users shall authenticate using username and password.
- Passwords shall be securely stored using encryption techniques.

### 3.2 Data Upload and Parsing
- Users shall upload CMP-provided usage data files in specified formats.
- The system shall parse uploaded data files to extract kWh usage and timestamp information.

### 3.3 Data Visualization
- Monthly usage differences shall be visualized using line charts and bar graphs.
- Users shall be able to select specific time ranges for visualization.

### 3.4 Cost Calculation
- The system shall calculate estimated costs based on uploaded usage data and current energy rates.

### 3.5 Report Generation
- Users shall be able to generate detailed reports summarizing usage patterns and cost breakdowns.
- Reports shall be downloadable in PDF format.

## 4. Non-Functional Requirements
### 4.1 Performance Requirements
- The system shall handle concurrent user sessions without significant degradation in performance.
- Data parsing and visualization processes shall be optimized for efficiency.

### 4.2 Security Requirements
- User data shall be encrypted during transmission and storage.
- Access to sensitive data and administrative functions shall be restricted based on user roles.

### 4.3 Usability Requirements
- The user interface shall be intuitive and user-friendly, requiring minimal training for users to navigate and utilize functionalities.

## 5. Constraints
- The system shall comply with data privacy regulations and CMP's terms of service regarding usage data handling.
- Implementation shall adhere to budgetary constraints and resource availability.

## 6. User Interface Specifications
- The user interface shall feature responsive design principles, ensuring compatibility across various devices and screen sizes.
- Visualizations and reports shall be presented in a clear and accessible format.

## 7. Glossary
- **CMP**: Central Maine Power, the utility company providing energy usage data.
- **SRS**: Software Requirements Specification, this document outlining system requirements.

## Appendix A: Use Case Diagram
![Use Case Diagram](Usecase Diagram/Usecase Diagram.png)
