# Hannah Lyden Data Science and Analytics Portfolio
I’m a quantitative social scientist and data scientist focused on measurement validity, behavioral modeling, and applied machine learning systems. My work spans experimental design, survey methodology, LLM evaluation, and production-style deployment, with an emphasis on translating statistical insight into scalable, real-world decision systems.

## Core Tools & Methods
**Languages & Frameworks:** Python, FastAPI, scikit-learn, pandas, NumPy, OpenAI API  
**Modeling:** Logistic & linear regression, clustering, topic modeling (LDA), experimental analysis  
**Evaluation:** Confusion matrices, error auditing, demographic bias analysis  
**Engineering Practices:** Environment-based configuration, batch processing, modular pipelines  


## Project #1: Myntra Price and Discount Analysis (https://github.com/hannahlyden/Myntra_Analysis)
This project analyzes product listings from Myntra, a leading online fashion retailer, to explore how brands compete through pricing strategies and discounting practices. The analysis combines data wrangling, analysis, and visualization to reveal patterns in how sellers position themselves on the platform.

## Project #2: Evaluating LLMs for Automated Coding of Public Opinion Survey Responses (https://github.com/hannahlyden/anes_llm_content_analysis)
This project evaluates whether large language models can reliably automate the coding of open-ended responses in the American National Election Studies 2024 Time Series Survey, comparing LLM classifications to human-coded “gold standard” labels across 10 policy categories. Using accuracy metrics, confusion matrices, qualitative audits, and logistic regression analyses of demographic patterns, I assess model performance, error structure, and the substantive validity and behavioral sensitivity of LLM-coded outputs in public opinion research. The project demonstrates how LLM outputs must be evaluated not just for accuracy, but for behavioral and demographic sensitivity before being integrated into social science workflows.

## Project #3: Deploying LLMs for Automated Survey Coding: A FastAPI Service (https://github.com/hannahlyden/anes_llm_api)
This project is a production-style FastAPI service that classifies open-ended responses from the American National Election Studies into policy issue categories using OpenAI’s GPT-4.1-mini model, supporting both single and batch inference endpoints. It showcases end-to-end LLM integration—including structured prompting, JSON parsing with Markdown cleanup, robust error handling, and environment-based configuration, designed to demonstrate scalable, API-driven deployment of automated survey coding.

## Project #4: The Behavioral Impact of Uncertainty Displays: An Experimental Analysis of Decision Quality and Speed (https://github.com/hannahlyden/decision-uncertainty-ab-test)
This project evaluates how displaying uncertainty in a simulated A/B testing environment influences choice behavior, decision accuracy, and deliberation time. Using logistic and linear regression models, I show that uncertainty cues increase decision time and behavioral consistency without meaningfully altering accuracy, highlighting a tradeoff between cognitive effort and speed in decision-support system design.

## Project #5: Conversational Customer Segmentation & Action Engine: From Support Transcripts to Operational Strategy (https://github.com/hannahlyden/converstational_customer_segmentation)
This project builds an end-to-end enterprise-style pipeline that transforms synthetic customer support conversations into engineered behavioral features, applies K-means clustering for customer segmentation, and translates those segments into an auditable “action engine” for operational decision-making. By separating data modeling, unsupervised learning, and business rules, and using an LLM strictly as a post-analytic communication layer, the system demonstrates scalable, explainable AI workflows aligned with real-world customer experience platforms.

## Project #6: Social Media Engagement & Narrative Dynamics: A Reddit Analysis of The Real Housewives of Beverly Hills (https://github.com/hannahlyden/rhobh-audience-analysis)
This project analyzes 2,089 live-episode Reddit comments from The Real Housewives of Beverly Hills Season 14 to evaluate cast popularity, engagement drivers, and evolving discussion themes using regression modeling, composite scoring, and LDA topic modeling. Results show that structural features (thread depth and timing) predict engagement more than sentiment, and that discussion volume reflects narrative centrality and controversy, not audience approval, highlighting the importance of data scoping and platform context in social media analytics.

### What This Portfolio Demonstrates
- Rigorous evaluation of model performance beyond surface-level accuracy  
- Behavioral sensitivity and demographic validity checks  
- End-to-end ML system design from raw data to deployable services  
- Translation of analytical output into operational decision frameworks  
