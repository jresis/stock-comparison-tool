# Stock Comparison Tool

## Introduction
For this project, I observed statistics from 2017-2022 for three stocks and the overall S&P 500. The data was obtained from Yahoo Finance. The main goal is to set up a way to compare stocks' performance and give potential investors an idea as to the long-term profitability and volatility of stocks. While in this project, I selected three stocks to observe, this analysis can be used with any stock, as the stock ticker is all that is needed to pull information in this notebook.


## Analysis
I started by observing the graphs of the past five years for the stocks in question to give the user an idea of the stocks' recent trends.

![Screen Shot 2022-10-04 at 12 18 07 PM](https://user-images.githubusercontent.com/29186496/193872242-30dc1c14-2ade-40f3-9eeb-639f7fb7ac7d.png)
![Screen Shot 2022-10-04 at 12 18 33 PM](https://user-images.githubusercontent.com/29186496/193872255-8566cd31-9c98-49f2-9d39-6183503c0054.png)
![Screen Shot 2022-10-04 at 12 18 25 PM](https://user-images.githubusercontent.com/29186496/193872267-142b4d46-fff4-4739-8515-6a5ee11ce512.png)

It is worth noting that the date range can be adjusted, but I figured that five years would be an appropriate default setting, as it gives a large sample size but excludes old data that is less relevant.

Then, we can pull some statistics by using the Describe method. Here is an example:
![Screen Shot 2022-10-04 at 1 25 02 PM](https://user-images.githubusercontent.com/29186496/193885775-d2e61609-872e-45a5-bac9-68da0d4af918.png)
Here, we are observing data from LLY (Eli Lilly). The mean closing price of the stock for the five-year time frame was about $165, and the standard deviation was about $72. To make comparisons easier, the volatility index I assigned to this would be about 72/165. I divided the standard deviation by the mean because if we just take the raw standard deviation, then expensive stocks would usually appear to be unusually volatile (a 20% change in a stock that was originally $10 is much less than a 20% change in a stock that was originally $500, for example).

LLY's volatility index of about .44 is significantly higher than the S&P 500's volatility index of .20. As a result, investors who are risk-averse may not be as inclined to invest. However, LLY's annual return is incredibly high, averaging over 56% per year since the beginning of the time frame. In addition, LLY was among the few stocks that did not see a sizable drop near the beginning of the Covid-19 era. Overall, despite the large volatility index, LLY has a lot going for it.

## Takeaways

## Future Work
