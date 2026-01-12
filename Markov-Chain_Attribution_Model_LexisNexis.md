# Markov-Chain Based Attribution Model at LexisNexis Risk Solutions

## Author: Wecsley O. Prates, Ph.D.

---

## Executive Summary

During his tenure as **Data Scientist / Marketing Analyst** at **LexisNexis Risk Solutions** (January 2021 – April 2024), Wecsley Prates developed a pioneering **Markov Chain-based Multi-Touch Attribution (MTA) Model**—the first of its kind in the company's 25-year history. This innovative solution optimized marketing budget allocation, improved campaign performance, and provided deep insights into customer journey analytics, resulting in significant cost savings and improved ROI.

---

## Background & Problem Statement

### The Challenge

LexisNexis Risk Solutions had been relying on traditional attribution methods, primarily **Last-Touch Attribution**, which oversimplified customer journeys by crediting only the final touchpoint before conversion. This approach:

- **Ignored intermediate interactions** that contributed to conversions
- **Failed to recognize** the role of assisting channels (e.g., display ads, email)
- **Limited visibility** into the true value of each marketing channel
- **Resulted in suboptimal budget allocation** across marketing channels

### The Opportunity

The marketing team needed a more sophisticated approach to:
- Understand the complete customer journey across multiple touchpoints
- Accurately attribute value to each marketing channel
- Identify underperforming campaigns
- Optimize budget allocation based on data-driven insights

---

## Why Markov Chains?

### Rationale for Methodology Selection

Wecsley chose **Markov Chains** for this attribution modeling challenge because:

1. **Probabilistic Framework**: Markov Chains provide a robust probabilistic framework to model user pathways and determine channel contributions throughout the customer journey.

2. **Removal Effects Analysis**: The methodology enables calculation of "removal effects"—the impact on conversion rates if a specific channel were removed from the customer journey.

3. **Captures Sequential Behavior**: Unlike traditional methods, Markov Chains capture the sequential nature of customer interactions, accounting for:
   - Transitions between channels (e.g., email → search → direct)
   - The influence of intermediate touchpoints
   - Multi-step conversion paths

4. **Handles Complex Journeys**: The model can process complex, non-linear customer journeys that are common in modern digital marketing.

---

## Implementation Approach

### Data Preparation

**Data Sources:**
- Historical customer touchpoint data from multiple marketing channels
- Transactional data from the company's data warehouse
- Campaign performance metrics

**Data Processing:**
- Captured transitions between channels (e.g., email → search → direct)
- Structured customer journey sequences
- Cleaned and preprocessed historical interaction data

### Model Development

**Tools & Technologies:**
- **R Programming**: Primary development environment
- **Markov Chain Algorithms**: Implemented custom probabilistic models
- **Statistical Packages**: Utilized R's topicmodels and related libraries

**Methodology:**
1. **Transition Matrix Creation**: Built transition probability matrices showing how customers move between marketing channels
2. **Removal Effects Calculation**: Computed the impact of removing each channel from the customer journey
3. **Attribution Scoring**: Assigned conversion credit to each channel based on its contribution to the overall conversion probability

### Visualization & Reporting

**Delivery Tools:**
- **Power BI**: Created interactive dashboards for stakeholder insights
- **R-Shiny**: Developed dynamic reporting applications for deeper analysis
- **Clear Visualizations**: Enabled marketing teams to understand channel effectiveness and ROI scenarios

---

## Business Outcomes & Impact

### Quantifiable Results

#### 1. **Increased Budget Efficiency**
- **15% reduction in spend** on low-impact channels
- Identified and eliminated underperforming campaigns
- Redirected resources to high-performing channels

#### 2. **Improved Return on Investment**
- **12% increase in ROI** through optimized budget allocation
- **$500K budget reallocation** to high-impact channels
- **15% increase in conversion rates** from optimized channel mix

#### 3. **Enhanced Campaign Performance**
- **30% improvement** in campaign budget allocation accuracy
- Significant cost savings across marketing operations
- Better alignment between spend and performance

### Strategic Insights

#### Discovery of Assisting Channels
- Identified that certain channels (e.g., display ads) played **significant roles in assisting conversions**, even though they weren't directly leading to conversions
- This insight prevented potential budget cuts to valuable assisting channels

#### Optimized Customer Journey Understanding
- Provided comprehensive view of multi-step customer journeys
- Revealed the sequential importance of touchpoints
- Enabled data-driven journey optimization strategies

#### Improved Stakeholder Decision-Making
- Delivered actionable insights through clear visualizations
- Enabled marketing teams to make **data-driven decisions** with confidence
- Facilitated strategic discussions around channel investment

---

## Technical Innovation

### First-of-Its-Kind Implementation

This Markov Chain-based Attribution Model was **LexisNexis Risk Solutions' first implementation** since the company was created 25 years ago, representing:

- A significant technological advancement in the company's analytics capabilities
- A shift from traditional to advanced attribution methodologies
- A foundation for future data-driven marketing initiatives

### Integration with Broader Analytics Ecosystem

The attribution model complemented other analytics initiatives Wecsley led at LexisNexis:

1. **Topic Modeling System**: Used NLP to analyze customer feedback and support data
2. **Customer Segmentation Models**: Leveraged clustering techniques for targeted marketing
3. **Marketing Mix Modeling (MMM)**: Analyzed ROI across all channels (digital and traditional)
4. **Databricks Framework**: Established quality testing and model development protocols

---

## Complementary Work: Marketing Mix Modeling (MMM)

While the Markov Chain MTA model focused on user-level, digital attribution, Wecsley also developed **Marketing Mix Models** at LexisNexis to provide a holistic view:

### MTA vs. MMM: Complementary Approaches

| Aspect | Multi-Touch Attribution (MTA) | Marketing Mix Model (MMM) |
|--------|------------------------------|---------------------------|
| **Granularity** | User-level (micro) | Aggregate-level (macro) |
| **Focus** | Digital touchpoints in customer journey | All channels (digital + traditional) |
| **Data Type** | Granular, real-time clickstream data | Historical aggregate data (weekly/monthly) |
| **Use Case** | Optimize digital channel tactics | Strategic budget allocation across all channels |
| **Time Horizon** | Real-time to short-term | Long-term (annual planning) |

### Integrated Strategy

Wecsley employed both methodologies in concert:

1. **MMM for Strategic Planning**: Used to allocate budgets across all channels and identify KPIs
2. **MTA for Tactical Optimization**: Fine-tuned digital spend based on user journey insights
3. **Continuous Improvement Loop**: Validated MTA adjustments against broader MMM results

**Result**: This integrated approach ensured optimal budget allocation, continuous refinement, and higher ROI while maintaining alignment with long-term business goals.

---

## Key Competencies Demonstrated

### Technical Skills
- **Advanced Statistical Modeling**: Markov Chains, probabilistic frameworks
- **Programming**: R (primary), Python
- **Data Processing**: Large-scale historical data analysis
- **Machine Learning**: Attribution modeling, pattern recognition

### Analytical Skills
- **Customer Journey Analytics**: Multi-touchpoint analysis
- **Performance Optimization**: Budget allocation optimization
- **Data-Driven Decision Making**: Converting complex analytics into actionable insights

### Communication & Collaboration
- **Stakeholder Management**: Regular touchpoints with senior leadership
- **Data Visualization**: Power BI, R-Shiny dashboards
- **Cross-Functional Leadership**: Guided marketing, product, and customer support teams

### Business Acumen
- **ROI Optimization**: Improved returns through strategic reallocation
- **Cost Reduction**: Identified and eliminated wasteful spend
- **Strategic Thinking**: Aligned analytics with business objectives

---

## Supporting Analytics Initiatives at LexisNexis

### NLP-Based Topic Modeling System

**Objective**: Analyze unstructured customer feedback to uncover insights

**Approach**:
- Utilized **Latent Dirichlet Allocation (LDA)** for topic discovery
- Processed customer reviews, support tickets, and survey responses
- Delivered insights via **Power BI** and **R-Shiny** dashboards

**Impact**:
- Enabled Customer Support to target key issues and direct complaints to appropriate teams
- Helped Product team identify needed improvements and maintain successful products
- Supported Marketing in predicting customer issues, reducing detractors, and increasing promoters
- **12% improvement** in first-call resolution rates

### Generative AI for Customer Insights

**Innovation**: Fine-tuned **GPT models** from OpenAI ChatGPT

**Purpose**:
- Automate text-based customer insights
- Analyze and summarize feedback
- Enhance marketing strategies with AI-powered analysis

**Technical Approach**:
- Used **R-Studio** with **reticulate** package to interface with Python
- Fine-tuned **BERT-based summarization models** from Hugging Face
- Deployed via **FastAPI** with R-based API wrapper

**Results**:
- **27% improvement** in summarization accuracy
- Reduced manual review time significantly
- Automated summarization of thousands of customer feedback entries per week

### Databricks Implementation

**Objective**: Ensure data quality for model development

**Framework**:
- Data ingestion from various sources with quality checks
- Unit tests and data profiling for outliers, duplicates, and null values
- PySpark for large-scale data cleaning and transformation
- Automated pipelines for monitoring data drift

**Impact**: Ensured high-quality input data, reducing errors and improving prediction reliability

---

## Legacy & Impact

The Markov Chain-based Attribution Model developed by Wecsley Prates at LexisNexis Risk Solutions represents:

1. **Technical Innovation**: First advanced attribution model in 25 years of company history
2. **Business Value**: Significant ROI improvement and cost savings
3. **Strategic Advancement**: Shifted the company toward data-driven marketing decision-making
4. **Scalable Framework**: Established foundation for future analytics initiatives
5. **Cross-Functional Impact**: Benefited marketing, product, and customer support teams

---

## Conclusion

Wecsley Prates' development and implementation of the Markov Chain-based Multi-Touch Attribution Model at LexisNexis Risk Solutions exemplifies the powerful intersection of advanced statistical methodology, practical business application, and effective stakeholder communication. By choosing the right analytical approach, implementing it rigorously, and presenting results in actionable formats, he delivered measurable business value while advancing the company's analytical capabilities to new heights.

The project's success—marked by improved ROI, optimized budget allocation, and enhanced decision-making—demonstrates the transformative potential of sophisticated data science when applied thoughtfully to real-world business challenges.
