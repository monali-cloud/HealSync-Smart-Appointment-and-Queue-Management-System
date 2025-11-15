#HealSync – Smart Appointment and  Queue Management System

## Project info 
HealSync is a web-based mini-project focused on real-time queue management in hospitals.
It allows patients to book appointments and instantly receive their queue position, while doctors can update the queue by clicking Next Patient.

##Key Features
*Doctor Dashboard*
View full patient queue
Click Next Patient to call the next one
Queue automatically rearranges
Instant real-time updates to all patient screens

*Patient Dashboard*
Book appointment with name & email
Automatically assigned queue position (1, 2, 3...)
Queue updates live whenever doctor moves the line

*Backend Logic*
Flask handles all API endpoints
MySQL stores doctors & patients
Socket.IO broadcasts updates to all users
Queue positions reorder automatically


##System Workflow

Patient enters name + email → clicks Book Appointment
Backend assigns next available queue number
Patient and doctor screens instantly update in real-time
Doctor clicks Next Patient → backend reorders the queue
All active clients refresh automatically without page reload

