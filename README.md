# Stocks_Portfolio_Dashboard

I created this program for a friend who was maintaining his financial portfolio on Excel. The two main goals were to automate the addition of up-to-date information from Yahoo Finance to the workbook and to visualise the information on the workbook on a dashboard. This saved him more than 85% of the time he would spend daily manually updating the workbook and it also increased the accuracy of the information added to workbook.

#Setup
Call the functions create_book, initial_stock_tickers, and add_data_to_portfolio simultaneously and in that order. This results in the workbook created in the format that would allow this programme to add and read data. 

## excel_connector.py
*  Extracts the information regarding the stocks on the portfolio through Yahoo Finance's API and adds it to excel.
*  Maintains a record of all the investor's of the portfolio and their respective investments
*  Maintains a log of the purchases and sales of stocks
*  Displays various information regarding the stocks, such as their respective prices, 52 day averages, and the returns on investment.

## dash_file.py
* Displays information from the workbook, such as the live value of the portfolio and the trend of the Net Asset Value, with Dash
* Presents the returns of the stocks, categorized by industry
* Updates the dashboard every 30 seconds

The dashboard, as it currently stands (select values have been redacted from image):

<img width="2880" height="5536" alt="Dash_latest" src="https://github.com/user-attachments/assets/0e5d7dc7-9c1b-4a11-bc29-6b06c1414585" />

