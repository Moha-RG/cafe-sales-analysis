# ☕ Cafe Sales Data Analysis Project

## 📊 Overview
This project analyzes **cafe sales data** to understand sales performance, spending patterns, and customer payment behavior.  
The goal of the analysis is to identify trends that help increase **profitability** and improve business decisions.

---

## 🧰 Tools Used
- **Microsoft Excel** → Data cleaning and preparation  
- **Power BI** → Data analysis, visualization, and dashboard creation  

---

## 🔍 Steps Performed
(1). Data Cleaning (Excel):
 - remove duplicates 
 - use first row as a headers
 - change data type 

 1- item column   
   replace all unknown , error and blank cells from the column and replace it with item name
   based on the (price per unit) By making a small list of items that have uniqe (price per unit)
   , use the (xlookup) function and (find & select) to fill the cells
   Then delete the rest of the rows that the previous step could not be applied to
   because they had a similar price (price per unit).

 2- price per unit column
   use the (xlookup) function to fill the blank cells from the small price list we just have made 

 3- quantity column 
   divide (total spent) by (price Per unit) to fill in the blanks, and write 1 for the rows that
   have blank (total spent)

 4- total spent column
   multiply (total spent) by (price Per unit) to fill in the blanks

 5- payment method column
   fill in the empty cells with the three payment methods provided in the column using the percentage
   for each payment method.
   Using a combination of functions like (IF,CHOOSE,MOD,COUNTBLANK)

 6- location column 
   fill in the empty cells in the same way as in the previous column.

 7- transaction date column
   fill in the empty cells by using (randbetween) function 



(2). Data Analysis & Visualization (Power BI):
   - Imported the cleaned Excel dataset into Power BI.    
   - Designed an **interactive dashboard** showing:
     - 💰 **Total Revenue:** \$83.89K  
     - 🧾 **Total Transactions:** 9,499  
     - 📊 **Sales by Item** – highest spending on *Salad* (\$19.1K) and *Sandwich* (\$13.7K).
     - 📊 **Quantity sold by Item** – highest sold item *Coffee* (3.9K) and *Salad* (3.8K).  
     - 📅 **Sales by Month** – strong performance in March and April.  
     - 🏪 **Sales by Location** – balanced split between *In-store* (49.3%) and *Takeaway* (50.7%).  
     - 💳 **Payment Methods** – evenly distributed between *Credit Card*, *Cash*, and *Digital Wallet*.

---

## 📈 Key Insights
- **Salad** and **Sandwich** are the top contributors to total sales revenue.  
- **In-store** and **Takeaway** orders have nearly equal spending, indicating consistent customer engagement.  
- Sales are stable throughout the year, with slight peaks in **March** and **October** AND sharp decline in **February**.  
- Payment methods are evenly used, showing flexibility in customer preferences.  

---

## 🧠 Conclusion
This project demonstrates how Excel and Power BI can be used together to gain valuable insights from sales data.  
The findings can help cafe owners focus on top-selling products, maintain inventory efficiently, and optimize payment options for better customer satisfaction.

---

## 🔗 View Project
📂 You can check the full project files here:  
👉 

---

### #DataAnalysis #PowerBI #Excel #SalesAnalysis #Dashboard #CafeSales #Profitability #Portfolio
