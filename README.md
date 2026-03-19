# ShieldAI  
### AI-Powered Income Protection for Gig Delivery Workers

> *“When disruptions stop deliveries, income shouldn’t stop.”*

---

## Overview

ShieldAI is an AI-powered parametric insurance platform designed for India’s gig delivery workers — including Swiggy, Zomato, Zepto, and Amazon delivery partners.

These workers often lose **20–30% of their income** due to uncontrollable disruptions like heavy rain, extreme heat, pollution, or curfews. Currently, there is **no safety net** to protect their income.

ShieldAI solves this problem by **automatically detecting disruptions and instantly compensating workers for income loss**, without requiring manual claims.

---

## Problem Statement

Gig workers depend on daily earnings, but:

- External disruptions reduce working hours  
- No insurance exists for **income loss**  
- Workers bear full financial risk  

> This system covers **income loss only** — not health, life, or vehicle insurance.

---

## Solution

ShieldAI introduces a **fully automated parametric insurance system**:

- Real-time disruption detection (weather, pollution, etc.)
- AI-based risk prediction
- Automatic claim triggering
- Instant payout processing

No paperwork. No delays. No manual intervention.

---

## Unique Features

### AI-Based Dynamic Weekly Pricing
- Premium adapts based on:
  - weather conditions  
  - city risk levels  
  - worker activity  
- Designed around **weekly earning cycles**

---

### Real-Time Risk Heatmap
- Live visualization of:
  - high-risk zones  
  - pollution spikes  
  - rainfall intensity  
- Helps workers decide whether to work or stay safe

---

### Zero-Claim Insurance
- No need to file claims manually  
- System automatically detects disruptions  
- Claims and payouts happen instantly  

---

### Intelligent Fraud Detection
- Detects:
  - fake location claims  
  - repeated suspicious claims  
  - inactivity patterns  
- Uses machine learning (Isolation Forest)

---

### AI-Based Income Loss Estimation
- Predicts expected earnings vs actual earnings  
- Calculates **real income loss**, not just fixed payouts  

---

### Worker Reputation Score
- Each worker gets a trust score based on:
  - activity  
  - claim history  
  - fraud risk  
- Benefits:
  - lower premiums  
  - faster payouts  

---

### City-Level Risk Pool
- Workers contribute to a shared insurance pool  
- AI balances risk across locations  
- Enables scalable micro-insurance  

---

### One-Click Demo Simulation
- “Simulate Rainstorm” feature  
- Shows:
  - disruption detection  
  - income drop  
  - claim triggered  
  - payout processed  

---

## System Architecture

ShieldAI is designed as a modular, scalable system combining frontend, backend, and AI microservices.

### Architecture Flow

Frontend (React + Vite)
↓
Node.js API Gateway (Express)
↓
| AI Risk Engine (Python FastAPI) |
| Fraud Detection Engine |
| Parametric Trigger Engine |
↓
Claim Automation Engine
↓
Payment Service (Razorpay Mock)
↓
MongoDB Atlas Database
↓
External APIs (Weather, AQI, Maps)


### How Data Flows

1. Worker registers and logs in  
2. Backend stores worker data in MongoDB  
3. AI engine calculates risk score  
4. Policy is created with weekly premium  
5. External APIs continuously monitor disruptions  
6. If disruption occurs → trigger engine activates  
7. Claim engine processes claim automatically  
8. Fraud detection validates claim  
9. Payment service simulates payout  
10. Dashboard updates with analytics  

---

## Tech Stack

### Frontend
- React + Vite  
- TailwindCSS  
- Chart.js  
- Mapbox  

### Backend
- Node.js  
- Express.js  

### AI Engine
- Python FastAPI  
- Scikit-learn  
- XGBoost  

### Database
- MongoDB Atlas  

### APIs
- OpenWeather API  
- AQI API  
- Mapbox API  

### Payments
- Razorpay Sandbox (Simulation)  

### Deployment
- Vercel (Frontend)  
- GCP Cloud Run (Backend & AI)  
- MongoDB Atlas (Database)  

---

## Core Features

- Worker Registration & Login  
- AI-Based Risk Profiling  
- Weekly Premium Calculation  
- Real-Time Disruption Detection  
- Automated Claim Processing  
- Instant Payout Simulation  
- Fraud Detection System  
- Analytics Dashboard  

---

## How It Works

1. Worker registers on the platform  
2. AI calculates risk score using location & environment  
3. Weekly insurance policy is created  
4. External disruption (rain, pollution, etc.) occurs  
5. System detects event automatically  
6. Claim is triggered without user action  
7. AI calculates income loss  
8. Payment is processed instantly  

---

## Example Scenario

**Worker:** Ravi (Swiggy, Chennai)

- Expected weekly income: ₹3000  
- Heavy rain reduces deliveries  
- Actual income: ₹1800  

=> Loss = ₹1200  
=> System detects heavy rain  
=> Claim triggered automatically  
=> ₹1200 payout processed  

---

## Project Structure
shieldAI/
│
├── frontend/ # React application
├── backend/ # Node.js Express server
├── ai-engine/ # Python AI models
├── data/ # datasets
├── scripts/ # helper scripts
├── docs/ # documentation
└── README.md # project overview