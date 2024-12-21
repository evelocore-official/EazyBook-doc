# Roadmap for EasyBook Doc Channel System 
> Powered by evelocore

The application consists of two sides: **Doctor** and **Patient**.

---

## **Doctor Side**

### 🧢 Signup/Login via WhatsApp OTP
- Doctors sign up or log in using a WhatsApp OTP.
- Upon login, they access the dashboard to manage events.
- Doctors can't log in from multiple devices for the security.

### 🧢 Timetable Management
- Doctors can create and manage their weekly timetables.
- The timetable includes days of the week (Mon, Tue, Wed, Thu, Fri, Sat, Sun).
- Multiple events can be scheduled on the same day.
- Each event includes:
  - **Title**
  - **Start/End Time**
  - **Place**
  - **Location on Map**

### 🧢 Dashboard
- Displays all events for the current week.
- Selecting an event allows the doctor to view the next 5 occurrences of that weekday (e.g., the next 5 Mondays).
- The doctor can see all appointments scheduled for each occurrence.
- On a scheduled date, the doctor can start the event, and all patients are notified via WhatsApp.

### 🧢 Event Control Panel
- During an event, the doctor can access a control panel to:
  - Move appointment numbers up or down.
  - Select specific patients directly.
  - Patients can view updates live.

### 🧢 Account Management
- Doctors can update their personal information.

---

## **Patient Side**

### 🍅 Login/Signup
- Patients sign up by entering their phone number (e.g., 07...).
- They receive an OTP for verification and complete their profile.
- Patients can't log in from multiple devices.

### 🍅 Dashboard
- Displays upcoming appointments.
- When an event starts, patients see a **Visit** button to view live event progress.
- Patients can also edit their personal information.

### 🍅 Search for Doctors
- Patients can search for doctors by name.
- View the selected doctor’s timetable and events.
- Book an appointment by selecting a preferred event and clicking the **Channel** button.
- View the next 5 occurrences of the event and choose a date to make an appointment.

### 🍅 Event
- When an event starts, patients can click the **Visit** button to view live progress.
- The live interface displays:
  - **Current Appointment Number**
  - **Your Appointment Number**
  - **Current Patient**
- When a patient's turn comes, a nurse opens the door and announces the appointment number along with the patient’s name.

---
## Incompleated Works

> Payment Method

> Hosting

> Testing

