# GhostJob
Fake job detection for South Africa- Developed using # 👻 GhostJob - Fake Job Detector for South Africa

> Because no one in SA should pay to get a job.

In Durban, thousands of young people lose money to fake jobs on WhatsApp every week.
"Pay R350 for training, earn R20,000 work from home"

GhostJob fixes this. Paste any job message and get a Scam Score 0-100 in 2 seconds.

## 🚀 Features
- Paste & Check any WhatsApp job message
- C# Scam Engine with 6 rules (upfront fee, WhatsApp only, Gmail, urgency, crypto, high salary)
- Community Blacklist - Report scam numbers
- Search Blacklist by phone number or company
- RED = Scam, ORANGE = Suspicious, GREEN = Safe

## 🛠 Tech Stack
- C# + ASP.NET Core 8 MVC
- Entity Framework Core + SQLite
- Bootstrap 5
- Custom Rule-Based Scam Detector Service

## ▶️ How To Run
```bash
dotnet restore
dotnet build
dotnet run
