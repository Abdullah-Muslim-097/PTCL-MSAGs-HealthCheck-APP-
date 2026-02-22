# PTCL-MSAGs-HealthCheck-APP-
PTCL Internal PMR &amp; MSAGs Audit Management System is a secure, role-based internal web application prototype designed for PTCL operational teams.  The system enables authorized employees to log in using pre-registered PTCL email addresses, manage assigned PMRs , submit MSAGs health check audits with mandatory image verification

PTCL Internal PMR & MSAGs Audit Management System (Prototype)
🚀 Overview

This project is a prototype internal application developed for PTCL to manage:

PMR (Preventive Maintenance Reports)

MSAGs Health Check Audits

Executive Performance Monitoring

Automated Alerts & Escalations

AI-based Reporting & Analytics

The system is designed strictly for internal use, with role-based access and hierarchical database structure.

⚠️ This project is currently under implementation and developed as a prototype demonstration for PTCL.

🔐 Authentication & Security

Only pre-registered PTCL email addresses can create accounts.

Signup requires:

PTCL registered email

Name

Designation (already stored in database)

OTP verification is sent to official PTCL email.

If email does not exist in database → account cannot be created.

WiFi/Internet required for first login.

📊 Dashboard Features

After login, users can view:

Total PMRs

Completed PMRs

Pending PMRs

Live updated charts

Only PMRs assigned to that specific user

The dashboard reflects real-time data and updates automatically upon form submission.

📝 MSAGs Health Check Module

Users can submit MSAGs audits by:

Clicking MSAGs HealthCheck

Selecting MSAG by:

Name

Address

IP

Filling structured audit form

📷 Image Upload Rules

Uploading Earthing Value image is mandatory

If any field is marked "NO (Alarming)", an optional image upload field dynamically appears

Form submission updates dashboard metrics automatically

🚨 Alerts & Escalation System
Automatic Alerts

If earthing value is low → responsible manager receives continuous alert

If executive misses PMR submission → continuous alert with deadline

If deadline exceeds → escalation notification sent to designated manager

Hierarchical Workflow

Database follows zonal → managerial → executive hierarchy

Deadlines are uploaded only by zonal team (e.g., Sidra Saif)

Alerts flow upward in hierarchy when unresolved

🤖 AI Integration (Planned & In Progress)

AI will be used for:

Performance evaluation of executives based on resolution speed

Identifying high-alert MSAG sites

Root cause analysis of recurring issues

Future implementation:

Detect MSAG cards with high connection load

Predict cards likely to fail

📧 Automated Reporting

Quarterly reports generated

Reports shared via email to all hierarchical levels

AI-assisted evaluation included in reports

📱 Offline Functionality

Similar to WhatsApp offline capability:

Internet required for initial login

Forms can be filled offline

Data stored locally

Automatically synced to server when connection is restored

⚙️ System Architecture (High-Level)

Role-based authentication

Hierarchical database structure

Real-time dashboard updates

Local storage for offline mode

Server sync mechanism

Alert & notification engine

AI analytics layer (under development)

🎯 Key Objectives

Improve operational transparency

Ensure timely PMR submissions

Enable proactive fault management

Reduce downtime in MSAG infrastructure

Digitize internal audit workflow

📌 Current Status

🟡 Under Implementation
🟡 Prototype Version
🟡 Developed for PTCL Demonstration
🔵 AI Module – In Progress

🔮 Future Enhancements

Predictive failure detection

Advanced analytics dashboard

Push notification system

Mobile app deployment

Automated escalation workflow refinement

👤 Author

Developed as a prototype system for PTCL internal operational management.
