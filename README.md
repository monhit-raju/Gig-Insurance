# ShieldAI

### AI-Powered Income Protection for Gig Delivery Workers

> *“When disruptions stop deliveries, income shouldn’t stop.”*

---

## Overview

ShieldAI is an AI-powered parametric insurance platform designed to protect gig delivery workers (Swiggy, Zomato, Zepto, Amazon, etc.) from income loss caused by external disruptions such as heavy rain, pollution, extreme heat, and curfews.

Gig workers lose **20–30% of their income** due to such uncontrollable events, and currently there is **no insurance solution for income protection**.

ShieldAI solves this by enabling **automatic disruption detection, AI-driven risk assessment, and instant payout processing** without requiring manual claims.

---

## Problem Understanding

Gig delivery workers depend on daily earnings. However:

* External disruptions reduce working hours
* No system exists to protect **income loss**
* Workers face financial instability

> Important Constraint:
> ShieldAI only covers **income loss**, not health, life, or vehicle insurance.

---

## Persona-Based Scenario

### Persona: Ravi (Delivery Partner – Swiggy, Chennai)

* Works 8–10 hours daily
* Earns ~₹3000/week
* Relies completely on active delivery time

### Scenario

* Heavy rainfall hits Chennai
* Delivery demand drops + roads flood
* Ravi can only work 3–4 hours

### Impact

* Expected income: ₹3000
* Actual income: ₹1800
* Loss: ₹1200

### ShieldAI Response

* Detects heavy rainfall via API
* Calculates disruption severity
* Estimates income loss
* Automatically triggers payout

Ravi receives compensation instantly without filing a claim

---

## System Workflow

1. Worker registers on platform
2. AI calculates risk score based on location & conditions
3. Weekly insurance policy is generated
4. External APIs monitor disruptions continuously
5. When disruption occurs → parametric trigger activates
6. Claim is automatically created
7. AI estimates income loss
8. Fraud detection validates claim
9. Payout is processed instantly

---

## Weekly Premium Model

ShieldAI uses a **dynamic weekly pricing system** aligned with gig workers’ earning cycles.

### How it Works

Premium is calculated based on:

* Weather risk (rainfall, heat, pollution)
* Location risk (city-level disruptions)
* Worker activity (hours worked, consistency)
* Historical disruption data

### Example

| Risk Level  | Weekly Premium |
| ----------- | -------------- |
| Low Risk    | ₹30            |
| Medium Risk | ₹50            |
| High Risk   | ₹80            |

This ensures affordability and fairness.

---

## Parametric Triggers

Payouts are triggered automatically based on predefined conditions.

### Examples

* Rainfall exceeds threshold
* AQI crosses dangerous level
* Extreme heat alert issued
* Government curfew or shutdown

No manual claim submission required.

---

## AI/ML Integration

ShieldAI uses AI in multiple components:

### 1. Risk Prediction Model

* Predicts likelihood of disruptions
* Uses:

  * weather data
  * pollution data
  * historical patterns

### 2. Dynamic Premium Calculation

* Adjusts weekly premium in real-time
* Based on risk score

### 3. Income Loss Estimation

* Predicts expected vs actual earnings
* Calculates accurate payout

### 4. Fraud Detection Model

* Detects:

  * fake location claims
  * duplicate claims
  * abnormal behavior
* Uses anomaly detection (Isolation Forest)

---

## System Architecture

```
Frontend (React + Vite)
        ↓
Node.js Backend (Express)
        ↓
--------------------------------------
| AI Risk Engine (FastAPI)          |
| Fraud Detection Engine            |
| Parametric Trigger Engine         |
--------------------------------------
        ↓
Claim Automation Engine
        ↓
Payment Service (Simulation)
        ↓
MongoDB Atlas
        ↓
External APIs (Weather, AQI, Maps)
```

---

## Tech Stack

### Frontend

* React + Vite
* TailwindCSS
* Chart.js
* Mapbox

### Backend

* Node.js + Express

### AI Engine

* Python FastAPI
* Scikit-learn
* XGBoost

### Database

* MongoDB Atlas

### APIs

* OpenWeather API
* AQI API
* Mapbox API

---

## Platform Choice

We chose a **Web Application** because:

* Easy access for all users
* Faster development for hackathon
* No installation required
* Scalable for future mobile integration

---

## Development Plan

### Phase 1 (Current)

* Problem understanding
* Persona definition
* System design
* AI planning
* README (Idea Document)

### Phase 2

* Backend + database setup
* AI model integration
* API development

### Phase 3

* Frontend dashboard
* Map visualization
* Claim automation

### Phase 4

* Testing + optimization
* Demo simulation
* Deployment

---

## Unique Innovation

* Fully automated **zero-claim insurance system**
* AI-based **income loss estimation**
* **Worker reputation scoring system**
* Real-time **risk heatmap visualization**
* City-level **insurance pooling concept**

---

## Future Scope

* Integration with delivery platform APIs
* Real-time earnings tracking
* Government-backed micro-insurance
* Expansion to ride-sharing & freelance workers

---

## Conclusion

ShieldAI transforms insurance from a **reactive system** into a **proactive, intelligent safety net** for gig workers.

> *“We are not just insuring events — we are protecting livelihoods.”*
