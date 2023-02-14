# forecasting_net_prophet

Analysing Mercado Libre's financial and user data in clever ways to help the company grow.

**hvPlot to visualize the data for May 2020**
![Alt text](Images/image_1_may_2020_data.png)

**Question:** Did the Google search traffic increase during the month that MercadoLibre released its financial results?

**Answer:** Yes, the Google search traffic increased from an overall monthly median value of 51 to 54 in May 2020 - the month that MercadoLibre released its financial results.

**Average traffic by the day of week**
![Alt text](Images/image_2_group_hourly.png)

**hvPlot to visualize the hour of the day and day of week search traffic as a heatmap**
![Alt text](Images/image_3_traffic_heatmap.png)

**Question:** Does any day-of-week effect that you observe concentrate in just a few hours of that day?

**Answer:** Based on the heatmap, it appears that search traffic is highest during 11pm to midnight on weekends and from 11pm to 1am on all weekdays except Friday.

**Average traffic by the week of the year**
![Alt text](Images/image_4_traffic_hvplot.png)

**Question:** Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?

**Answer:** The traffic tends to increase during the winter holiday period. However, it initially dips in weeks 40 and 41 before increasing.

**hvPlot to visualize the closing price of the df_mercado_stock DataFrame**
![Alt text](Images/image_5_stock_price_hvplot.png)

**hvPlot to visualize the close and search trends data for first half of 2020**
![Alt text](Images/image_6_2020_1st_half_close%20price_hvplot.png)

![Alt text](Images/image_7_2020_1st_half_search_trends_hvplot.png)

**Question:** Do both time series indicate a common trend that’s consistent with this narrative?

**Answer:** Subsequent to COVID-19 being declared a pandemic by WHO in March 2020, the stock price and search declined dramatically. Both, the stock price and search, gradually picked up around April 2020 and then consistently went up.

**hvPlot to visualize the stock volatility**
![Alt text](Images/image_8_stock_volatility.png)

**Question:** Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?

**Answer:** There does not appear to be a predictable relationship between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns.

**use **hvPlot to visualize the yhat, yhat_lower, and yhat_upper columns over the last 2000 hours**
![Alt text](Images/image_9_forecast_hvplot.png)

**hvPlot to visualize the daily sales figures**
![Alt text](Images/image_10_mercado_sales_hvplot.png)