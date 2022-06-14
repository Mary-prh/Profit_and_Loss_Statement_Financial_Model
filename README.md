# Profit_and_Loss_Statement_Financial_Model
Building a Profit and Loss (P&amp;L) statement from a raw data extraction
# Dataset Description:
- This case study is about the financials of a company with diversified business. The source data is an extraction from the accounting system of a firm called *Generco*. There are three sheets showing detailed personal data for the years from 2016 to 2018.
## FY 2016 sheet:
- **P&L account:** It indicates the name of the account and shows us what the given amounts of revenue or expenditure are related to.
- **Partner company:** It indicates the partner company number. The company whose extractions we are studying, is a holding entity. 
Its financials include transactions with related companies and third party companies.
Each number in C corresponds to a single partner company, and all third party companies are under the same number.
(There are some rows named *total*. They indicate the overall amount for a given item given by the sum of the amounts registered against
multiple counter parties).
- **Name of partner company:** The transactions with third parties are marked as *external*. 
- **Amounts:** The amount registered for each of the items.Revenues have a negative sign and costs have a positive sign.
- **Account number:** It contains a code which is a reference to the given P&L item in the accounting system.

In this case, the three sheets for FY 16, FY 17 and NY 18 are perfectly aligned.

## Data Cleaning:
- Firstly, ready filters are created on the top of the page with data in Excel (Alt + T).
- Using filter, the rows with *total* are eliminated, which do not provide any new information (filtering the total >> Ctrl + minus).
-  
- 
