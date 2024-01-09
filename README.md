 # Data Scientist Capstone Project: Optimizing App Offers with Starbucks
<img width="2000" alt="Storefront_Resized" src="https://github.com/AlJawharhALOtaibi/Optimizing-App-Offers-with-Starbucks/assets/87391133/7562565c-d54e-4ab8-a8bf-50aaeecf0a3e">

## Introduction
In the evolving landscape of customer engagement, businesses grapple with ensuring that their offers effectively target the intended audience. This project delves into the intricate challenge of addressing the issue of sending offers to customers who, despite completing associated tasks, did not view the offers. This article aims to reveal our analysis outcomes, focusing on mitigating the impact of "unnecessary offers."

## Significance of the Study
The essence lies in understanding the repercussions. Starbucks, akin to many companies, incentivizes customers for completing offers. However, a significant concern arises when customers, oblivious to the offer, fulfill its requirements, resulting in unforeseen losses for the company. This analysis aims to confront this challenge by examining the revenue magnitude lost due to "unnecessary offers" and identifying traits of customers frequently completing offers without viewing them.

## Key Questions Guiding the Exploration
1. How much revenue is lost due to "unnecessary offers"?
2. What are the characteristics of customers frequently completing offers without viewing them?
3. How does income vary across different customer segments?

## Requirements
The analysis relies on several libraries:
- pandas
- numpy
- seaborn
- json
- tqdm
- pandasql

Install these libraries by running the following command in your terminal or Jupyter notebook:
```bash
pip install pandas numpy matplotlib seaborn json tqdm pandasql
```
After installing the libraries, open the Jupyter notebook to proceed with the analysis.

## Dataset Description
The dataset encompasses three pivotal components:
- **Customer Demographics**: Includes customer characteristics like age, gender, income, and potentially other demographic details, crucial for segmenting and targeting strategies.
- **Offer Interactions**: Contains offer-related data, such as offer types, channels of receipt, and customer responses (viewed, completed, or ignored), aiding in understanding customer behaviors.
- **Transaction Data**: Unfortunately not publicly available due to size constraints; it provides insights into customer purchasing behavior and its correlation with offer engagement.

## Analysis
The analysis was conducted using a Jupyter Notebook (Data_Scientist_Capstone_Project.ipynb) and documented in a Medium article.

## Key Findings
- Unnecessary offers potentially contribute to an annual revenue loss of $588,384.
- Females exhibit higher spending per transaction ($16.3) than males ($10.4) and are more likely to complete offers without viewing.
- Customers completing offers without viewing tend to have higher average incomes, especially concerning discount offers.

## Recommendations
- Strategically target offers:
  - Reassess the distribution of BOGO offers.
  - Adjust offer distribution for females, especially discount offers.
  - Customize offer difficulty based on individual customer income levels.

## Further Research
- Explore additional customer characteristics influencing offer completion behavior.
- Develop predictive models for optimizing offer targeting.
- Evaluate the impact of offers on customer satisfaction and loyalty.

## Resources
- Medium Article: https://medium.com/@aljawharhalotaibi/optimizing-offer-targeting-a-data-driven-exploration-into-revenue-loss-and-customer-behavior-ef7057f68ed9
- Jupyter Notebook: Data_Scientist_Capstone_Project.ipynb
