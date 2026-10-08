# Health360 – Appointment & Prescription Management System

Health360 is a Salesforce-based healthcare management application designed to manage patients, doctors, appointments, prescriptions, and appointment-related automation in a centralized CRM environment.

The project demonstrates practical Salesforce Administration concepts including data modeling, custom objects, relationships, validation rules, formula fields, Flow automation, security, reports, and dashboards.

---

## 📌 Project Overview

Healthcare organizations need an efficient way to manage patient information, doctor information, appointments, and prescriptions.

Health360 provides a centralized Salesforce application that helps healthcare staff:

- Manage patient records
- Manage doctor records
- Schedule and track appointments
- Manage prescriptions
- Automate appointment-related processes
- Identify missed appointments
- Maintain data accuracy
- Control user access
- Monitor healthcare operations through reports and dashboards

---

## 🎯 Objectives

The main objectives of the Health360 project are:

1. Centralize patient and doctor information.
2. Manage appointments efficiently.
3. Maintain prescription records.
4. Automate appointment-related processes.
5. Identify and handle missed appointments.
6. Maintain data quality using validation rules.
7. Implement Salesforce security controls.
8. Provide reports and dashboards for operational monitoring.

---

## 🏗️ System Architecture

``
                         HEALTH360
                             |
             +---------------+---------------+
             |               |               |
             v               v               v
         Patients         Doctors       Appointments
                                             |
                                             v
                                      Prescriptions
                                             |
                                             v
                                     Flow Automation
                                             |
                          +------------------+------------------+
                          |                  |                  |
                    Notifications     Status Updates       Missed Appointment
                                                               Handling
                          v                  v                  v
                    Notifications     Status Updates     Missed Appointment
                                                               Handling
