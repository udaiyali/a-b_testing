# udacity-a-b-test
A/B tests are very commonly performed by data analysts and data scientists. It can help us make a better decision.

For this project, you will be working to understand the results of an A/B test run by an e-commerce website. Your goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

PROJECT SPECIFICATION Analyze A/B Test Results

The project is divided into three parts which is given as below. 

**Part I - Probability**

**Findings** From the findings (you can see the results in the .html file), we cannot make a sound decision as teh converstion rate for contorl group sits at 0.12 and that of treatment is at 0.11. We can see that the difference is marginal and this can't be a sufficent evidence. But inorder to find this we further do the other tests to determine the results. The answer is no. We don't have sufficient evidence.

**Part II - A/B Test**

**Hypothesis**

𝐻0:𝑝𝑛𝑒𝑤≤𝑝𝑜𝑙𝑑
 
𝐻1:𝑝𝑛𝑒𝑤>𝑝𝑜𝑙𝑑

**Finding**

1) Here, we find the P value to be large large. Hence we fail to reject the Null hypothesis and keep the old page.

2) From the results we see that the z_score is ess that 1.64. In this situation also we fail to reject the null. Hence this result    is consisten with the results in part J and K.

**Part III - A regression approach (Logistic)**


**Finding**

It is evident from the results that there is not much impact of countries and page on conversion rates.
