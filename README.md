# Employee Onboarding Integration

## 1. Business Requirement
The business requirement is that Whenever a new employee is created in the HR system, the employee details must be sent to SAP S/4HANA automatically.
## 2. Source System
HR System
## 3. Target System
SAP S/4 HANA System
## 4. Integration Protocol
HTTPS/REST
## 5. Input Format
JSON
## 6. Output Format
XML
## 7. High-Level Integration Flow
HR System
   ↓
HTTPS
   ↓
SAP CPI
   ↓
Transformation
   ↓
SAP S/4HANA
