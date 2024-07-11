

## **INTRODUCTION**

Amazon product reviews are customer-generated evaluations of products purchased on Amazon's platform. These reviews are vital for potential buyers, offering insights into product quality, functionality, and user satisfaction. Each review typically includes a star rating (from one to five), a written comment, and photos or videos of the product in use.


## **Tools and Technologies**

In my data analysis project, I thoroughly cleaned the dataset by handling missing values, removing duplicates, converting data types, addressing outliers, and standardizing or normalizing values. I wrote functions to automate these tasks, ensuring consistency and efficiency.
For data visualization, I used Seaborn and Matplotlib.pyplot to create various plots such as histograms, scatter plots, and heatmaps. These visualizations helped me understand data distributions, relationships, and trends, making it easier to derive insights and present findings clearly.

## **Problem Statement**

1. Which category of the product does Amazon have the most?

2. How does the discount percentage affect the rating of a product?

3. Which category has the highest average rating?

4. Is there a correlation between the product’s price and its ratings?

5. What is the distribution of ratings across all products?

6. Is there a correlation between the length of review and the rating given?

7. Can the length of the product description be correlated to the product’s rating?

## **Inferences**

1. The top 3 listed categories of Amazon are Electronics(525),Computers&Accessories(453) and Home&Kitchen(448).

2. From the above plot, we can conclude that people rate mostly between 3.5 and 4.5 no matter what discount is given.

3. Office Products  has the highest average rating with 4.309677 followed by Toys&Games 4.300000.

4. Yes, there is a positive correlation between actual_price and rating but it is poorly correlated (0.11)

5. The distribution of ratings across all products is between 3.5 to 4.5
  
6. There is a negative correlation between the length of review and the rating given(-0.044).

7. There is a positive correlation between the length of product description and product's rating but it is poorly correlated(0.013).
