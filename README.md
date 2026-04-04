#  Shield AI  
### *AI-Powered Parametric Income Protection for Food Delivery Riders*

>  Transforming unpredictable gig earnings into a **stable and protected income system**

---

##  Target User (Focused Segment)

Our platform is specifically designed for:

>  **Food delivery riders working with platforms like Swiggy and Zomato in urban India**

###  Why this segment?

- Highly dependent on **weather and mobility**
- Earn **₹700–₹1000/day**
- Face **frequent income disruptions**
- Lack structured financial protection  

---

##  Problem Statement

Food delivery riders experience **income loss due to external disruptions** such as:

-  Heavy rainfall  
-  High AQI  
-  Extreme heat  

Current platforms provide **incentives**, but:

❌ No guaranteed protection  
❌ No structured compensation  
❌ No transparency  

---

##  Our Solution

**Shield AI** is a **parametric micro-insurance system** that:

- 🤖 Predicts disruption risk using AI  
- 📊 Dynamically prices weekly premiums  
- ⚡ Detects real-world triggers  
- 💸 Automatically pays income compensation  

> ✅ No claims. No paperwork. Instant payouts.

---

##  AI/ML Strategy

###  Objectives

1. **Disruption Prediction** *(Classification)*  
2. **Income Loss Estimation** *(Regression)*  

---

###  Input Features

- rainfall  
- temperature  
- AQI  
- wind_speed  
- working_hours  
- deliveries_per_hour  
- city_factor  

---

###  Model Choices (Justification)

-  **Random Forest**  
  → Used for disruption prediction due to:
  - high interpretability  
  - robustness with tabular data  
  - ability to handle non-linear relationships  

-  **XGBoost**  
  → Used for income loss estimation because:
  - captures complex interactions  
  - performs well on structured datasets  
  - handles variance effectively  

> These ensemble methods balance bias and variance, ensuring stable predictions under dynamic conditions.

---

###  Outputs

- `risk_score (0–1)`  
- `predicted_income_loss (₹)`  

---

##  System Architecture
Weather + AQI APIs
↓
Data Processing Layer
↓
ML Prediction Engine
↓
Fraud Detection Engine
↓
Decision Engine
↓
Premium + Payout System


---

##  Business Model (Insurance-Aligned)

###  Weekly Premium Model
Premium = max(20, min(100, income × risk_score × 0.03))


-  Affordable (₹20–₹100/week)  
-  Personalized pricing  

---

###  Payout Logic
If disruption triggered → payout = income_loss

✔ Instant payout  
✔ No manual claims  

---

##  Loss Ratio Modeling (Key Differentiator)

We maintain a sustainable **loss ratio**:
Loss Ratio = Total Claims / Total Premiums

###  Target:

> ✅ **60% – 70% loss ratio (industry healthy range)**

###  Example:

- Premium collected = ₹30,000  
- Payout = ₹18,000  
- Loss ratio = 60%  

---

##  Claim Frequency Modeling

We estimate claim frequency using:

- predicted disruption probability  
- historical environmental patterns  

This ensures:

✔ sustainable payouts  
✔ controlled risk exposure  

---

##  Parametric Trigger System

Triggers based on real-world data:

-  Rainfall > 20mm  
-  AQI > 300  
-  Temperature > 42°C  

---

###  Claim Flow (5-Step System)

1. Environmental data monitored  
2. AI predicts disruption risk  
3. Parametric trigger validated  
4. Fraud detection applied  
5. Instant payout credited  

---

##  IRDAI Awareness & Compliance

Our system is designed with awareness of **IRDAI microinsurance principles**:

###  Key Elements:

- Structured premium limits  
- Defined claim conditions  
- Sustainable loss ratio  
- Transparent pricing  

---

###  Standard Exclusions

- War and civil unrest  
- Pandemic-related disruptions  
- Government-imposed shutdowns  

---

##  Adversarial Defense & Anti-Spoofing

> GPS alone is unreliable — we use **multi-signal verification**

---

###  Multi-Signal Trust Model

-  Real user → consistent behavior  
-  Fraud → signal mismatch  

---

###  Signals Used

- movement patterns  
- device sensors  
- delivery activity  
- weather verification  
- IP/device fingerprinting  

---

###  Fraud Score

- `fraud_score (0–1)`

---

###  Decision Logic

| Score | Action |
|------|-------|
| Low | Instant payout |
| Medium | Soft verification |
| High | Flag & block |

---

###  UX Principle

> “Trust first. Verify silently. Protect genuine users.”

---

##  Key Innovations

- AI + Parametric Insurance Model  
- Focused gig segment (food delivery)  
- Loss ratio-based pricing  
- Multi-signal fraud detection  
- Real-time risk prediction  

---

##  Impact

-  Income stability  
-  Instant payouts  
-  Reduced financial stress  
-  Scalable system  

---

##  Future Scope

- Real-time API integration  
- Mobile app (Flutter)  
- Blockchain-based claim validation  
- Expansion to ride-sharing sector  

---

##  Final Thought

> “We are not replacing gig income — we are stabilizing it.”

---

##  Tech Stack

Python, Pandas, NumPy, Scikit-learn, XGBoost, Google Colab, Matplotlib

---

##  Team : ELITE

---

## 🏁 Status

✔ Data Pipeline Completed  
✔ ML Models Trained  
✔ Risk Engine Built  
✔ Fraud Detection Designed  
✔ Insurance Logic Integrated  


