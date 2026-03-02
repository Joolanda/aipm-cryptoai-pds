### **[Crypto Pulse AI] - 3-Week Scope Definition**

#### **MVP Statement**

"In 3 weeks, we will build a **functional web-based dashboard** that allows **retail crypto traders** to **view a consolidated sentiment score for a specific cryptocurrency (e.g., Bitcoin)**, helping them **quickly gauge market mood and validate their trading ideas.**"

#### **Core Features (Must Have)**

1.  **Data Ingestion Pipeline:** A script that automatically fetches recent news articles and tweets related to a target cryptocurrency using at least one free API.
2.  **Core AI Sentiment Model:** A basic sentiment analysis model (e.g., using a pre-trained library like VADER or a simple Hugging Face model) that processes the text data and assigns a positive, negative, or neutral score.
3.  **Data Aggregation & Scoring:** A process that aggregates the individual sentiment scores into a single, time-based overall sentiment score (e.g., an average score for the last 24 hours).
4.  **Simple Dashboard UI:** A single web page that displays the current sentiment score for the chosen crypto, perhaps with a simple "Positive," "Neutral," or "Negative" indicator and a basic chart showing the score over the last few days.

#### **Success Criteria**

-   **User:** A user can load the dashboard and, within 30 seconds, understand the current prevailing sentiment for Bitcoin.
-   **Technical:** The sentiment model can process 100+ articles/tweets and produce a daily score that directionally correlates with major positive or negative price movements.
-   **Business:** You have a working prototype that you can show to other traders to get initial feedback and validate that "consolidated sentiment" is a valuable metric for them.

#### **Weekly Milestones**

-   **Week 1: Foundation & Core AI.**
    
    -   **Goal:** Get the core AI functionality working with test data.
    -   **Deliverable:** A functional Python script that can take a list of crypto news headlines and output a sentiment score for each.
    -   **Demo:** "Here's our script successfully analyzing sample news data and scoring it."
-   **Week 2: Integration & Dashboard.**
    
    -   **Goal:** Create the complete user journey from live data to display.
    -   **Deliverable:** A live data pipeline that fetches data from at least one API, processes it with the sentiment model, and displays the final aggregated score on a basic, functional web page.
    -   **Demo:** "Here is our live dashboard showing today's sentiment score for Bitcoin, based on real-time data."
-   **Week 3: Polish & Validation.**
    
    -   **Goal:** Refine the experience and prepare for the final presentation.
    -   **Deliverable:** A cleaned-up dashboard with improved visuals (e.g., a simple time-series chart), basic error handling, and a clear explanation of what the user is seeing.
    -   **Demo:** "Here is our validated Crypto Pulse AI MVP, ready to be shown to users for feedback."

#### **Explicitly Out of Scope (for the 3-Week MVP)**

-   **Analysis of multiple cryptocurrencies.** We will focus only on one (e.g., Bitcoin) to prove the concept.
-   **Advanced alternative data.** Your brilliant idea for **Flight Radar data integration** is a fantastic "next version" feature but is out of scope for the initial 3-week sprint.
-   **User accounts and personalization.** The dashboard will be public and the same for all users.
-   **Real-time, sub-minute updates.** A daily or hourly update is sufficient for the MVP.

#### **Biggest Risks & Mitigations**

1.  **Risk: Data Access Issues.** A chosen free API for news or tweets becomes unreliable or has stricter-than-expected rate limits.
    -   **Mitigation**: Identify 2-3 potential data sources _before_ Week 1 begins. If the primary one fails, you can quickly pivot to the backup without losing significant time.
2.  **Risk: Sentiment Model Quality.** The basic sentiment model is not accurate enough and gives nonsensical results.
    -   **Mitigation**: Start with the simplest possible model (like VADER). It's better to have a working, simple system than a broken, complex one. The goal is to build the full pipeline; the model's accuracy can be improved later.

----------

### ✅ **Final Day 1 Complete!**

We just successfully laid an incredible foundation for our project:

-   ✅ A **viable team** with shared excitement.
-   ✅ A strong **business foundation** with a clear model.
-   ✅ A responsible **ethical approach** to building your AI.
-   ✅ A **realistic and achievable scope** for the next 3 weeks.
-   ✅ Clear **weekly milestones** to guide your development sprint.