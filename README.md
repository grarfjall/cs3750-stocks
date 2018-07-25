# cs3750-stocks
### Requirements 

* The user should create an account (standard login/security from assignment 1). 
* The user should enter a starting amount of money.
* The user should enter stock ticket symbols for stocks to invest, minimum of 3.  (I will allow other kinds of investments, such as mutual funds, metals, or cryptocurrencies.)
* The server should supply back current cost per share of stock, and start with the assumption that the user will equally invest in all companies (assume fractional shares of stocks are allowed.)
* The investment data should be shown in a textbox or table, a pie chart, and a bar chart. 
* The user should be able to change the initial investment amounts by modifying the textboxes/table, pie chart, and the bar chart.  When one is modified, the others should reflect the change.  (If one stock is increased by $1000, two others could decrease by $500 each if there were 3 total.)
* These investment ratios can be modified later at any time (You do not have to account for adding new stocks or removing stocks if you don't want to.)
* A running history of the investment portfolio should be saved in the database.  Let the user view a historical chart/graph showing how the various stocks have performed.  This historical chart/graph should account for any times when the user modified the investment ratios.  (You shouldn't allow the user to change their past history.)

Overall, keep the application asynchronous, meaning, when data is saved, do not trigger a page refresh. 

The application must be formatted to look clean on a mobile device.

You can choose any language and database as you need.  The database needs to perform such that if the computer were rebooted, the server could load up all data again.  Data can't simply be stored perpetually only in memory.

The website needs to be publicly hosted. 

For any missing details, please ask, and I can add the details here.

I reserve the right to tweak or add new requirements, but I will try to keep these to a minimum.

---
