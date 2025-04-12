# I. Solution Architecture

## Overview
The system is designed to provide a smart, scalable, and responsive AI-powered assistant for merchants. It consists of a mobile frontend, a robust backend API, and an AI engine that handles personalization and natural language understanding.

## Overall System Diagram
![Simple Architecture](/simplifiedarchitecture.png)


---

## System Components

### React Native (Frontend)
- Cross-platform mobile app where merchants:
  - Interact with the assistant
  - View insights
  - Take actions

### FastAPI (Backend)
- Handles:
  - Business logic
  - Authentication
  - Data processing
  - Communication between frontend and AI engine

### Claude MCP (AI Engine)
- Powers the conversational assistant:
  - Natural language understanding
  - Generating insights
  - Triggering personalized recommendations

### Database + Analytics Layer
- Stores:
  - Merchant data
  - Usage history
  - AI feedback loops
- Used to:
  - Fine-tune recommendations
  - Track performance

---

# II. Data Utilization

### Data Sources
- Hackathon 2025 provided datasets

### Data Storage
- Lightweight relational database: **SQLite**

---

# III. Personalization Goals and Objectives

## Desired Outcomes
- **Increased Engagement**  
  Show relevant content to increase usage frequency.

- **Higher Conversion Rates**  
  Drive sales through actionable, tailored insights.

- **Improved Satisfaction**  
  Deliver value-aligned suggestions to each merchant.

## Measurement Metrics
- Engagement rate (e.g., click-through, usage time)
- Business performance (e.g., sales growth)
- User satisfaction (e.g., feedback scores, retention rate)

---

## Segmentation Strategies

Users segmented by:

- **Business Size:** Small, Medium, Growing  
- **Location:** Urban vs. Rural  
- **Type:** Food vendor, Clothing seller, Electronics, etc.  
- **Behavior:** Engaged daily vs. Passive users  

Each segment receives customized:
- Messages
- Alerts
- Recommendations
- Reports

---

## Real-Time vs. Batch Personalization

### Real-Time (Instant)
- Chat responses
- Urgent alerts (e.g., "Stock is low")

### Batch (Nightly/Weekly Processing)
- Sales trend analysis
- Market comparison reports
- Updated product recommendations

