# PetCare App

PetCare is a mobile application built using **React Native with Expo** for the frontend and **Spring Boot with Maven** for the backend. The app provides features such as pet management, an adoption center, missing pet alerts, and pet care articles.
---

## Features

- User registration and authentication
- Manage pet profiles
- Missing pet alerts
- Adoption center
- Search and browse pet care articles
- Bluetooth communication integration (if applicable)
- Real-time updates and notifications

---

## Prerequisites

Ensure you have the following installed before setting up the project:

### General:
- **Git**: [Download](https://git-scm.com/downloads)
- **Node.js (LTS version)**: [Download](https://nodejs.org/)
- **Java 17 or later**: [Download](https://adoptopenjdk.net/)
- **Maven**: [Download](https://maven.apache.org/download.cgi)
- **Expo CLI**: `npm install -g expo-cli`
---

## Setup

### Frontend Setup (React Native with Expo)

1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-repo/petcare.git
   cd frontend
   
2. **Install dependencies**
 ```sh
   npm install
```

3. ** Start the Expo development server:**
```sh
  npx expo start
```

 ### Backend Setup (Spring Boot with Maven)
1. **Navigate to the backend directory:**:
   ```sh   
   cd backend
   
2. **Build and run the backend:**
 ```sh
   mvn clean install
```
Then, open VS Code, locate the PetCareApplication.java file, and click Run Java.

