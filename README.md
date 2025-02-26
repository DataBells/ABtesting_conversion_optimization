🚀 **Introducing the Ultimate A/B Testing and Experiment Analysis Dataset!** 👀
<br>

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F23961675%2Ff3761bd2d7ee460ad464de8f25634f63%2Fsteve-johnson-z6LlNgsDeug-unsplash.jpg?generation=1740481184467263&alt=media)

Are you ready to dive into some **high-impact A/B testing** and **conversion optimization**? 📊 If you're working on **data science, marketing analytics**, or just love exploring **real-world business concepts**, this **dataset** is **perfect for you**!

🔍 **What’s Inside?**
- **30,000+ sessions** with detailed user behavior: time spent, pages visited, and more!
- **Demographic breakdown**: Age, gender, location, and device usage.
- **Conversion data**: Sign-ups, purchases, and revenue generation from different landing page designs (Vibrant, Cold, Heat).
- **Engagement insights**: Understand how factors like device type, session duration, and traffic source affect conversions.

📈 **Why Should You Use This Dataset?**
- Perfect for performing **A/B testing**, analyzing **conversion rates**, and exploring **user segmentation**.
- Explore **multivariate analysis**, **hypothesis testing**, and **statistical significance** for **simulated business** insights.
- **Practical application**: Ideal for **learning, experimentation**, or creating models that improve **sales and marketing performance**.

🌟It mirrors real-world scenarios to help you practice and enhance your skills. Whether you’re a beginner or an expert, this dataset will help you understand conversion analysis, optimization, and marketing strategies with **data you can trust for learning**. 💥

🔗 **Ready to get started?** Check out the dataset now and join the discussion! 💬 Let’s explore the **secrets behind successful conversions** together. 🚀

https://www.kaggle.com/datasets/sandeep1080/bassburst/data   <br>

## Column Descriptors:


| Column Name             | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `user_id`               | Unique identifier for each visitor.                                         |
| `session_id`            | Unique identifier for each session or visit.                                |
| `sign_in`               | Indicates if the user logged in via email or used guest access.             |
| `name`                  | Name of the visitor (generated from multiple locales).                      |
| `demographic_age`       | Age of the visitor (ranging from 14 to 80).                                 |
| `demographic_age_group` | Age group of the visitor: "Teenage", "Adult", "Old".                        |
| `demographic_gender`    | Gender of the visitor (Male, Female, Not Answered).                         |
| `email`                 | Email address of the user (if logged in via email).                         |
| `location`              | The city where the visitor is located.                                      |
| `country`               | Country corresponding to the location.                                      |
| `device_type`           | Type of device used (Mobile, Desktop, Tablet).                              |
| `timestamp`             | Session start time.                                                         |
| `variant_group`         | The landing page design variant the user saw (Vibrant, Cold, Heat).         |
| `time_spent`            | Total time (in minutes) the user spent on the landing page.                 |
| `pages_visited`         | Number of pages the user viewed during the session.                         |
| `conversion_flag`       | Binary flag (0/1) indicating whether the user converted (signed up or made a purchase). |
| `conversion_type`       | Type of conversion achieved (Signup or Purchase).                           |
| `traffic_source`        | Source of traffic (Organic, Paid, Social, Referral).                        |
| `product_purchased`     | List of products purchased (if applicable).                                 |
| `revenue`               | Total revenue generated from the transaction (if purchase was made).        |
| `payment_type`          | Payment method used (Card or COD).                                          |
| `card_type`             | Card type if payment was made by card (Amex, Visa, Master).                 |
| `coupon_applied`        | Whether a coupon was applied (Yes/No).                                      |
| `bounce_flag`           | Indicates if the session was a bounce (only one page visited).              |

<br>

## Algorithms/Models Used & Libraries Required:

### **Algorithms/Models Used**

| Algorithm/Model        | Description                                               |
|------------------------|-----------------------------------------------------------|
| **A/B Testing**         | Used for comparing landing page variants and determining the most effective design. |
| **Logistic Regression** | For analyzing the relationship between various factors (e.g., time spent, pages visited) and conversion outcomes. |
| **T-Test**              | Used to compare the means of time spent and pages visited between converters and non-converters. |
| **ANOVA**               | Used to compare pages visited across different demographic age groups. |
| **Chi-Square Test**     | Used to evaluate the association between categorical variables such as sign-in type and conversion outcomes. |
| **Kaplan-Meier Estimator** | For survival analysis, to estimate time-to-conversion. |
| **Sequential Testing**  | Monitoring conversion rates over time with cumulative Z-tests. |
| **Bayesian Methods**    | Posterior distribution analysis for conversion rates. |
| **Multi-Armed Bandits**| Thompson Sampling for dynamically selecting the best-performing landing page variant. |

### **Libraries Required**

| Library                    | Purpose                                                   |
|----------------------------|-----------------------------------------------------------|
| **Pandas**                  | For data manipulation and handling.                      |
| **NumPy**                   | For numerical operations and array manipulation.         |
| **Matplotlib/Seaborn**      | For data visualization (plots and graphs).               |
| **Statsmodels**             | For statistical models and hypothesis testing.           |
| **Scipy**                   | For statistical tests like T-tests and Chi-Square.       |
| **Lifelines**               | For survival analysis (Kaplan-Meier).                    |
| **Plotly**                  | For interactive visualizations.                          |
| **Statsmodels.formula.api** | For fitting logistic regression models using formulas.   |
| **Statsmodels.stats.proportion** | For calculating proportions and effect sizes. |
| **Warnings**                | For suppressing unnecessary warnings during analysis.    |


# Business Questions

Throughout the analysis, we addressed **23 key business questions** that helped us uncover actionable insights for optimizing the landing pages and user experience. These questions were centered around understanding:

1. **User Engagement**: How are users interacting with the website?
2. **Conversion Metrics**: Which landing page variant and user behaviors are driving conversions?
3. **Demographics Impact**: How do age, gender, location, and device type influence conversion rates?
4. **Marketing Strategy**: Which traffic sources (organic, paid, referral) perform best?
5. **Revenue Analysis**: How does session behavior impact revenue generation and average order value?
6. **User Segmentation**: What are the behaviors of first-time visitors vs. returning users?
7. **Time & Session Metrics**: What is the impact of time spent and pages visited on conversions?

---

# How We Analyzed the Questions

Each of these business questions was analyzed using various statistical methods and techniques:

- **Exploratory Data Analysis (EDA)**: To understand the distribution of data, conversion rates, and behavior across different segments (age, gender, device type).
- **A/B Testing**: To compare landing page variants and determine the most effective one in terms of conversion rates.
- **Hypothesis Testing**: Employed tests like two-proportion z-tests, T-tests, ANOVA, and chi-square tests to assess statistical significance.
- **Regression Analysis**: Used logistic regression to analyze the relationship between user behaviors (time spent, pages visited) and conversion rates.
- **Multivariate Testing**: To account for multiple factors affecting conversions, including demographic and engagement variables.
- **Bayesian Methods & Multi-Armed Bandits**: To dynamically evaluate which landing page variant performs best over time.
- **Sequential Testing**: Analyzed conversion rates as sample sizes increased to ensure stable and reliable results.

---

# Follow the Code

To see the full analysis, experiment with different questions, and explore how each metric impacts business performance, you can find the code in the following links:

- **Kaggle Dataset**: [Kaggle Link](https://www.kaggle.com/datasets/sandeep1080/bassburst/data)
- **Kaggle Code**: [Kaggle Link](https://www.kaggle.com/code/sandeep1080/a-b-testing-conversion-insights-for-sales)

<br>
🤝Thank you!

