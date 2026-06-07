# LLM_price_performance_analysis

#### Overview
Exploratory data analysis on a dataset of 454+ large language models (LLMs) sourced from Kaggle. The project investigates whether expensive AI models are always smarter, how speed relates to cost, and which providers offer the best value.

#### Goals
- Analyze the relationship between model price and intelligence score
- Explore the speed vs. cost tradeoff across models
- Compare pricing distributions across providers (OpenAI, Anthropic, Google, open source)
- Understand the overall distribution of model performance in the current AI market

#### Key Findings
- Price and intelligence have a positive but imperfect correlation — several mid-range models ($0.50–$2.00/M tokens) achieve near-frontier intelligence scores
- Open source models (LLaMA, Mistral) have closed the performance gap significantly while remaining near zero cost
- A negative correlation exists between price and speed — more expensive models tend to be slower due to heavier computation
- Intelligence scores follow a roughly normal distribution centered around 75–80, with only a few premium models exceeding 90

#### Tools & Libraries
`Python` `Pandas` `Matplotlib` `Seaborn` `Jupyter Notebook`

#### Visualizations
- Scatter plot — Price vs. Intelligence Score (colored by provider)
- Correlation heatmap — relationships between all numeric features
- Histogram — distribution of intelligence scores across all models
- Box plot — price range comparison across providers

---





