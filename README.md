# 📱 Budget Tracker App

![Android](https://img.shields.io/badge/Platform-Android-green)
![Kotlin](https://img.shields.io/badge/Language-Kotlin-blue)
![RoomDB](https://img.shields.io/badge/Database-Room-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview
The **Budget Tracker App** is an Android mobile application designed to help users efficiently manage their personal finances by tracking income, expenses, and budgeting categories.

The system provides real-time financial insights and uses **Room Database** for secure offline data storage. The application demonstrates strong application of Android development principles, including structured architecture, persistent storage, and interactive UI design.

---

## 🎯 Objectives
- Track daily income and expenses
- Categorize financial transactions
- Provide financial summaries and insights
- Improve budgeting discipline
- Ensure offline-first data persistence

---

## ✨ Key Features

### 💰 Expense Management
- Add, view, and delete expenses
- Store amount, category, date, and description
- Real-time updates on dashboard totals

### 📊 Category System
- Predefined and custom categories
- Category-based filtering
- Spending breakdown per category

### 🏠 Dashboard Overview
- Total income vs expenses
- Remaining balance calculation
- Quick financial summary

### 💾 Room Database Integration
- Local persistent storage
- Efficient CRUD operations
- Offline functionality

### 🔐 Authentication System
- Simple login using SharedPreferences
- User session persistence

---

## 📊 Advanced Features (Distinction Enhancement)
- Monthly expense summaries
- Category-based spending analysis
- Basic financial insights dashboard
- Data aggregation for reporting

---

## 🧠 System Architecture

The application follows a **layered architecture approach inspired by MVVM principles**:

- **UI Layer** → Activities & Adapters (User interaction)
- **Data Layer** → Room Database (Entities + DAO)
- **Repository Layer** → Mediates between UI and database
- **ViewModel Layer (if implemented)** → Manages UI-related data lifecycle

This structure improves maintainability, scalability, and separation of concerns.

---

## 🧱 Technologies Used

- Android Studio
- Kotlin / Java
- Room Database (SQLite abstraction)
- SharedPreferences
- RecyclerView
- Material Design Components
- XML Layout Design

---

## 📂 Project Structure
