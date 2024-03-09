# Domino's Pizza Sales Analysis


## Problem Statement

Dominos Pizza wants to sell more pizzas and make more money. To do this, they need to understand what makes people buy pizzas and what stops them. 
They want to look at things like where they sell the most pizzas, which pizzas are most popular, and if discounts or promotions help sell more. By figuring out these things, 
Dominos Pizza can come up with better ways to sell pizzas and make more profit.

### Steps followed 

- Step 1 : Load data into Power BI Desktop from MYSQL Database.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also we check duplicate values,null values and data types of all columns.
- Step 4 : In pizza_size column, i did replaced M to Medium, S to Regular,L with Large,XL to X-Large and XXL to XX-Large.
- Step 5 : After that i did close & Apply
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : I did create new table Key-Measures, In this Key-Measures i did create All Measures that is mentioned below.
    
   (A)  Total Revenue = sum(pizza_sales[total_price])

  ![a](https://github.com/narendrakharol037/Domino-s-Sales-Analysis/assets/121941969/e9dd62c8-15c3-4660-ab6a-ac7f6d30849c)
    
   (B)  Average Order Value = [Total Revenue]/[Total Orders]

  ![b](https://github.com/narendrakharol037/Domino-s-Sales-Analysis/assets/121941969/289b2545-6628-4df4-91b7-1d1b83fe6343)


   (C)  Total pizzas sold = sum(pizza_sales[quantity])

  ![c](https://github.com/narendrakharol037/Domino-s-Sales-Analysis/assets/121941969/27513391-8864-46a2-ba5d-54698120cc7b)

   (D)  Total Orders = DISTINCTCOUNT(pizza_sales[order_id])

  ![db](https://github.com/narendrakharol037/Domino-s-Sales-Analysis/assets/121941969/6bcabf79-2c05-4e96-9da2-8cc1a947ecee)

   (E)  Average Pizzas per Order = [Total pizzas sold]/[Total Orders]

  ![k](https://github.com/narendrakharol037/Domino-s-Sales-Analysis/assets/121941969/103eac04-5070-4bf2-9674-06a52ef3f612)

   
            
- Step 9 : After that I did take new-card visual from Visualization tab and all above five measures value put in the card, and modyfied all five cards increase font.
- Step 10 :After that I did take Rectangle shape from Shape tab and rounded it's corneres and all visuals are put in the Rounded Shape.
- Step 11 :I did created Some visuals like that.

  (a) Daily trend for total orders

  (b) Monthly trend for total orders
  
  (c) % of Sales by Pizza Category
  
  (d) % of Sales by Pizza slice
  
  (e) Total Pizza sold by Pizza Category


- Step 12 : After that I did take text box, In this box i did write Report title DOMINO'S SALES REPORT
- Step 13 : In the report view, I insert two slicer from visualization tab, that is mentioned are below.

   (a)  By Pizza Category

   (b)  By Order Date

   
# Snapshot of Dashboard (Power BI Desktop)

        HOME PAGE

        ![in](https://github.com/narendrakharol037/Domino-s-Sales-Analysis/assets/121941969/a52c7a14-629e-43ba-85f9-6e305d543536)
        


- Step 14 : After that I did created Second Page of the Report that is Best/Worst_Seller
- Step 15 : In this Page I did also put all five Measures that is put in the above Home Page.
- Step 16 : After that I did created six Bar Plot from Visualization tab that is mentioned below.

    (a)  Top 5 Pizzas by Revenue

    (b)  Top 5 Pizzas by Quantity

    (c)  Top 5 Pizzas by Total Orders

    (d)  Bottom 5 Pizzas by Revenue

    (e)  Bottom 5 Pizzas by Quantity

    (f)  Bottom 5 Pizzas by Total Orders 
 
- Step 17 : After that I did write Report title that is DOMINO'S SALES REPORT
- Step 18 : Then I did insert two slicer from visualization tab that is like that Home Page.

# Report Snapshot (Power BI DESKTOP)

        BEST/WORST_SELLER PAGE
 
 
 
# Insights of Home Page

 (1) Orders are Highest on Weekends like that Friday and Saturday Evening.

 (2) There are maximum orders from months of July and January.

 (3) Sales Category, Classic contributes to maximum sales and total oredrs.

 (4) Sales by Size, Large size Pizza contributes to maximum sales. 



# Insights of Best/Worst Seller Page

 (1) Thai Chicken Pizza contributes to maximum Revenue.

 (2) Sales by Quantity, Classic deluxe Pizza contributes to maximum Quantity.

 (3) Classic deluxe Pizza contributes to maximum Total Orders.

 (4) The Brie care Pizza contributes to minimum Revenue.

 (5) The Brie care Pizza contributes to minimum Quantity.         

 (6) The Brie care Pizza contributes to minimum Total Orders.
 
 

           
  
  



 



  
 

