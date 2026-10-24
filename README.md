# Rawa - Water Delivery Management System💧 | نظام رواء لإدارة توصيل المياه

> **Rawa** is an integrated smart digital platform (Cross-Platform Mobile Application & Web Administration Dashboards) engineered to solve household water tank delivery challenges in Mukalla City[cite: 17, 21]. The platform bridges the communication gap between end-users, delivery drivers, and regional water supply companies through automated order assignment, real-time geolocation tracking, and structured digital invoicing[cite: 21, 28].

---

## Executive Summary | ملخص المشروع

- **Domain:** Smart Logistics, Fleet Management & Public Service Transformation
- **Role:** Front-End Developer & UI/UX Designer
- **Target Location:** Mukalla, Hadhramout, Yemen[cite: 17]
- **Academic Institution:** Hadhramout University - College of Computers & Information Technology (2026)[cite: 1]

---

## Architectural & Technology Stack | التقنيات المستخدمة

- **Mobile Application (Client & Driver):** Flutter & Dart (Cross-Platform iOS/Android)[cite: 23]
- **Web Administration Dashboards:** Angular & TypeScript
- **UI/UX Design & Prototyping:** Figma[cite: 23]
- **Backend Architecture:** C# ASP.NET Core (RESTful APIs)[cite: 23]
- **Database & Cloud Management:** PostgreSQL & Supabase Services[cite: 23]

---

## 1. Super Admin Dashboard | إدارة النظام العامة

<img width="661" height="350" alt="سوبر1" src="https://github.com/user-attachments/assets/ff54fc42-48be-4a81-b62d-d5bb85cae65f" />

The Super Admin module serves as the central governing panel for managing overall platform operations, vendor onboarding, and global communications[cite: 7, 10, 13].

### 1.1 Authentication & Portal Entry
- **Login Interface:** Secure access portal requiring verified administrative credentials to maintain database integrity[cite: 8].

<img width="661" height="350" alt="سوبر1" src="https://github.com/user-attachments/assets/58638f36-01bc-4526-ad75-344acc9f6de8" />

### 1.2 Platform Analytics Overview
- **System Dashboard:** Visual representation of key metrics including total companies registered, active drivers, total fulfilled orders, and month-over-month vendor growth charts[cite: 9].

<img width="648" height="347" alt="سوبر2" src="https://github.com/user-attachments/assets/61810b3f-7b0b-4c9b-9644-f31a26693568" />

### 1.3 Supplier & Operations Management
- **Company Onboarding & Verification:** Modules to register new water suppliers, manage contact parameters, monitor operational status, and assign geographic coverage zones[cite: 10, 11, 12].
- **System-Wide Broadcast Notifications:** Capability to send bulk alerts, system update logs, or maintenance warnings across the platform[cite: 13, 14].
- **Central Complaint Resolution:** Ticket tracking mechanism to process reported issues from water companies or end-users[cite: 15].

<img width="632" height="349" alt="سوبر3" src="https://github.com/user-attachments/assets/a7ae868a-d742-4612-a7ce-c674117ca85c" />

---

## 2. Water Company Dashboard | لوحة تحكم شركة المياه

Designed for local water delivery companies to oversee fleet movement, manage incoming customer requests, and track financial performance[cite: 17, 18, 19, 20].

### 2.1 Dispatch & Order Workflow
- **Live Fleet Tracking:** Interactive mapping interface displaying active delivery trucks across Mukalla districts[cite: 18].
- **Order Status Processing:** Multi-tab monitoring system categorizing requests into Pending, Automated, In Progress, and Completed orders[cite: 19].

<img width="362" height="220" alt="سب1" src="https://github.com/user-attachments/assets/789929c3-298a-4755-97f9-b2e67e68be66" />

### 2.2 Driver & Customer Oversight
- **Driver Performance & Rostering:** Tools to register drivers, track completed deliveries, assign vehicle license numbers, and view driver rating metrics[cite: 20].
- **Customer Registry & Ratings:** Complete directory of registered clients, order history logs, and customer service ratings[cite: 21, 22].
- **Technical Support Ticketing:** Dedicated channel for branch managers to log operational bugs or request system assistance[cite: 26].

<img width="499" height="320" alt="سب2" src="https://github.com/user-attachments/assets/3a75db3d-cf7d-44a2-960b-9011e2134a45" />
<img width="511" height="325" alt="سب3" src="https://github.com/user-attachments/assets/895b945b-b919-4352-b934-124f7016a744" />

---

## 3. Customer Mobile Application | تطبيق العملاء

A user-friendly mobile experience allowing residents to discover local water providers, request custom water volumes, and monitor delivery progress[cite: 27, 28, 30].

### 3.1 Onboarding & Vendor Selection
- **Interactive Geolocation:** GPS-based location detection allowing users to set exact tank location pinpoints or enter manual address fallbacks[cite: 28, 29, 35].

<img width="594" height="206" alt="كستمر1" src="https://github.com/user-attachments/assets/768e76ef-3dc7-4112-bb09-47e3cc1b8d2a" />

- **Supplier Directory & Ratings:** Browse nearby water vendors, compare price per volume (e.g., 700L tank option or full refill), and read community ratings[cite: 30, 33].

<img width="405" height="341" alt="كستمر2" src="https://github.com/user-attachments/assets/66829f7f-0683-44c3-a524-c5d5d8eca8d1" />

### 3.2 Ordering, Payment & Live Tracking
- **Order Customization & Flexible Payments:** Select specific water volume needs, with options to pay Cash on Delivery or via local electronic transfers (e.g., Kuraimi Bank)[cite: 33].
- **Real-Time Delivery Lifecycle Tracking:** Live tracking screen displaying 7-stage order status (Pending ➔ Driver Accepted ➔ In Transit ➔ Arrived ➔ Refilling ➔ Payment ➔ Delivered)[cite: 34].
- **Digital PDF Invoicing:** Auto-generated digital bills stating order ID, volume, total cost, timestamp, and vendor contact info[cite: 34].

<img width="187" height="350" alt="كستمر3" src="https://github.com/user-attachments/assets/577b2d70-0a71-4f68-b3a7-41658774e1ad" />
<img width="282" height="394" alt="كستمر5" src="https://github.com/user-attachments/assets/7c7c3def-1d74-4b46-8db8-ec0d4d7b1d89" />
<img width="151" height="408" alt="كستمر4" src="https://github.com/user-attachments/assets/e1151efc-43d7-4ac4-95c2-72648e07d588" />

---

## 4. Driver Mobile Application | تطبيق السائقين

An operational tool tailored for delivery drivers to manage daily work shifts, receive automated dispatch alerts, and navigate to client addresses[cite: 28, 37, 39, 40].

### 4.1 Shift & Dispatch Management
- **Work Shift Toggle:** Online/Offline toggle system enabling drivers to control their availability for receiving automated delivery orders[cite: 39].
- **Interactive Dispatch Alerts:** Instant pop-up notifications displaying new delivery requests with a 2-minute decision window[cite: 39, 40].

<img width="448" height="380" alt="درايفر1" src="https://github.com/user-attachments/assets/384d835e-ef57-4a89-a20e-8f50a75bcf77" />

### 4.2 Navigation & Payment Settlement
- **Order Details & Route Mapping:** Displays customer name, phone number, required water volume, and precise map navigation coordinates[cite: 40, 41].
- **Cash Collection & Settlement:** Interface to confirm cash received from the client, complete the transaction, and generate immediate digital receipt confirmations[cite: 41].

<img width="634" height="358" alt="درايفر2" src="https://github.com/user-attachments/assets/4be1b82c-53cf-4ecb-ad83-59985032d7f1" />
<img width="668" height="381" alt="درايفر3" src="https://github.com/user-attachments/assets/65667e7f-8c83-4b90-90e2-2e6582911a3b" />

---

## Academic & Team Information

- **Project Type:** Undergraduate Graduation Project (2026)[cite: 1]
- **Supervised By:** Dr. Samera Obaid Barraood[cite: 1]
- **Developed By:** Information Technology Department Team, Hadhramout University[cite: 1]
