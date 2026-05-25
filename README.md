# SmartMaintenanceHub

## Overview

SmartMaintenanceHub is a maintenance management application built in **OutSystems ODC** to supoort equipment monitoring, maintenance planning and work order execution.

This project was developed as a portfolio application to demonstrate not only end-to-end app creation in OutSystems but also integration capabilities, such as external database connectivity, API exposure and API consumption.

---

## What this project demonstrates:

This application showcases my ability to:
- Develop a complete business application in **OutSystems ODC**
- Creation, configuration and integration to an **external AWS SQL database**
- Integration and usage of **MySQL Workbench** as data viewer / editor
- Automation with **Timers** 
- Consume external APIs
- Expose custom APIs for external usage
- Test API endpoints with **Postman**
- Model role-based business flows
- Design operational dashboards and monitoring screens

---

## Main business flow

The app follows a manager-driven maintenance process:
1. The **Maintenance Manager** registers equipment
2. The **Maintenance Manager** creates maintenance records
3. During maintenance creation, the manager assigns a technician and defines work order priority
4. The app automatically creates the related work order
5. The **Technician** executes assigned work orders through a dedicated execution screen

This design separates planning from execution and creates a clearer ownership model.

---

## Main features:

- Equipment registry
- Maintenance creation and tracking
- Automatic work order generation
- Technician assignment
- Technician execution flow
- Work order status progression
- Sensor-based alert monitoring
- Integration monitoring screen
- Internal user administration

---

## Integrations:

### External database:
The app uses an **external AWS MySQL database** as part of the solution architecture, demonstrating integration with data outside the default application database context.

### Exposed API
The application exposes custom API endpoints, including:

- `GET`
- `POST`

These endpoints were successfully tested in **Postman**.

### Consumed API
The application also consumes an external API, including a **random number generator API**, used to support simulation scenarios within the app.

---

## Technical highlights

- Built in **OutSystems ODC**
- Connected to an **AWS external database**
- API consumption and API exposure
- Postman validation for endpoint testing
- Timer automation
- Role-based access and separation of responsibilities
- Business-oriented maintenance flow modeling

---

## Roles

- **Administrator**
  - full administrative access

- **Maintenance Manager**
  - registers equipment
  - creates maintenance
  - assigns technicians
  - defines work order priority
  - owns work order creation flow

- **Technician**
  - accesses assigned work orders
  - starts and completes execution

- **Viewer**
  - read-only operational visibility

---

## Main screens

- `Homepage`
- `Equipment_List`
- `Equipment_Form`
- `Maintenance_List`
- `Maintenance_Form`
- `WorkOrder_List`
- `WorkOrder_Form`
- `My_WorkOrders`
- `Integration_Monitor`
- `Users_List`
- `User_Form`

---

## API testing

The application APIs were tested externally using **Postman**, validating successful request and response behavior for exposed endpoints.

## Screenshots

### Dashboard
<img width="1300" height="909" alt="image" src="https://github.com/user-attachments/assets/37e47ab4-616e-4acf-b9cb-7bb67a2eea2c" />

### Maintenance creation
<img width="1002" height="622" alt="image" src="https://github.com/user-attachments/assets/8361cf93-570e-411e-a6e7-a28bb0e6e31f" />

### Integration Monitor
<img width="815" height="856" alt="image" src="https://github.com/user-attachments/assets/e1059070-76b4-4d9f-bd09-218495784af2" />

### API testing
<img width="1261" height="700" alt="image" src="https://github.com/user-attachments/assets/58d1fefc-a1ec-4a0a-9ffc-192e2adc15ed" />

### External DB SQL AWS using SQL Workbench
<img width="437" height="663" alt="image" src="https://github.com/user-attachments/assets/32aeaacc-67ea-4c3a-8492-3ffec7ed9576" />

### Timers and automation 
<img width="1364" height="636" alt="image" src="https://github.com/user-attachments/assets/a11a13e6-bf49-49a5-bcaa-b48e0e65ea83" />
---

## Portfolio goal

This project was built as a portfolio case to demonstrate practical development skills in **OutSystems ODC**, including application design, integration architecture, business flow modeling, and API-based communication.
