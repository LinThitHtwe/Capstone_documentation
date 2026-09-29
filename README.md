# Smart Library Table Reservation & IoT Monitoring

This project is an INTI Capstone that combines a web-based library table reservation system with IoT monitoring. Students, lecturers, and visitors can view a virtual floor map, reserve tables in time slots, and check in with OTP. Weight sensors and LCD displays track occupancy and show table or entrance status. Admins manage users, table layouts, reservations, weight sensors, and LCD devices from a dedicated console.

## Members

| ![LinThitHtwe](https://github.com/LinThitHtwe.png) | ![Yuka](https://github.com/Yuka2608.png)
|:---:|:---:|
| [LinThit](https://github.com/LinThitHtwe)  | [Yuka](https://github.com/Yuka2608)  |

## Table of Contents

- [Hardware](#hardware)
  - [IoT Top View](#iot-top-view)
  - [IoT Side View 1](#iot-side-view-1)
  - [IoT Side View 2](#iot-side-view-2)
- [User](#user)
  - [Home](#home)
  - [Homepage Seats](#homepage-seats)
  - [Homepage Seats Floor 2](#homepage-seats-floor-2)
  - [Sign In](#sign-in)
  - [Create Account](#create-account)
  - [Dashboard Home](#dashboard-home)
  - [Dashboard Home Seats](#dashboard-home-seats)
  - [Reserve Table](#reserve-table)
  - [Reserve Table Confirmation](#reserve-table-confirmation)
  - [My Reservation History](#my-reservation-history)
- [Admin](#admin)
  - [Admin Home](#admin-home)
  - [Admin Table Map](#admin-table-map)
  - [Admin Table Map Detail](#admin-table-map-detail)
  - [Admin Table Map Floor 2](#admin-table-map-floor-2)
  - [Admin Students](#admin-students)
  - [Admin Lecturers](#admin-lecturers)
  - [Admin Visitors](#admin-visitors)
  - [Admin Reservation History](#admin-reservation-history)
  - [Admin Reservation History Detail](#admin-reservation-history-detail)
  - [Admin Weight Sensors](#admin-weight-sensors)
  - [Admin Add Weight Sensor](#admin-add-weight-sensor)
  - [Admin LCD Displays](#admin-lcd-displays)
  - [Admin Add LCD Display](#admin-add-lcd-display)

## Hardware

### IoT Top View
![IoT Top View](docs/images/iot-top-view.jpg)

Top-down view of the smart table hardware setup, showing how the sensor and display components sit on the table unit.

### IoT Side View 1
![IoT Side View 1](docs/images/iot-sideview-1.jpg)

Side view of the IoT table unit, highlighting the physical mounting of weight sensing and related electronics.

### IoT Side View 2
![IoT Side View 2](docs/images/iot-sideview-2.jpg)

Alternate side angle of the IoT hardware, showing how the LCD and sensor assembly attach to the table for occupancy monitoring.

## User

### Home
![Home](docs/images/home.png)

Landing page for the library reservation system. Visitors can see the overall product entry point before signing in or browsing seat availability.

### Homepage Seats
![Homepage Seats](docs/images/homepage-seats.png)

Public seat map view for a library floor. Users can inspect table layout and availability without needing an admin account.

### Homepage Seats Floor 2
![Homepage Seats Floor 2](docs/images/homepage-seats-floor2.png)

Seat map for floor 2, letting users switch floors and check which tables are free or occupied on that level.

### Sign In
![Sign In](docs/images/signin.png)

Sign-in screen for existing students, lecturers, visitors, or admins. Successful login routes each role to the correct area of the app.

### Create Account
![Create Account](docs/images/create-account.png)

Registration form for creating a new library user account with the allowed public roles before booking tables.

### Dashboard Home
![Dashboard Home](docs/images/dashboard-home.png)

Signed-in user dashboard home. From here, library users can reach seat maps, booking flows, and their own reservation tools.

### Dashboard Home Seats
![Dashboard Home Seats](docs/images/dashboard-home-seats.png)

Authenticated seat overview inside the user dashboard, showing live table status for planning a reservation.

### Reserve Table
![Reserve Table](docs/images/user-reserve-table.png)

Reservation form where a user picks a table, date, and time slot within library hours to book a seat.

### Reserve Table Confirmation
![Reserve Table Confirmation](docs/images/reserve-table-confirmation.png)

Confirmation step after submitting a booking. The system records the reservation and prepares OTP / email details for check-in.

### My Reservation History
![My Reservation History](docs/images/user-my-reservtion-history.png)

Personal reservation history for the signed-in user, listing past and upcoming bookings for that account only.

## Admin

### Admin Home
![Admin Home](docs/images/admin-home-2.png)

Admin console home / overview. Librarians use this as the entry point to manage maps, users, reservations, and IoT devices.

### Admin Table Map
![Admin Table Map](docs/images/admin-tablemap.png)

Admin virtual table map for arranging and reviewing library tables, floors, and layout positions.

### Admin Table Map Detail
![Admin Table Map Detail](docs/images/admin-table-map-2.png)

Detailed admin table-map view for inspecting or editing table placement and availability on the floor plan.

### Admin Table Map Floor 2
![Admin Table Map Floor 2](docs/images/admin-tablemap-floor2.png)

Admin map for floor 2, used to manage table layout and status on the second library level.

### Admin Students
![Admin Students](docs/images/admin-students.png)

Directory of student accounts. Admins can review and manage students who reserve library tables.

### Admin Lecturers
![Admin Lecturers](docs/images/admin-lecturers.png)

Directory of lecturer accounts for managing staff users who can book tables in the system.

### Admin Visitors
![Admin Visitors](docs/images/admin-vistors.png)

Directory of visitor accounts, covering non-student / non-lecturer users who use the reservation system.

### Admin Reservation History
![Admin Reservation History](docs/images/admin-reservation-history.png)

System-wide reservation history for librarians to monitor bookings across all users and tables.

### Admin Reservation History Detail
![Admin Reservation History Detail](docs/images/admin-reservation-history-2.png)

Expanded reservation history view for reviewing booking details, status, and oversight information.

### Admin Weight Sensors
![Admin Weight Sensors](docs/images/admin-weight-sensors.png)

List of registered weight sensors used to detect table occupancy and feed live status into the system.

### Admin Add Weight Sensor
![Admin Add Weight Sensor](docs/images/admin-add-weight-sensor.png)

Form to register or configure a new weight sensor and link it to the IoT occupancy workflow.

### Admin LCD Displays
![Admin LCD Displays](docs/images/admin-lcd-displays.png)

List of LCD displays (entrance and per-table) that show availability, status, or countdown information.

### Admin Add LCD Display
![Admin Add LCD Display](docs/images/admin-lcd-display-add.png)

Form to add or configure an LCD display and associate it with a table or entrance display role.
