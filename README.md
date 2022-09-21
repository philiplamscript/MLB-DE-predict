# MLB-DEn-predict


![image](https://user-images.githubusercontent.com/74084724/134948391-941cf203-7c1b-4555-a59c-40623e951f04.png)

Competition link: https://www.kaggle.com/c/mlb-player-digital-engagement-forecasting

Here is the Code on project, where:

**mlb-explorer.ipynb:**

pre modeling researching, focus on 
1) Targets basic stat or infomation, for example: correlation, distribution, time series ACF/PACF trend,
2) Targets distribution with some key features, like player status, have competition on the day.

**model-tune-train-model-and-data-export.ipynb**

Data clean, selection to training data, feature variable building, modeling stepup.
Build the final model which will apply in **mlb-trained-model-submission.ipynb**.

P.S. non-runned code after model trained can be igorne, which is further study on parameter and features.

**mlb-trained-model-submission.ipynb**

Code on applying to future application data as a final source in competition.
