# Conversion Rate Optimization (CRO) Data Analysis Project

This project analyzes landing page performance data to identify conversion bottlenecks and suggest evidence-based A/B test hypotheses. The analysis includes data exploration, visualization, statistical tests, and practical UX/CRO recommendations based on real user behavior.

---

## Project Structure

- **/notebooks/** — Main Jupyter Notebook with all code, charts, and analysis  
- **/data/** — Source datasets (traffic/behavioral data in CSV or Excel format)  
- **/images/** — Screenshots of the landing page and key visualization outputs  
- **README.md** — Project description and instructions

---

## Main Objectives

- Review and summarize user traffic and behavior metrics  
- Identify key underperforming segments and conversion drop-off points  
- Test for statistically significant differences in form submission rates by traffic source  
- Visualize scroll depth, bounce rate, and CTA interactions for different devices and segments  
- Recommend actionable UX and CRO improvements, including specific A/B test scenarios  

---

## Data Overview

The dataset includes:  
- Traffic source (Email, Meta Ads, Organic)  
- Device type (Mobile, Desktop)  
- Session-level metrics: time on page, scroll depth, bounce rate  
- User actions: CTA clicked, form submitted  

---

## Key Results

- Email and Organic channels had higher form submission rates than Meta Ads  
- Users who clicked CTA spent more time on the page across all sources  
- On mobile, higher scroll depth correlated with lower bounce rate (r ≈ -0.89)  
- ANOVA confirmed statistically significant differences in conversion between traffic sources  

---

## Proposed Experiments

- Move CTA button to the right side and increase size for desktop users (A/B test)  
- Simplify the home page and reduce the number of informational blocks before pricing (A/B or hybrid test)  
- Combine both changes to test for potential synergistic effects  

---

## How to Run

1. Open the notebook in Jupyter or Google Colab  
2. Place the provided data file in the `/data` directory  
3. Run cells sequentially to reproduce all charts and statistical tests  

---

## Requirements

- Python 3.x  
- pandas, numpy, seaborn, matplotlib, scipy  

---

## Authors & Attribution

Analysis and code by [Your Name]. Landing page screenshots and design elements are for educational and testing purposes only.

---

> This project analyzes website user data to find key factors impacting conversion rates and provides recommendations for A/B testing and CRO based on data-driven insights.

