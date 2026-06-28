# Remote Health Care System

The **Remote Health Care System** is a comprehensive, full-stack application designed to revolutionize the telemedicine experience. It bridges the gap between patients and healthcare providers by offering an integrated, secure, and user-friendly platform for remote medical consultations and management.

This platform empowers patients to seamlessly book appointments, access medical records, and consult with doctors via high-quality video links. Simultaneously, it provides doctors and administrators with robust tools for managing patient data, prescribing medications, and overseeing hospital operations. Innovative features such as real-time ambulance tracking, an AI-powered 24/7 help bot, and multi-language support ensure that critical healthcare services are accessible, efficient, and inclusive for all users.

## Features & Modules (Tasks TODO)

This project is divided into several key modules, with specific team members responsible for each:

- **Login & Registration** (Narendra): Secure authentication system with role-based access control (Admin, Doctor, Patient, etc.), JWT-based session management, and password recovery.
- **Patient Management** (Bhavya): Comprehensive profiles for patients, tracking personal details, health metrics, historical data, and seamless onboarding workflows.
- **Doctor Management** (Bhavya): Portals for healthcare providers to manage their profiles, specializations, availability schedules, and consult history.
- **Appointment Booking** (Narendra): A robust scheduling system allowing patients to find available doctors, book, reschedule, or cancel appointments with automated email/SMS reminders.
- **Video Consultation** (Nanda): Integrated WebRTC-based high-quality video and audio calling for secure remote telemedicine sessions directly within the browser.
- **24/7 Help Bot** (Vishnu): An AI-powered conversational agent that assists patients with general health inquiries, platform navigation, and automated preliminary triage.
- **Ambulance Tracking** (Sravanthi): Real-time GPS tracking for emergency services, locating nearby hospitals via geographic APIs, and coordinating rapid emergency responses.
- **Medical Records** (Harsha): A secure, centralized repository for storing and retrieving patient prescriptions, consultation notes, lab reports, and overall treatment progress.
- **Admin Dashboard** (Harsha): A centralized control panel for hospital administrators to oversee system activities, manage users, and monitor overall hospital operations.
- **Reports & Analytics** (Nanda): Data visualization and exportable reports covering hospital performance, financial metrics (invoices), and system usage trends.
- **Multi-language Support** (Sravanthi): Comprehensive localization and internationalization (i18n) to ensure the platform is accessible and user-friendly for diverse linguistic backgrounds.

## Project Structure
- `frontend/`: Contains the frontend application code.
- `swecha/`: Contains the backend Spring Boot application code.
