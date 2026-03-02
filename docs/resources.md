# **Crypto Pulse AI - Project Resources**

## **1. Data Sources**

_A collection of datasets, APIs, and live feeds to power our project._

#### **1.1. Static Datasets (For training and backtesting)**

-   **Crypto News Articles:** [https://www.kaggle.com/datasets/oliviervha/crypto-news](https://www.kaggle.com/datasets/oliviervha/crypto-news)
    -   _Description:_ A large dataset of historical crypto news headlines. Perfect for training our initial sentiment model.
-   **Daily Cryptocurrency Prices:** [https://www.kaggle.com/datasets/svaningelgem/crypto-currencies-daily-prices](https://www.kaggle.com/datasets/svaningelgem/crypto-currencies-daily-prices)
    -   _Description:_ Historical daily price data for various cryptocurrencies. Essential for correlating sentiment with price action.
-   **Hourly Crypto Market Data:** [https://www.kaggle.com/datasets/adrianjuliusaluoch/hourly-crypto-stocks-market-data](https://www.kaggle.com/datasets/adrianjuliusaluoch/hourly-crypto-stocks-market-data)
    -   _Description:_ More granular price data for detailed backtesting.

#### **1.2. Live Data Feeds & APIs (For the live dashboard)**

-   **Market News (Seeking Alpha):** [https://seekingalpha.com/market-news/trending](https://seekingalpha.com/market-news/trending)
    -   _Description:_ A source for real-time, trending financial news. We will need to investigate if they have a usable API or if we need to use a web scraping approach.

## **2. Code & Inspiration**

_GitHub repositories and articles for technical ideas and reusable code._

#### **2.1. Full Project Examples**

-   **Cryptocurrency Trading Data Analysis:** [https://github.com/yashajoshi/Cryptocurrency-Trading-Data-Analysis](https://github.com/yashajoshi/Cryptocurrency-Trading-Data-Analysis)
    -   _Description:_ A good example of a project that combines data analysis and trading. We can learn from its structure.

#### **2.2. Specific Tools & Libraries**

-   **Sentiment Analyzer Tool:** [https://github.com/Preethi303/sentiment-analyzer](https://github.com/Preethi303/sentiment-analyzer)
    -   _Description:_ A simple sentiment analysis tool. Good for understanding the basic mechanics.
-   **Awesome Systematic Trading List:** [https://github.com/wangzhe3224/awesome-systematic-trading](https://github.com/wangzhe3224/awesome-systematic-trading)
    -   _Description:_ The "candy store" we found! An amazing, curated list of tools and resources for every part of our project.

----------

### **Ideas for What to Add**

Here are some more categories and specific items you can add to your document as you find them.

#### **More Data Sources:**

-   **Live Price APIs:**
    -   **CoinGecko API:** Free, reliable, and has extensive data on thousands of coins. A must-have for our live dashboard.
    -   **CryptoCompare API:** Another excellent free API with news and social stats.
-   **Social Media Data:**
    -   **Twitter/X API:** Essential for real-time social sentiment. We'll need to apply for access.
    -   **Reddit API (PRAW):** For mining sentiment from communities like r/CryptoCurrency.
-   **On-Chain Data (Advanced):**
    -   **Dune Analytics or Glassnode:** For future versions, we could add data directly from the blockchain (e.g., transaction volumes, active addresses).

#### **More Code & Inspiration:**

-   **Dashboarding Libraries:**
    -   **Streamlit:** A very fast and easy way to build data apps in Python. Perfect for our MVP.
    -   **Plotly Dash:** More powerful and customizable for building complex, enterprise-level dashboards.
-   **Machine Learning & Sentiment Libraries:**
    -   **Hugging Face Transformers:** For using state-of-the-art AI models for sentiment analysis.
    -   **VADER Sentiment:** A simple, rule-based sentiment tool that's great for social media text and doesn't require training.

#### **New Category: Tools & Platforms**

-   **API Testing:**
    -   **Postman:** A tool to help us test and understand how different APIs work before we write any code.
-   **Cloud Hosting:**
    -   **AWS, Google Cloud, or Azure:** We'll eventually need a place to host our live application. We can start with their free tiers.