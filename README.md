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
