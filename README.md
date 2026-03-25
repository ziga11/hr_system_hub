# Modular HR Operating System | Project Hub

This repository serves as the central documentation and architecture hub for a distributed ERP ecosystem. The system is split into specialized services to optimize performance across Web, Mobile, and Administrative interfaces.

## 🛰️ System Architecture
![System Architecture Diagram](/assets/system_structure.svg)

## 📦 Repository Index

### 1. [Mobile Backend (Golang)](https://github.com/ziga11/diploma-mobile-backend)
* **Role:** High-concurrency API for the Flutter client and Slack webhook management.
* **Key Tech:** Go, SHA-256, bcrypt, Google Drive, Slack integration.

### 2. [Mobile Client (Flutter & Dart)](https://github.com/ziga11/diploma-mobileapp)
* **Role:** Native Android/iOS application for candidate onboarding.
* **Key Tech:** Dart, ValueListeneable state management, App-Links.

### 3. [System of Project Tables](https://github.com/ziga11/diploma-boards)
* **Role:** The "Monday.com" clone dashboard for internal HR management.
* **Key Tech:** Vite, TypeScript, Bootstrap, Supabase.

### 4. [Project Form Frontend (TypeScipt & Vite)](https://github.com/ziga11/proj-obrazec-backend)
* **Role:** Decoupled service for dynamic document generation.
* **Key Tech:** Bootstrap, Dynamic forms.

### 5. [Project Form Backend (TypeScript)](https://github.com/ziga11/proj-obrazec)
* **Role:** Decoupled service for dynamic document generation.
* **Key Tech:** Node.js, Express, TypeScript, Google Drive.
