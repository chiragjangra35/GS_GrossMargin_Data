![image](https://github.com/user-attachments/assets/03400e77-0393-4480-8312-91ad3d65c39b)

![image](https://github.com/user-attachments/assets/1160d870-f98a-4999-88c4-f5056075c44e)

![image](https://github.com/user-attachments/assets/898b2ed8-44aa-422e-b442-2a90b2364062)

  **Data Model**
  
![image](https://github.com/user-attachments/assets/0e7935f1-f62a-443c-b9fd-2567f3b56167)

Hi Everyone

Welcome to **GS_Grossmargin_Data** report.

**In this report we have used following methods to make it dynamical:-**

1.  Show Sales Amount and GM Amount as gray and green columns.  
Columns should have data labels. Color for the data label of GM Amount 
must be yellow if GM Percent is less than 10%, and green if GM percent 
is more than 50%. Filter data to only show data for selected filters in the 
header
2. Show Product Categories along the X axis. Support drill through on the selected category.
   Note:  GM is Gross Margin, i.e., Sales Amount – Cost Amount
 GM Percent = GM Amount / Sales Amount
3. Drill through products by Category / Subcategory / Model / SKU
 List Price Brackets (USD, round prices to the nearest cent to determine which brackets they lie in.  Presentation must show them in the following order.):  
0 – 10, 10 – 20, 20 – 50, 50 – 100,
 100 – 200, 200 – 500, 500 – 1000, 
1000 – 2000, 2000 – 5000
 Metrics along the column axis  (All amounts must be in USD accounting format):
 Sales Amount, Sales Quantity, Cost Amount, GM Amount, GM Percent  (Red if below zero, yellow if less than 10%, green if above 50%), 
AUR (Sales Amount / Sales Quantity), AUC (Cost Amount / Sales Quantity;  Red if more than AUR), PPP Sales (Percent Penetration to Parent for Sales 
Amount
4. Show bubbles for Sales Amount.  Bubble must be yellow if GM Percent is 
less than 10%, and green if GM percent is more than 50%.

**Finding:-**

Overall Sale for the year 2020 is **$25M**
Overall Gross Margin for the year 2020 is **$4M**

At 21343167 Bike had the highest sales and was 4058% higher than Accessories, which had the lowest sales at 513253.
Sales and total Gross Margin are positively correlated with each other
Bike accounted for the 87.08% of sales.

At 9388946 United Stated had the highest sales and was 1156.48% higher than Australia, which had the lowest sales at 747242.
United Stated accounted for 38.31% of sales
Across all 7 counties, sales ranged from 747242 to 9388946

Product Basket between 0-10 and 20=50 had highest sales as well as highest Gross Margin 55.89% and 52.83% respectively
