# Steamliner Documentation

---

## **Project Overview**
Steamliner is a modern solution to unify game libraries from multiple platforms into a single, easy-to-use application. It eliminates the need for users to open separate launchers for platforms like Steam, Epic Games, and GOG, providing a streamlined experience for managing and launching games. The project also includes a website to introduce the launcher, manage user accounts, and offer support.

---

## **Purpose**
This project was born out of the frustration of gamers having to juggle multiple launchers to access their game libraries. The goal is to simplify this experience by integrating these libraries into one central hub, saving time and improving usability. Steamliner aims to:

- Enhance convenience for gamers.
- Provide a unified interface for managing games.
- Allow customization and scalability for future expansions.

---

## **Technology Stack**
### **Frontend (Website)**
- **Framework**: React.js
- **Purpose**: To provide a user-friendly interface for account management, support, and feature showcases.

### **App Framework (Launcher)**
- **Framework**: Tauri
- **Purpose**: To create a lightweight desktop application for managing and launching games.

### **Backend**
- **Language**: Node.js
- **Purpose**: Handles API connections, manages authentication (OAuth), and facilitates communication between the frontend, the launcher, and third-party game libraries.

### **Database**
- **Database**: MongoDB
- **Purpose**: Stores user data, game library details, and account integration settings.

---

## **How It Works**
1. **User Account Creation**:
   - Users create an account through the website or launcher.
   - OAuth is used to connect third-party game libraries (e.g., Steam, Epic Games).

2. **Game Library Aggregation**:
   - The launcher uses APIs from game platforms to fetch user game libraries.
   - Games are displayed in a unified library within the launcher.

3. **Game Launching**:
   - Users select a game from the unified library.
   - The launcher communicates with the respective platform to initiate the game.

4. **Website Features**:
   - Account management, including linking/unlinking platforms.
   - FAQ, support, and feature showcase.

---

## **Why This Project Was Created**
The gaming industry is fragmented, with numerous platforms offering exclusive games and requiring their own launchers. This fragmentation creates inconvenience for users, leading to wasted time and effort switching between platforms. Steamliner was created to solve this problem by:

- Combining all game libraries into one interface.
- Reducing the overhead of managing multiple accounts and platforms.
- Focusing on user experience and convenience for gamers worldwide.

---

## **Future Features**
- Support for more game platforms.
- Cloud saves and synchronization.
- Community features like sharing game libraries and achievements.
- Mobile app integration for remote management.
