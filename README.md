#  ShieldAI  
### *AI-Powered Parametric Income Insurance for Gig Workers*

>  Transforming unpredictable gig earnings into a **protected, intelligent income system**

---

##  **Who Are We Building For?**

Our platform is designed for **gig economy workers** — delivery partners working with platforms like:

- Swiggy  
- Zomato  
- Blinkit  
- Amazon  

###  **User Reality**

-  Earn **₹700–₹1000/day**
-  Paid **weekly**
-  Income depends on:
  -  Weather  
  -  Pollution  
  -  Demand  
  -  Mobility  

---

##  **Problem Statement**

Gig workers face **frequent income disruption** due to:

-  Heavy rainfall  
-  High AQI  
-  Heatwaves  
-  Urban restrictions  

 No structured system exists to **protect lost income**  

>  Platforms provide *incentives*, not *guarantees*

---

##  **Our Solution**

We introduce **RiskWise AI** — a next-generation **parametric insurance platform** that:

-  Predicts disruption risk using AI  
-  Dynamically prices weekly premiums  
-  Detects real-world triggers  
-  Automatically compensates workers  

---

##  **What Makes This Different?**

We are NOT building:

-  Just another ML model  
-  Just another insurance app  

We are building:

>  A **real-time AI-driven income protection system**

---

##  **AI/ML Strategy**

###  **Objectives**

Our system predicts:

1. **Disruption Probability** *(Classification)*  
2. **Income Loss** *(Regression)*  

---

###  **Input Features**

- rainfall  
- temperature  
- AQI  
- wind_speed  
- working_hours  
- deliveries_per_hour  
- city_factor  

---

###  **Models Used**

| Task | Model |
|------|------|
| Disruption Prediction |  Random Forest |
| Income Loss Prediction |  XGBoost |

---

###  **Outputs**

- `risk_score (0–1)`  
- `predicted_income_loss (₹)`  

---

###  **Example**

| Input | Output |
|------|--------|
| Rainfall = 25mm | Risk = 0.82 |
| AQI = 320 | Loss = ₹450 |

---

##  **System Architecture**
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

##  **Business Model**

###  **Weekly Premium**
Premium = max(2, min(50, income × risk_score × 0.03))

-  Affordable: ₹2–₹50/week  
-  Personalized pricing  

---

###  **Payout Model**

-  Affordable: ₹2–₹50/week  
-  Personalized pricing  

---

###  **Payout Model**

✔ No paperwork  
✔ No manual claims  
✔ Fully automated  

---

##  **Parametric Trigger System**

Triggers based on:

-  Rainfall > 20mm  
-  AQI > 300  
-  Temperature > 42°C  

---

###  **Workflow**
Trigger detected → Verified → Instant payout

---

##  **Adversarial Defense & Anti-Spoofing Strategy**

>  GPS alone is unreliable. We use **multi-signal intelligence**

---

###  **Core Idea**

-  Real user → consistent behavior across signals  
-  Fraud actor → mismatched signals  

---

###  **Signals Used Beyond GPS**

####  Movement Intelligence
- Speed consistency  
- Route continuity  
- Teleport detection  

####  Device Sensors
- Accelerometer  
- Gyroscope  

####  Work Behavior
- Delivery count  
- Idle time  
- App interaction  

####  Environmental Matching
- Weather API validation  
- AQI verification  

####  Network Intelligence
- IP clustering  
- Device fingerprinting  

---

###  **Fraud Risk Engine**

- Outputs: `fraud_score (0–1)`

---

###  **Decision Logic**

| Score | Action |
|------|-------|
| 🟢 Low | Instant payout |
| 🟡 Medium | Soft verification |
| 🔴 High | Flag + block |

---

###  **UX Principle**

> “Trust first. Verify silently. Never penalize genuine users.”

---

##  **Key Innovations**

-  AI + Parametric Hybrid Insurance  
-  Hyper-local risk prediction  
-  Gig worker simulation engine  
-  Dynamic weekly pricing  
-  Multi-signal fraud detection  

---

##  **Impact**

-  Income stability  
-  Instant payouts  
-  Reduced financial stress  
-  Scalable across cities  

---

##  **Future Scope**

- Real-time API integration  
- Mobile app (Flutter)  
- Blockchain-based claims  
- Expansion to all gig sectors  

---

##  **Final Thought**

> “We are not replacing gig work — we are stabilizing it.”

---

##  **Tech Stack**

- Python  
- Pandas / NumPy  
- Scikit-learn  
- XGBoost  
- Google Colab  

---

##  **ELITE**

---

## 🏁 **Status**

- ✔ Data Pipeline Completed   

---
