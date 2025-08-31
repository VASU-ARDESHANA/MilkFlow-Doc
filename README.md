# MilkFlow - Dairy Management & Billing App

MilkFlow is a native Android application built with Kotlin, designed to help local dairy farmers and milk suppliers digitize and manage their daily business operations. It provides a simple interface to manage customers, track daily milk sales, and automatically generate and share monthly bills, all powered by an Appwrite backend.

## Features

#### User Authentication & Profile
* **Secure Onboarding:** Simple and secure login for suppliers.
* **Business Profile:** Manage your dairy's name, contact details, address, and UPI ID for easy payments.

#### Dashboard
* **At-a-Glance View:** A central hub with quick access to all major functions like Customer Management, Daily Sales, Monthly Bills, and Product Settings.

#### Customer Management
* **Add & Edit Customers:** Easily add new customers with details like name, number, address, and delivery preferences.
* **Customer List:** View all your customers in a clean list with search functionality.
* **Vacation Mode:** Temporarily pause deliveries for a customer without removing them from your list.

#### Product & Sales Management
* **Product Pricing:** Set and update prices per liter for different types of milk (e.g., Cow Milk, Buffalo Milk).
* **Daily Sales Entry:** A dedicated screen to log morning and evening milk quantities for all customers on a specific date. The app automatically calculates the daily cost.

#### Billing & Payments
* **Automated Monthly Bills:** Generate detailed, itemized monthly bills for each customer with a single tap.
* **Bill Summary:** Bills include a day-by-day breakdown of milk supplied, total quantity, rate, and the final amount.
* **Payment Tracking:** Log payments received from customers and keep track of pending balances.
* **Share Bills:** Instantly share the generated bill as an image with customers via WhatsApp or any other sharing app.

#### Multi-Language Support
* **Localization:** The app is fully functional in both **English** and **Gujarati (ગુજરાતી)**, allowing users to choose their preferred language.

## Technology Stack

* **Frontend:** Android Native (Kotlin)
* **Backend-as-a-Service (BaaS):** [Appwrite](https://appwrite.io/) – Used for database, authentication, and other backend services.
* **UI Toolkit:** Jetpack Compose – For building a modern, declarative UI.
* **Asynchronous Programming:** Coroutines – For managing background threads and ensuring a smooth, non-blocking user experience.
* **Architecture:** MVVM (Model-View-ViewModel) + Clean Architecture – To create a scalable, maintainable, and testable codebase.
* **UI Design:** Material Design 3 – For a consistent and intuitive user interface.

## Screenshots

| Login | Home Dashboard | Add Customer |
| :---: |:---:|:---:|
| ![1](https://github.com/user-attachments/assets/c135ae27-88ca-4d76-b508-df0ebcaeddb9) | ![2](https://github.com/user-attachments/assets/8f591d94-55ac-4519-a545-40323b23ad0d) | ![3](https://github.com/user-attachments/assets/69e64aad-e57f-415b-91fd-079cfc37ca56) |
| **Customer List** | **Daily Sales Entry** | **Monthly Bill List** |
| ![4](https://github.com/user-attachments/assets/0a220b54-46c6-46b3-a7e7-b08d8fd7a63d) | ![5](https://github.com/user-attachments/assets/e5030e9a-bf60-4d40-8b74-4975015ca7d4) | ![6](https://github.com/user-attachments/assets/42828959-79bb-485b-888f-1d97d2527298) |
| **Generated Bill Details** | **Share Bill Options** | **Update Profile** |
| ![7](https://github.com/user-attachments/assets/ec46cd68-d5da-4735-8dd0-7aa977218c3a) | ![8](https://github.com/user-attachments/assets/951826f9-7943-447f-a338-a3661602d9c6) | ![9](https://github.com/user-attachments/assets/65f3de28-c0da-4a0c-8579-212de2610b00) |
| **Gujarati Language UI** | **Update Products** | **App Update Screen** |
| ![10](https://github.com/user-attachments/assets/cca37169-cb80-45d7-a42f-96efb582eb79) |![11](https://github.com/user-attachments/assets/910c79b7-0524-4b34-a8b5-c80fc8f5c326) | ![12](https://github.com/user-attachments/assets/1a3de54e-6eb8-4c57-a613-09bccd3d718c) |
| **Reminders** | **Custom drawer in Gujarati**| **Make Payments** |
| ![13](https://github.com/user-attachments/assets/a5d488bc-9424-4bee-a2fa-e232be0a051a) | ![14](https://github.com/user-attachments/assets/d9c3a5c1-87ed-49ae-a390-5b624e09e2d1) | ![15](https://github.com/user-attachments/assets/e1823c95-413a-481a-8797-2447ed3a8d5f)
