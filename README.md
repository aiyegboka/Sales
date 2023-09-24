<p>
<h1><b><center>SUPERMARKET SALES PERFORMANCE</center></b></h1>

![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)
<p>This report is on telling the story of a supermaket sales for the first-quarter of the year 2019. The use of a business analytic tool was uesd to visualise insights gained from the initial stage; the process involved cleaning the dataset, checking for missing values, changing incorrect datatypes, adding new columns and measures. The analysis went through the phases of <i><code>Business Understanding</code></i>, <i><code>Data Understanding</code></i>, <i><code>Modelling</code></i> and <i><code>Deployment</code></i>.
</p>
<br>
The data attributes include: <code>Invoice ID</code>, <code>City</code>, <code>Gender</code>, <code>Payment Method</code>, <code>Product Line</code>, <code>Quantity</code>, <code>Unit Price</code>, <code>Rating</code> e.t.c. The visualisation is broken into:
</n>
<ol>
    <li><b>Sales Performane:</b> <p>This aspect involves some of the aggregates in the dataset which was displayed with the use of <code>Cards</code>, and measures were written through <code>DAX</code> (Data Analysis Expressions).</p>
    </n>
        <ul style= 'list-style-type:square'>
        <li><p><b><i>Total Sales:</i></b> the supermarket achieved a total revenue of <b>323,000</b> for the first-quarter of 2019.</p></li>
        <li><p><b><i>Total Invoice ID's:</i></b> there were an aggregate of <b>1000</b> customers that purchased an  item from the supermarket in the first quarter.</p></li>
        <li><p><b><i>Total Profit:</i></b> created from a measure, <code>Total Profit = SUM(supermarket_sales[Profit])</code>this visualisation sums up the total profit acquired through the first-quarter of 2019 which a total profit of <b>292,000</b>.</p></li>
        <li><p><b><i>Total Profit (%):</i></b> the percentage of profit accrued was <code>95%</code>.</p></li>
        <li><p><b><i>Total Cost:</i></b> this was created with the use of a measure <code>Total Cost = SUM(supermarket_sales[Cost])</code>, the visualised cost was filtered by the Top 1 (highest cost), which gave a result of <b>993</b>.</p></li>
        <li><p><b><i>Quantity:</i></b> the visualised value showcases a filtered value for the highest quantity <b>1190</b>.</p></li>
        <li><p><b><i>Sales by Category:</i></b> this shows the distribution of sales by each product line in a column chart.</p></li>
        <img src = "https://drive.google.com/file/d/1JWanez66-POEuchAsBHfVp95JLnGkm2-/view?usp=sharing", alt = "Sales over Time"><br>
        <img src = "https://drive.google.com/file/d/1M775qYDiCRC87EpqYqw8dw6U1F6VXw0j/view?usp=sharing", alt = "Product Line"><br>
        </ul>
        </n>
    </li>
    <li><b>Customer Behaviour:</b> <p>This involved the <i>customer demographics</i>, <i>buying patterns</i>, <i>customer rating</i>.</p>
    </n>
        <ul style= 'list-style-type:square'>
        <li><p><b><i>Customer Demographics:</i></b> this shows the total customer ID's which is <b>1000</b>, the gender ratio; the female gender supercedes the males.</p></li>
        <li><p><b><i>Patterns:</i></b> here, the most popular payment method is <b>Ewallet</b>, there was a peak sales on <b>1/24/2019</b>.</p></li>
        <img src = "https://drive.google.com/file/d/1j_i5XWfWSd93gnnWJ9HpFkVTpmU2b1Pa/view?usp=sharing", alt = "Payment Method"><br>
        <img src = "https://drive.google.com/file/d/1AwnvmOvxH7LiC8w-RNuUJ8pENzxWFMH3/view?usp=sharing", alt = "Cost vs Gross Income"><br>
        <li><p><b><i>Customer Rating:</i></b> this shows the average customer rating of <b>6.97/10</b>.</p></li>
        <img src = "https://drive.google.com/file/d/1t--vVGd7xiYb5xwEyxRmn5zT9U-RyKKq/view?usp=sharing", alt = "Customer rating"><br>
        </ul>
    </li>
    <li><b>Recommendations:</b> <p>From the analysis carried out, here are proposed recommendations.</p>
    </n>
        <ul style= 'list-style-type:square'>
        <li><p><b><i>Expansion:</i></b> The supermarket should invest in an ecommerce platform and expand their product lines.</p></li>
        <li><p><b><i>Product Expansion:</i></b> invest in lines that have a growth potential <i><code>Fashion Accessories</code></i>, <i><code>Food and Beverages</code></i>, <i><code>Electronic Accessories</code></i>.
        <li><p><b><i>Engagement:</i></b> enhance customer strategies through personalised promotions and loyalty programs to lure and retain customers.</p></li>
        </ul>
    </li>
</ol>
<br>
<h2><b><i>CONCLUSION</i></b></h2>
<p>The sales during the month of February and a high profit during the month of January, showed a positive growth and opportunities for improvement. Focusing on the identified trends, and recommended strategies, the supermarket is well-equiped on its success journey in the competitive market.</p>
<br>
<h4><b>APPENDICES</b></h4>
<p>City by Month</p>
<img src = "https://drive.google.com/file/d/15VjMxLRpvKW0xT6vK1v62eLdAXUC9WHB/view?usp=sharing", alt = "City vs Profit"><br>
<p>Key Performance Indicator</p>
<img src = "https://drive.google.com/file/d/19pnev1cyDjHWNRWp9duFSTTw95H3WSFp/view?usp=sharing", alt = "KPI"><br>
<p>Customer Type Ratio</p>
<img src = "https://drive.google.com/file/d/1R33o3TMJsCnjklcwQHfGwtfV0PDU6tBz/view?usp=sharing", alt = "Customer Type"><br>
<p>Cost, Profit by Month</p>
<img src = "https://drive.google.com/file/d/1bJP55BBc-ZoTepirFxpiaS0OkHyY3hI3/view?usp=sharing", alt = "Monthly Cost"><br>
</n>
<p>This report provides an overview of supermarket sales during the first-quarter of 2019</p>
</p>