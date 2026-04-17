# 🏭 Remote Control Central (RCC) / Human Resource Efficiency (HRE)

A real-time industrial machine monitoring and analytics platform designed to digitize factory operations and improve production efficiency.

---

## 🚀 Overview

Remote Control Central (RCC) is a production-grade SaaS platform used across multiple manufacturing plants to monitor machine status, workforce allocation, and operational efficiency in real-time.

The system replaces manual processes (paper/Excel) with a centralized, data-driven solution, enabling faster decision-making and improved productivity.

---

## 🎯 Key Features

- ⚡ Real-time machine status monitoring (Running, Downtime, Changeover)
- 👷 Workforce (headcount) tracking per machine
- 🏭 Interactive factory layout (digital twin visualization)
- 📊 Live dashboards with status aggregation and analytics
- 🚨 Machine attention alerts based on time thresholds
- 📈 Advanced reporting (charts, statistics)
- 📄 Automated hourly Excel reports
- 📩 Integration with Microsoft Teams & Email notifications
- 🗂️ Historical data access and reporting

---

## ⚙️ System Architecture

- Event-driven architecture for high-frequency data processing
- WebSocket-based real-time communication (no polling)
- Queue-based processing using Redis + BullMQ
- Batch database insertion for performance optimization
- Data lifecycle management (hot vs historical storage)

---

## 📊 Scale & Performance

- 🏭 1000+ machines monitored
- ⚡ ~2000+ data records processed every 4 seconds
- 📈 100M+ rows handled per month
- 🚀 Low-latency real-time updates across dashboards
- 🔄 Stable under continuous high-frequency data load

---

## 🧠 My Responsibilities

- Designed and implemented event-driven architecture
- Built real-time data pipeline using WebSocket & queues
- Optimized database performance with batching & caching
- Developed interactive factory visualization (Fabric.js)
- Implemented automated reporting (Excel + Teams integration)
- Built deployment automation (Docker + Kubernetes)
- Improved system scalability and reliability

---

## 🛠️ Tech Stack

### Backend

- Node.js
- Elysia.js
- Redis
- BullMQ
- MSSQL
- Prisma

### Frontend

- React
- Next.js
- TailwindCSS
- Fabric.js

### Realtime

- WebSocket
- Socket.io

### DevOps

- Docker
- Kubernetes
- CI/CD automation

---

## 💡 Key Highlights

- Eliminated manual tracking systems across production plants
- Enabled real-time monitoring and faster issue detection
- Reduced operational overhead through automation
- Built a scalable system handling industrial-scale data

---

## 📫 Contact

- LinkedIn: https://www.linkedin.com/in/sazzad-bin-anwar-5790b3145/
- Email: sazzadzihan@gmail.com
