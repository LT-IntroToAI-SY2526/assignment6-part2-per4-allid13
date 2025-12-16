# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important:  Square feet
2. Bathrooms
3. Bedrooms
4. Least Important: Age

**Explanation:**
Square feet is the most important for developing house price model 




---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:** Age
The model demonstrates that the older a house is, the cheaper that house will be by around a couple thousand dollars.



**Feature 2:** Square Feet
 It depends how many square feet a house is to determine to average price of the house, the more square feet a house has, the more expensive it’s going to be


---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
My models R² score is .9936 which rounds up to 1 and this means that my model accurately predicts house prices. Yes, there can be improvments because my root mean sqaured error is $4477.89.
---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Loacation/Area

**Why it would help:**
 If the house is surrounded by a lot of stores, commuter transportation, and a walkable neighborhood,  it will most likely be more expensive than those who aren’t in such nice neighborhoods.


**Feature 2:**
Backyard

**Why it would help:**
 If the backyard is spacious, then it will allow for more additional things to add to the house like a playground, a pool and it will probably cost more than a house with a small backyard.


---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
 I would somewhat trust this model to predict the price of that house because the highest amount of square feet that was in the dataset was 2500 sqft (close to 3000 sqft) and had one less bedroom and bathroom than the house of the prediction so I think that the prediction would be somewhat accurate but I’m not sure how accurate especially since the amount of years differs by quite a lot. 

