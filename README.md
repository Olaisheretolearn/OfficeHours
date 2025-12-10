# OfficeHours

## Overview
OfficeHours is a lightweight, account-free queue management tool designed for instructors and teaching assistants.  
It streamlines student help sessions by providing a real-time queue, topic tracking, optional video call workflow, and automatic CSV summaries.

The platform is ideal for classes where many students attend office hours and need a simple, organized way to wait their turn.

---

## Features

### No Account Required
- Instructors do not need to create an account.  
- Students join the queue by entering their name and a short description of what they need help with.

### Live Queue Management
- Instructors see all waiting students in real time.  
- Each entry includes the student’s name and their topic/question.  
- Instructors can admit or remove students with a single click.

### Time Tracking and Session Summary
- The system automatically tracks how long each student spends with the instructor.  
- When the session ends, the instructor can download a CSV file containing:
  - Student names  
  - Time joined  
  - Time admitted  
  - Duration spent with the instructor  
  - Stated help topic  

### Waiting Room Experience
- While students wait, they see a rotating panel of commonly asked questions.  
- This helps answer simple issues immediately and reduces queue time.

### Video Call Support
- Instructors can open a video call room.  
- As students reach the top of the queue, the instructor can admit them directly into the call.  
- This allows the entire workflow—queue, admission, call—to remain in one place.

---

## Tech Stack

**Backend**
- Node.js  
- Express  
- WebSockets (for real-time queue updates)  
- MongoDB or in-memory session store depending on deployment

**Frontend**
- Pug templates or HTML/CSS/JS  
- Lightweight client-side scripts for live updates

**Other**
- CSV export for session history  
- No authentication required

---

## Project Structure

