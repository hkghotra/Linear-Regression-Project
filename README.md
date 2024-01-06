# Linear-Regression-Project

## Project Objective

A company in New York City specializes in selling clothing online and offers in-store style and clothing advice sessions. Their customer journey involves visiting the store, having sessions with personal stylists, and later ordering clothes through a mobile app or the website. This project aims to determine whether the company should prioritize the mobile app or the website based on customer behaviour and spending patterns. By leveraging data analysis and a linear regression model, the goal is to identify which platform has a stronger association with higher yearly customer spending.

## Data Overview

The dataset used for this project is sourced from the Ecommerce company and is provided in the form of a CSV file. The dataset includes customer information such as Email, Address, and Avatar color. Additionally, it comprises numerical columns that capture various aspects of customer engagement:

* Avg. Session Length: Average duration of in-store style advice sessions.
* Time on App: Average time spent on the mobile app in minutes.
* Time on Website: Average time spent on the website in minutes.
* Length of Membership: Number of years the customer has been a member.
* Yearly Amount Spent: Total amount spent by the customer annually.

## Results

Holding all other features fixed, a 1 unit increase in:
- **Avg. Session Length** is associated with an **increase of 25.98 total dollars spent**.
- **Time on App** is associated with an **increase of 38.59 total dollars spent**.
- **Time on Website** is associated with an **increase of 0.19 total dollars spent**.
- **Length of Membership** is associated with an **increase of 61.27 total dollars spent**.
  
## Conclusions and Insights

- The time customers spend on the app has a greater impact on dollars spent compared to the time spent on the website
- The length of membership has the most significant positive impact, indicating that customer loyalty (measured by the length of membership) strongly correlates with higher spending
- The impact of the average session length in the store also contributes positively to the total dollars spent, but to a lesser extent compared to app usage and membership length

**Is the website or the app showing a stronger performance in terms of Revenue?**

If the goal is to increase revenue, the company should consider strategies to enhance the mobile app experience, as it seems to have a stronger association with higher spending. They could also aim to develop the Website to catch up to the performance of the mobile app. Additionally, maintaining and improving customer loyalty could be a key factor in driving revenue.

## Libraries Used

pandas, numpy, matplotlib, seaborn, scikit-learn
