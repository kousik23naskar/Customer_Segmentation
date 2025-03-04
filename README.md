<h1 align="center">📊 Customer Segmentation using K-means Clustering</h1> 
<p align="center">
  <img src="images/Customer_Segmentation.jpg" alt="Customer Segmentation" width="600"/>
</p>
<p>
Welcome to the Customer Segmentation project! This repository contains code and resources for segmenting customers based on their annual income and spending scores using the K-means clustering algorithm. The goal is to group customers into distinct segments to help businesses target specific customer groups more effectively. 
</p>

## Project Overview 💡
This project leverages **K-means clustering** to categorize customers into distinct segments based on their annual income and spending behavior. The system analyzes customer data to identify patterns and creates actionable insights for businesses.

## Tech Stack Used 🛠️
- **Python**
- **numpy**
- **pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn (KMeans)**

## Dataset 📊
The system works with customer data, focusing primarily on:

- **CustomerID**
- **Gender**
- **Age**
- **Annual Income (in $)**
- **Spending Score (1-100)**

The data undergoes exploratory data analysis (EDA) and clustering to determine customer behavior.

## System Functionality 🧑🏻‍💻
The Customer Segmentation system features:

- **Data Cleaning & Exploration:** Identify and handle inconsistencies in the dataset.
- **Visualization:** Visualize the distribution of various features like Gender, Age, Annual Income, and Spending Scores.
- **K-means Clustering:** Apply K-means clustering to segment customers into different groups based on annual income and spending scores.
- **Cluster Analysis:** Identify the characteristics of each customer segment, helping businesses understand their target groups.

## Usage 💪🏻
To run the project locally, follow these steps:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/kousik23naskar/Customer_Segmentation.git
   ```
2. **Navigate to the project directory:**
  ```bash
  cd Customer_Segmentation
  ```
3. **Create a conda environment:**
  ```bash
  conda create -p venv python=3.11 -y
  ```
4. **Activate the environment:**
  ```bash
  conda activate ./venv
  ```
5. **Install the necessary dependencies:**
  ```bash
  pip install -r requirements.txt
  ```
6. **Execute the code inside Customer_Segmentation.ipynb**
7. **Visualize Results:** The script will generate visualizations to display the customer segments created through K-means clustering.

## Evaluation 📈
The effectiveness of this segmentation can be evaluated based on how well the identified clusters align with customer behavior and business objectives. The clustering results allow businesses to target specific customer segments for marketing strategies.

## Results and Discussion 📊
In this section, we discuss the segmentation outcomes:

- **Clusters Created**

  - **Cluster Orange - Balanced Customers:** Low income and low spending. These customers are frugal and unlikely to be targeted by businesses but can be loyal shoppers.
  - **Cluster Blue - Pinch Penny Customers:** High income but low spending. These are potential targets for businesses looking to improve customer satisfaction and engagement.
  - **Cluster Purple - Normal Customers:** Average income and spending. They represent the typical customer but may not be the primary focus for high-target strategies.
  - **Cluster Red - Spenders:** Low income but high spending. These customers spend more than expected, possibly due to high satisfaction or need. They could be treated as potential target customers.
  - **Cluster Green - Target Customers:** High income and high spending. These are the ideal customers for businesses, contributing the most to profits and loyalty.
  
- **Strengths:**

  - **Effective Segmentation:** The K-means clustering provides clear and actionable customer segments based on income and spending behavior.
  - **Clear Visualizations:** The use of bar plots, pie charts, scatter plots, and box plots makes the data easy to understand and analyze.
  - **Actionable Insights:** Each cluster provides a distinct customer profile, which businesses can use to tailor marketing and service strategies.
  
- **Limitations:**

  - **Sensitivity to Initial Conditions:** K-means clustering can be sensitive to initial cluster centroids, and results may vary with different initializations.
  - **Assumption of Spherical Clusters:** K-means assumes that clusters are spherical, which may not always align with real-world data.
  
- **Potential Areas of Improvement:**

  - **Advanced Clustering Algorithms:** Exploring algorithms like DBSCAN or hierarchical clustering to handle complex data distributions.
  - **Incorporating More Features:** Adding other customer attributes like purchase history or location could further refine the segmentation.

## Contributing 🤝
We welcome contributions to improve and expand this project! If you have suggestions, bug fixes, or new features to add, please submit a pull request.

## License 🔐
This project is licensed under the [MIT License](LICENSE).

## Contact 📩
For any questions or inquiries, feel free to reach out to us:
- **Email:** kousik23naskar@gmail.com
- **LinkedIn:** [Kousik Naskar](https://www.linkedin.com/in/dr-kousik-naskar/)

Let’s work together to enhance customer targeting strategies!

Thank you for visiting our project repository. Happy analyzing! 😇
