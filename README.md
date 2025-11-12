# 👀 Blindcode-Blitz / Smoke Screen 🕶️

<img src="/client/src/media/faviconz.ico.png" alt="Alt Text" width="300" height="200">

A "blind coding" platform developed for an event at NIT Trichy.

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.1.0-brightgreen)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 📌 Description

**Smoke Screen / Blindcode Blitz**, an extraordinary coding platform that takes you out of your coding comfort zone. Step into a world where your coding instincts are put to the ultimate test – you'll write code without seeing it. Engage in a unique challenge that sharpens your problem-solving skills and encourages creative thinking.

It is a competitive platform where participants write code **without seeing the code they type**.  
All typed content remains visually hidden, pushing users to rely on reasoning, memory, and structured thought.

To support progression checks, a **limited Peek System** allows a participant to briefly reveal their hidden code **three times**:
- 1st → **7 seconds**
- 2nd → **5 seconds**
- 3rd → **3 seconds**

Each peek requires a **minimum 1-minute cooldown** before it can be used again.

This system successfully served **200+ active users** during the competition, backed by Spring Boot + React, and AWS deployment.

> This project is designed for an event at National Institute of Technology, Trichy.

> Originally separate client [frontend] + server [backend] repos → now re-uploaded (~2 years later) as a **single merged repository**.

---

## ✨ Features  
- 🔒 **Blind Coding Mode** — Editor shows no code while typing  
- 👁️ **Peek System:** 3 timed reveals → 7s → 5s → 3s (1-min cooldown each)  
- ✅ JWT-based authentication  
- ☁️ AWS deployed (EC2, S3, RDS)  
- 📈 Stable at 200+ concurrent users  
- 🎯 Event-grade performance  

---

## 🏗️ Tech Stack  
| Layer | Technology |
|-------|-----------|
| Frontend | React, TinyMCE, Axios |
| Backend | Java 17, Spring Boot |
| Database | MySQL - (AWS RDS) |
| Cloud | AWS - EC2, S3 |

---

## 📂 Structure  

    │── client/ # React frontend
    │ ├── components/
    │ ├── pages/
    │ ├── services/
    │ └── auth/
    │
    │── src/main/.../ # Spring Boot backend
    │ ├── config/
    │ ├── security/
    │ ├── controller/
    │ ├── entities/
    │ ├── exception/
    │ ├── payload/
    │ ├── services/
    │ └── utilities/
    │
    ├── pom.xml
    ├── LICENSE
    └── README.md

---

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch for your feature/bugfix: `git checkout -b feature-new-feature`
3. Make your changes and commit them: `git commit -m "Add new feature"`
4. Push your changes to your fork: `git push origin feature-new-feature`
5. Open a pull request.

## 📄 License

[This project is licensed under the MIT License.](https://github.com/vishwasio/blindcode-blitz---coding-platform/blob/master/LICENSE)

## 🌐 Contact

[GitHub: /vishwasio](https://github.com/vishwasio)

⭐ If you like this project, please give it a star!
