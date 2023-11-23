<div align="center">
<h1 align="center">
<img src="./img/app_icon_wbg.webp" width="100" />
<br>MyPayCards
</h1>
<h3>◦ MyPayCards: Demo Angular & Asp.Net Core Web API project handling  CRUD Payments Operations.</h3>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/ASP.NET-0467DF.svg?style&logo=.net&logoColor=white" alt="ASP.NET" />
<img src="https://img.shields.io/badge/Angular-E34F26.svg?style&logo=Angular&logoColor=white" alt="Angular" />
<img src="https://img.shields.io/badge/Microsoft_SQL_Server-3178C6.svg?style&logo=microsoft-sql-server&logoColor=white" alt="Microsoft_SQL_Server" />
</p>
<img src="https://img.shields.io/github/languages/top/R3-da/MyPayCards?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/R3-da/MyPayCards?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/R3-da/MyPayCards?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/license/R3-da/ShapeSwipe?style&color=5D6D7E" alt="GitHub license" />
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [⚙️ Features](#-features)
- [📂 Project Structure](#project-structure)
- [🚀 Getting Started](#-getting-started)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---


## 📍 Overview

HTTPStatus Exception: 429

---

## ⚙️ Features

> - `ℹ️  Create Payment Cards`
> - `ℹ️  Read Payment Cards`
> - `ℹ️  Update Payment Cards`
> - `ℹ️  Delete Payment Cards`

---


## 📂 Project Structure

/MyPayCards  
├── /PaymentAPI                 # Server  
└── /PaymentAPP                 # Client

---


## 🚀 Getting Started

### ✔️ Prerequisites

Before you begin, ensure that you have the following prerequisites installed:
> - `ℹ️ Node v20.6.1`
> - `ℹ️ .NET v8.0.100`
> - `ℹ️ Angular v16.1.1`
> - `ℹ️ Microsoft SQL Server v16.0.1`

### 📦 Installation

1. Clone the MyPayCards repository:
```sh
git clone https://github.com/R3-da/MyPayCards
```

2. Change to the project directory:
```sh
cd MyPayCards
```

3. Install server dependencies:
```sh
cd PaymentAPI/PaymentAPI
dotnet restore
```

4. Install dotnet-ef to run db migrations :
```sh
dotnet tool install --global dotnet-ef
```

5. Install client dependencies:
```sh
cd PaymentApp
npm install
```

### 🎮 Using MyPayCards

1. Run db migrations:
```sh
cd PaymentAPI/PaymentAPI
dotnet ef database update
```

2. Start server:
```sh
cd PaymentAPI/PaymentAPI
dotnet run
```

3. Start client:
```sh
cd PaymentApp
ng serve
```
Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### 🧪 Running Tests

1. Server:
```sh
dotnet test
```

2. Client:
```sh
ng test
```

---


## 🗺 Roadmap

> - [X] `ℹ️  Set Up Backend`
> - [X] `ℹ️  Set Up Frontend`
> - [ ] `ℹ️ ...`


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for additional info.

---
