# Swire_Capstone
A time series analysis of product demand for future releases

**Business Problem (as team presented):**  
  Swire is set to introduce a range of innovative products and requests a reliable forecast model to predict the demand for each. The overall objective is to leverage historical data for similar products to forecast the demand for the new flavors at specific locations within a 13-week range. Additionally, the incorporation of relevant census data is critical to derive insightful business conclusions, such as identifying ideal locations or demographics for the different products based on prior sales. The approach to this project can be broad, encompassing a demand forecast for each innovation product, or in-depth, focusing on a select few products while considering factors like seasonality, trends, and other influencers. Success will be measured by the accuracy of the demand forecasts and the ability to provide actionable insights for strategic decision-making. The project scope includes the execution of the forecast model by the data science team to be presented upon completion, with the potential for additional enhancements in the future.

  Benefiting from a reliable forecast model, Swire aims to make data-driven decisions for the introduction of its new products, optimizing inventory management, and ensuring customer satisfaction. Stakeholders will judge the success of the project based on the accuracy of demand forecasts and the resulting actionable insights. The analytics approach will focus on the utilization of historical and census data to construct a robust forecast model, enabling informed decision-making for product introduction and market positioning. Potentially, additional market factors will be evaluated to achieve a deeper understanding of sales data. The project scope includes the execution of the forecast model with flexibility for potential enhancements based on project milestones and evolving business requirements.

**Group's Solution**  
  We decided to look at the problem from each question as a combined problem. We tried multiple model types, including ARIMA, Regression, and XGBoost. Ultimately, XGBoost gave us teh best results and teh fewest headaches. I touch more on these issues in a section below. WIth the results we receiveed from the XGBoost model, we were able to get results to the questions posed. Ultimately, they were not as accurate as we would have liked, mostly down to the way we split the data for training and testing. I took the time to bring in other, external, data that didn't work out due to the fact that we couldn't tell which locatio nwas a gas station, rendering the gas prices that were collected unusable. 

  When attacking the questions, we noticed that many of the requested parameters were not being accounted for in our model. I mistakenly went down a different route to try and solve the problem without rebuilding the model. This took up valuable time, and in hindsight, I probably should have gone back before submitting the model portion and redone the entire model. I partially did that afterwards, this code is in the TimeSeriesSplit notebook attached to this repository. 

  Ultimately, we didn't achieve what we had set out to do. We did get working models in place, though they were not accurate enough to use effectively to answer the questions posed to us. The majority of the issues stemmed from the splitting of data and not paring down the dataset to a more manageable size. IT was an oversight that 

**My Contribution**  
  My main contributions to the project were centered around the modeling and building of the final presentation. I worked on both an ARIMA model that didn't go anywhere and the XGBoost model that we ended up using. The ARIMA model was a problem for me because of the size of the data. I was obstinate in getting it to run properly, to my own detriment. After running it to no satisfactory conclusion in Databricks, I decided to shelve it and focus on the XGBoost model. The failure did cause a bit of concern on my part.  
  After completing the XGBoost model, and receiving what looked like promising metric scores, the next step was the questions. I worked on 3 of the questions posed, and saw some concerns with the data as it was after testing completed. I got into a bit of tunnel vision with these and was not able to get satisfactory responses. Again, lesson learned.
  The final portion that I worked on was the PowerPoint presentation. I designed and put together the main components of the presentation, then we as a team fine tuned it for the final result. Overall, I am happy with the visuals and our oral presentation. 

**Business Value**  


**Difficulties Faced**  


**Lessons Learned**  
