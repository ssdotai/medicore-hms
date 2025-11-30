# 🏥 MediCore HMS

MediCore HMS is a modern healthcare management system built with ASP.NET Core MVC. It streamlines patient, doctor, appointment, medical record, and prescription management, helping healthcare providers improve efficiency, organize clinical workflows, and deliver better patient care.

## Overview

This project is a sample hospital management system that provides:

- Secure login and registration for different user roles
- Admin tools to manage patients and doctors
- Doctor dashboards for viewing appointments and creating medical records
- Patient dashboards for viewing appointments and prescriptions
- Appointment scheduling and tracking
- Medical record and prescription management

## Key Features

### Admin
- Manage doctors and patients
- View all appointments
- Access overall system dashboards and summaries

### Doctor
- View assigned appointments
- Create and edit medical records
- Create prescriptions for patients
- View patient history related to their own cases

### Patient
- Register and sign in
- View personal appointments
- View medical records
- View prescriptions issued by doctors

## Technology Stack

- ASP.NET Core MVC (.NET 8)
- Entity Framework Core
- SQLite database
- ASP.NET Core session-based authentication
- Bootstrap for UI layout

## Project Structure

- Controllers: request handling for account, appointments, doctors, patients, medical records, and prescriptions
- Models: domain entities such as User, Patient, Doctor, Appointment, MedicalRecord, and Prescription
- Data: database context and seed data
- Views: Razor views for each feature area

