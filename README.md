100 days of code - Python3.9

Day 36 - Stock Alert

This application checks a stock's (currently set to Tesla) closing market price of the previous day. It then compares the price to the closing price of the day before. If the difference is greater than 5, it will go to the news api to search for the top 3 headlines concerning the stock. Then using the twilio API will send an sms to alert the user.

For info on the variables/keys required, see the .envexample

Highlights: APIs
