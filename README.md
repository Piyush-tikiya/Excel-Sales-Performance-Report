# Excel/Sales-Performance/Profit and Loss Report(Brick and Mortar Model) 
### This repository contains various analytical PDF reports prepared for AtliQ Hardware, highlighting sales performance, financial health, market dynamics, and product-level insights for the fiscal years 2019 to 2021.

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/AtliQ%20Hardware%20Business%20Hierarchy%20Model.pdf"> AtliQ Business Model </a>

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/market%20performance.pdf"> Market Performance report </a>

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/Customer%20performance%20report.pdf"> Customer Performance report </a>
  
<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/CUMULATIVE%20P%26L%20REPORT.pdf"> Profit & Loss Statement Year Wise </a>

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/Top%2010%20products.pdf">Top 10 Products </a>

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/division%20level%20report.pdf"> Division Level report </a>

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/top%20%20and%20least%205%20products.pdf"> Top five and bottom five products by qty </a>

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/New%20products%20launched%202021.pdf"> New product launched in 2021 </a>

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/top%205%20countries.pdf"> top five countries by qty </a>

Tools Used: Microsoft Excel, Power Query, Power Pivot, Dax Measures

**Situation:**

AtliQ Hardware experienced rapid business growth from 2019 to 2021, with net sales increasing from $87.5M in 2019 to $598.9M in 2021. The company needed to analyze and present performance across customers, products, countries, and divisions to inform strategy.

**Task:**

I was responsible for developing and presenting a comprehensive business performance analysis using Excel. The objective was to identify key growth drivers, underperforming areas, and opportunities across customer segments, product lines, and global markets.


**Action**: 

I consolidated data from multiple sources and created a busines report which includes following below KPI:


1) **Market Performance**
   
    🎯 Purpose to Make: 
      To compare market-wise performance against targets.

    📝 Task: 
      Track sales progression over three years and evaluate shortfalls against targets for 2021.

    ✅ Solution: 

        India had the highest revenue but also missed targets by $9.6M.
   
        Countries like Spain and Poland saw substantial shortfalls.

        Aids in refining future forecasting and market prioritization.

 2. **Customer Performance Report**
      
    🎯 Purpose to Make: To evaluate how individual customers contributed to AtliQ Hardware’s total revenue and to identify high-growth and high-value accounts from 2019 to 2021.

    📝 Task: Analyze customer-level sales data over three years, comparing net sales and calculating the year-on-year growth, particularly focusing on 2021 vs 2020.

    ✅ Solution:

         The report covers performance of over 70 customers.

         Notable performers:

         Amazon: Grew from $37.5M (2020) to $82.1M (2021) — 118.88% increase.

         AtliQ Exclusive: Rose to $61.1M, up by 245.74% from 2020.

         Nova: Showed explosive growth — 2560.52% YoY.

         Overall, total customer revenue increased from $196.7M in 2020 to $598.9M in 2021, reflecting a 204.47% increase.

         Enables the sales team to focus on top-performing accounts and investigate customer acquisition success.
    

3. **Cumulative P&L Report**
       
      🎯 Purpose to Make: To evaluate the financial health of AtliQ Hardware over FY 2019–2021.

      📝 Task: Aggregate quarterly data to observe trends in Net Sales, COGS, Gross Margin, and GM%.

      ✅ Solution:
   

          Year-over-year growth with FY 2021 reaching $598.9M in Net Sales.
   
          Gross Margin stability around 36–41%.

          Visualizes profitability and guides budgeting decisions.

 4) **Top 10 Products**
      
     🎯 Purpose to Make: To analyze the growth trajectory of the most successful products.

     📝 Task: Identify and compare the top 10 products by sales growth from 2020 to 2021.

     ✅ Solution:

   
          Total sales grew from $6.4M to $52.0M (708% increase).

          AQ Mx NB saw an explosive growth of over 5600%.

          Great for understanding product-market fit and customer preferences.
    

5) **Division Level Report**
     
     🎯 Purpose to Make: To analyze sales performance across business divisions.

     📝 Task: Break down revenue by divisions (N & S, P & A, PC) over 2020 and 2021.

     ✅ Solution
     
         PC division saw the highest YoY growth at 313.70%.

         Overall sales grew by 204.48%.
     

 6) **Top 5 and Least 5 Products**
        
     🎯 Purpose to Make: To identify the best-performing and underperforming products based on sales quantity and revenue.

     📝 Task: Analyze product-level sales data to extract the top 5 and bottom 5 products across all regions and markets.

     ✅ Solution:

          Top 5 products contributed a combined $19.0M in revenue.

          Bottom 5 products only contributed $0.2M.
7) **New Products Launched 2021**
   
     🎯 Purpose to Make: To review the impact of new product launches on overall revenue.

     📝 Task: Track sales performance of products launched in 2021.

     ✅ Solution:

          16 new products brought in $176.2M collectively.

          Top contributors include AQ Qwerty ($22.0M) and AQ Trigger ($20.7M).

8) **Top 5 Countries**
   
      🎯 Purpose to Make: To understand geographical distribution and performance in different countries.

      📝 Task: Determine which countries generated the highest net sales in 2021.

      ✅ Solution:
   
          The top 5 countries are:

             India ($161.3M)

             USA ($87.8M)

             South Korea, Canada, and the UK complete the list.

            

   **ETL Process:**

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/power%20query%20view.png"> Power Query View used for Extract,Transform and Load  </a>

•	Extracted raw sales data from multiple sources

•	Transformed and cleaned data using Power Query

•	Loaded data into Power Pivot for modeling and analysis

  **Data Modeling:**

<a href = "https://github.com/Piyush-tikiya/Excel-Sales-Performance-Report/blob/main/data%20model.png"> Relationship between tables using star schema  </a>

•	Five dimesnions tables(Having Unique values) are linked with fact tables (transactional table)

•	Created calculated columns and measures using DAX

• Created a date table in Power Query by fetching the start date of each month and the corresponding year, then added a new column for Fiscal Month to represent the fiscal year.

**Results**

Delivered clear, data-driven insights through structured reports on customers, products, markets, and P&L.

Identified growth opportunities and underperforming areas to guide strategic actions.

Delivered insights that improved decision-making, speed and accuracy which played a key role in achieving  1x revenue growth.










