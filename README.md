# 💧 The Aqua Cycle — *Go Green, Go Fresh*

> Reducing single-use plastic waste through IoT-enabled smart water fountains and an AI-powered mobile app, piloted in Boston, MA.

---

## 🌍 Problem Statement

Over **1 million plastic water bottles** are consumed every minute globally, with less than 30% recycled. In Boston alone:
- Only **250 public water fountains** exist citywide
- Underserved neighborhoods like Dorchester and Roxbury have **fewer than 10 fountains each**
- The Charles River receives **1.6 million pounds** of plastic waste annually, with bottles contributing 35%
- **43% of users** continue buying single-use bottles simply due to lack of accessible refill stations

---

## 💡 Solution

The Aqua Cycle is a two-part system:

1. **IoT-Enabled Smart Water Fountains** : sensors monitor real-time usage, water quality, and operational status across the city
2. **The Aqua Cycle Mobile App** : connects users to nearby fountains, tracks their environmental impact, and rewards sustainable behavior

---

## 📱 App Features

| Feature | Description |
|---|---|
| 🗺️ Water Fountain Locator | Real-time map showing nearby fountains with availability status |
| 👤 User Profile & Dashboard | Tracks refills, rewards points, and personal sustainability impact |
| 🏆 Points & Rewards | Gamified system: earn points per refill, redeem for coupons |
| 📷 QR Code Check-in | Scan fountain QR code to log usage and earn points |
| 🔔 Push Notifications | Alerts for nearby fountains when within walking distance |
| 🌐 Company & Mission Page | Learn about Aqua Cycle's mission and the team |

**Prototype built with:** proto.io — screenshots available below
<img width="771" height="513" alt="Screenshot 2026-06-05 120853" src="https://github.com/user-attachments/assets/30259ff8-a6ee-4126-b08d-f0216172191f" />
<img width="661" height="460" alt="Screenshot 2026-06-05 120846" src="https://github.com/user-attachments/assets/1ccbc5d5-d8dd-47de-a046-e45b7dc630b8" />
<img width="766" height="507" alt="Screenshot 2026-06-05 120839" src="https://github.com/user-attachments/assets/cb18c7be-6dd6-4f2e-a6a4-347526d1a47c" />
<img width="822" height="572" alt="Screenshot 2026-06-05 120910" src="https://github.com/user-attachments/assets/c95dc99c-f067-4dca-90ad-034353e6694a" />
<img width="797" height="570" alt="Screenshot 2026-06-05 120900" src="https://github.com/user-attachments/assets/ffc50475-f45e-4610-9e6f-0ee4182d3514" />

---

## 🤖 AI & Technology Stack

### IoT Layer
- **Sensors** collect real-time data on water quality (pH, turbidity, chloramines), usage volume, and foot traffic
- **SQL databases** store large-scale multi-fountain data
- **ARIMA / Time-Series Analysis** for predictive maintenance scheduling

### AI Models
- **Random Forest / Gradient Boosting** :forecast fountain usage and maintenance needs
- **K-Means Clustering** :group fountains by usage level and maintenance priority
- **Regression Analysis** :identify factors influencing usage (weather, proximity, time of day)

### App Development
- **React Native / Flutter** :cross-platform iOS & Android compatibility
- **NLP (Hugging Face / Dialogflow)** :chatbot and voice-based navigation
- **Recommendation System** :suggests nearby fountains based on user behavior

### Data & Analytics
- **Python** (Pandas, NumPy, Scikit-learn) for preprocessing and modeling
- **Google Colab** for ML development and experimentation
- **Tableau / Power BI** for stakeholder dashboards
- **Water potability dataset** via [Kaggle](https://www.kaggle.com/code/neesha12/water-potability-analysis/input)
- **MA Recycling & Waste Data** via [MassDEP](https://www.mass.gov/lists/recycling-solid-waste-data-for-massachusetts-cities-towns)

---

## 🗺️ Rollout Plan

```
Phase 1 (0–6 months)     → Pilot: 10 smart fountains in high-traffic Boston locations
Phase 2 (6–18 months)    → Regional: 50–60 fountains, expand to underserved neighborhoods
Phase 3 (18+ months)     → National & Global scaling with city-specific customization
```

---

## 📊 Projected Impact

- 🔻 **10% reduction** in single-use plastic bottles → prevents **10,000+ lbs of waste/year** in Boston
- 💧 **20% increase** in clean drinking water access in underserved communities
- 🏥 **25% reduction** in dehydration incidents in areas with accessible fountains
- 💰 ROI turns positive in **Year 2**, reaching **396% ROI by Year 6**

---

## 💰 Business Model

| Revenue Stream | Details |
|---|---|
| User Fees | $0.50 per litre — projected $18.25M in Year 1 (100K users) |
| In-App Advertising | $10–$200/day (Boston market) |

**Total Phase 1 Cost:** ~$140,000–$220,000  
**Break-even:** Year 2

---

## 🤝 Key Stakeholders

- **Local Government** — funding and policy support
- **Schools & Businesses** — awareness campaigns and bottle distribution
- **Environmental NGOs** — advocacy and education
- **Reusable Bottle Manufacturers** — distribution partnerships

---

## 🧩 SDG Alignment

| Goal | Relevance |
|---|---|
| 🌊 SDG 6 — Clean Water & Sanitation | Expanding access to free, clean drinking water |
| ♻️ SDG 12 — Responsible Consumption | Reducing single-use plastic waste at scale |
| 🏙️ SDG 11 — Sustainable Cities | Smart city infrastructure for urban communities |

---

## 👥 Team — MBAN2 Team 4

| Name | Role |
|---|---|
| Mohammed Labaran Halliru | Business Strategy |
| Yashvi Nagda | App Design & Business Strategy |
| Hakeem Garcia | Data Analyst |
| Ashley Josi | Business Strategy |
| Janati Nakimera | Business Strategy |
| Vincent Nyamora Osere | Data Analyst |

*Hult International Business School, Cambridge, MA*

---

## 📎 Resources

- 📄 Business Proposal [(attached)](https://github.com/YashviNagda20/The_Aqua_Cycle/blob/main/The%20Aqua%20Cycle.pdf)]
- 📄 Business Problem (https://github.com/YashviNagda20/The_Aqua_Cycle/blob/main/Business%20Challenge%20Proposal.pdf)
- 📊 MVP Technical Documentation [(attached)](https://github.com/YashviNagda20/The_Aqua_Cycle/blob/main/Phase%203_%20MVP%20Prototyping%20and%20Testing%20(1).pdf)]

---

> *"Every refill is a step toward a plastic-free future."*
