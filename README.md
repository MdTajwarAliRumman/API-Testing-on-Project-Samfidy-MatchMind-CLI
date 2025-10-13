# Api-Testing-on-Project-Samfidy(MatchMind)-with-Newman-Report

<h1 align="center">🧪 API Automation Reports</h1>
<p align="center">
  <b>Postman + Newman + HTML Extra Reporter</b><br/>
  <i>Automated API test results with clear insights</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Postman-API-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Newman-Automation-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" />
</p>

---

## 📌 Project Summary

The primary objective of the Match Mind project is to design and develop a comprehensive mobile application that provides users with an interactive platform to track, analyze, and engage with football matches in real time. The app aims to deliver a seamless experience by combining essential features such as live match updates, detailed statistics, team lineups, news feeds, and AI-powered chat assistance. Additionally, it focuses on enhancing user engagement through personalized profiles, favourite team and player selections, and league-specific insights. Overall, the goal is to create an all-in-one digital companion for football enthusiasts, offering both information and interactivity within a clean, user-friendly interface.

The main goals of this project are given below:

⚽ Track Matches — View match details for today, tomorrow, or yesterday

🌟 Add Favourites — Save your favourite teams and leagues

📊 Match Insights — Get live updates on player positions and in-game events

📰 Football News — Stay updated with the latest football updates and stories 

---
## 🖼️ Screenshot of the Mobile App
<details>
  <summary>Click to view Screenshots</summary>
  
<img width="1291" height="705" alt="Image" src="https://github.com/user-attachments/assets/9a0a3d12-0026-48b8-8a62-0f41aa37f963" />
<img width="1010" height="786" alt="Image" src="https://github.com/user-attachments/assets/67d76f7f-82ff-4015-a1ad-cd4940704eda" />
<img width="1382" height="716" alt="Image" src="https://github.com/user-attachments/assets/98197a47-b2ff-456b-9c77-eaf02ff0306f" />

</details>

---
## 📊 API Test Summary
Some demo API endpoints and test status are given below:

| Endpoint             | Method | Test Status |
|----------------------|--------|-------------|
| `/register`          | POST   | ✅ Passed    |
| `/login`             | POST   | ✅ Passed    |
| `/verify-otp`        | POST   | ✅ Passed    |
| `/change-password`   | POST    | ✅ Passed    |
| `/user/profile`      | POST    | ✅ Passed    |
| `/user/update-profile`      | PUT | ❌ Failed    |
| `/favourite-league/add `  | POST    | ✅ Passed     |
| `/favourite-Team/add`      | POST    | ✅ Passed    |
| `/favourite-league/Del`      | DEL    | ❌ Failed   |
| `/match-summary`      | GET    | ✅ Passed    |
| `/Match-details`      | GET    | ✅ Passed    |
| `/chat-AI`  | POST    | ✅ Passed    |
_**Total Assertions:**_ 
✅ _Passed: 147_ &nbsp;&nbsp;&nbsp;&nbsp;❌ _Failed: 3_


---
## 📊 Live Report Preview

👉 **[View Full Test Report](https://drive.google.com/file/d/1dDwD9F8kmQXLMzYgePPvHjtwpFKOi18o/view?usp=drive_link)**

<img width="914" height="923" alt="Image" src="https://github.com/user-attachments/assets/c525552a-644e-458a-b451-192aa9ca9095" />
<img width="923" height="607" alt="Image" src="https://github.com/user-attachments/assets/8d765b05-8078-4afc-bc5f-3a454b5e4abb" />
<img width="954" height="398" alt="Image" src="https://github.com/user-attachments/assets/9cffe92b-8594-48dd-b761-5aa54cec2a8a" />
<img width="916" height="270" alt="Image" src="https://github.com/user-attachments/assets/92a5e6d7-3b26-4c8e-bf59-c10e4b4a4a24" />



🕒 _Last generated: **October 11, 2025**_  

---

## ⚙️ Tech Stack

| Tool     | Purpose                       |
|----------|-------------------------------|
| Postman  | API requests & test scripting |
| Newman   | CLI-based test runner         |
| htmlextra | Stylish HTML report generator |
| Figma | Template design of the App  |


---

## 🚀 Quick Start

### 🔧 Install Dependencies

```bash
npm install -g newman newman-reporter-htmlextra
```
## 👨‍💻 Contributor
**SQA Engineer:** Md. Tajwar Ali
