# Management Insights Report

## Management Questions

### 1. How much revenue is the business generating, and how much of that value is being successfully delivered?

- Business is generating ₹21,176,377 revenue and ₹19,710,544 is successfully delivered.

### 2. What proportion of business value and quantity is affected by returns, cancellations and refunds?

- 6.92% of business value and 7.73% of quantity are affected by returns, cancellations, and refunds.

### 3. How has sales performance changed month-on-month? Which periods show meaningful improvement or deterioration?

- Best-performing month: March, with ₹1.93M in sales.
- Lowest-performing month: November, with ₹1.62M in sales.
- Sales show an overall declining trend after March, with the sharpest MoM decline in September (-6.62%).

### 4. Which sales channels contribute most to orders, sales and delivered sales? Does the highest-volume channel also create the highest value?

- Amazon is the leading channel, generating 10,607 orders (35.0%) and ₹7.52M in overall sales (35.5%).
- It also leads in delivered sales at ₹6.97M, confirming that the highest-volume channel is also the highest-value channel.
- Myntra and Flipkart follow, contributing 23.3% and 21.6% of sales, respectively.

### 5. What differences can be observed between male and female customers in customer count, orders, quantity and sales?

- Women customers dominate in volume, with 19,961 customers (68.5%), 19,980 orders (68.6%), and 21,702 units sold (69.5%), generating ₹13.56M in sales (64.1%).
- Men have a smaller customer base (9,163) but a higher Average Order Value of ₹830.64 vs ₹678.82 for women, indicating higher spending per order.
- Overall, women drive the majority of volume and sales, while men show stronger order value per transaction.

### 6. Which product categories and sizes generate the greatest demand? Are the highest-volume products also the highest-value products?

- SET is the strongest category, with the highest demand at 12,446 units and the highest sales of ₹10.51M, followed by KURTA at 10,541 units and ₹4.96M.
- By size, M has the highest demand at 5,526 units, followed by L (5,173) and XL (4,463).
- The highest-volume category is also the highest-value category (SET), showing that strong product demand is translating into higher revenue.
- For sizes, M also generates the highest sales at ₹3.77M, followed by L (₹3.45M) and XL (₹2.95M).

### 7. How significant is B2B activity compared with B2C activity in terms of customers, orders, quantity and sales?

- B2C dominates the business, accounting for 28,276 customers, 28,309 orders, 31,048 units sold, and ₹21.05M in sales, representing almost the entire business volume.
- B2B activity is relatively small, with only 186 customers and orders, 189 units, and ₹126K in sales, roughly 0.6% of total sales.
- Although B2B volume is low, its 95% delivery rate is slightly higher than B2C's 93%, while cancellation rates are broadly similar (2% vs 3%).

### 8. Which geographical markets contribute most to performance, and are there locations where fulfilment performance requires attention?

- Maharashtra (₹2.99M), Karnataka (₹2.65M) and Uttar Pradesh (₹2.10M) are the top three states by sales; together with Telangana (₹1.71M) and Tamil Nadu (₹1.68M), the top five states contribute about 52.6% of overall sales.
- Fulfilment needs attention in the large markets: Maharashtra (135) and Karnataka (112) have the most cancelled orders, while Karnataka (146) and Maharashtra (144) have the most returned orders. Karnataka, Telangana, Gujarat and Kerala lose about 8% of sales value to non-delivery, versus 5% in Delhi.
- Small markets such as Meghalaya (14%), Andaman & Nicobar (12%), Chandigarh (11%) and Puducherry (10%) show the highest non-delivered share, but their order volumes are small (40–92 orders), so these rates should be read with caution.
- At city level, Bengaluru, Hyderabad, New Delhi, Chennai and Mumbai lead in transaction volume.

### 9. When the Start Date and End Date are changed, which business drivers change most noticeably?

- Overall Sales and Quantity change most noticeably with the date range, followed by Delivered Sales and Quantity.
- Among quality measures, the delivered share changes most across date ranges: about 94.3% in Q1 versus 91.0% in Q4, with the non-delivered value share rising from 5.7% to 9.0%, mainly because of returns.

### 10. Based on the complete analysis, what are the most important issues or opportunities that senior management should investigate further?

- Returns are the largest source of lost value (₹719K), and the delivered share of monthly sales declined from 94.7% in January to 90.6% in November.
- Western Dress and Kurta drive a disproportionate share of returns and refunds.
- The business depends heavily on one category (SET, about 50% of sales), three marketplaces (about 80% of sales) and five states (about 53% of sales).
- B2B is only 0.6% of sales but delivers better (95% vs 93%), which makes it an untapped opportunity.

### Highest contributing customer segment

- Adults are the highest-contributing age group, generating ₹10.61M in sales and 15,631 units, followed by Teenagers at ₹6.41M.
- By gender, Women contribute the most, with ₹13.56M in sales and 21,702 units, compared with Men at ₹7.61M.
- Overall, Adults and Women are the largest customer segments by sales and volume.

---

## Executive Summary

### Three Business Insights

- Returns drive most of the value leakage. ₹1.47M (6.92% of sales) is not delivered: returned ₹719,147 (3.40% of sales, 49% of the leakage), cancelled ₹481,844 (2.28%) and refunded ₹264,842 (1.25%). The delivered share of monthly sales fell from 94.7% (Jan) to 90.6% (Nov).
- Fulfilment problems are concentrated in two categories. Western Dress is 14.9% of sales but 28.4% of returned value (₹204,409), with an 88% delivery rate versus 95% for SET. Kurta is 23.4% of sales but 44.9% of refunded value (₹118,824).
- Performance is highly concentrated. SET generates 49.6% of sales (₹10.51M), Amazon, Myntra and Flipkart together generate about 80%, and the top five states generate about 53%.

### Three Management Actions

- Run a returns-reduction programme for Western Dress and Kurta (size/fit guidance, product description and image audit, quality checks) and track monthly Return Rate and Delivered %. Target: close the gap between Western Dress (88%) and SET (95%).
- Investigate fulfilment in Maharashtra, Karnataka and Telangana with logistics partners, as they have the highest cancelled/returned counts. Set a state-level alert for a non-delivered share above 8%.
- Reduce concentration risk: grow Ajio, Nalli and other channels, pilot B2B sales (0.6% of sales but 95% delivery rate), and use targeted upsell for men (AOV ₹830.64 vs ₹678.82 for women).

---

## Data Prep Notes

- Raw data preserved: the Raw Data tab is untouched (31,047 transaction lines); all preparation was done in the Working File.
- Retained: Order ID, Cust ID, Gender, Age, Age Group, Date, Status, Channel, Category, Size, Qty, Amount, City, State, B2B.
- Excluded: SKU (not needed for the required analysis), currency (all INR), postal code, the country-code column and the raw Month text (replaced by derived date fields).
- Renamed: ship-city to City, ship-state to State, "Channel " (trailing space) to Channel.
- Transformed: Year, Quarter, Month, Month Number, Week, Day (name), and Numeric Day derived from Date; Customer Type (B2B/B2C) derived from the B2B flag; text fields (gender, age group, status, channel, category, size, city, state) standardized to uppercase.
- City cleaning: common spelling variants were merged (e.g. Bangalore to Bengaluru, Allahabad to Prayagraj, Gurgaon to Gurugram); remaining small-town names are as in source data.
- State: Delhi and New Delhi were kept separate (New Delhi has only 10 orders).
- KPI logic: customers and orders are distinct counts (COUNTUNIQUEIFS), not row counts. Group totals in reports are sums of distinct counts per group, so an order appearing in more than one group is counted in each.
- MoM: January is the base month, so month-on-month growth starts from February.
- Limitation: the dataset contains only 36 unique dates (about three per month), so monthly and weekly trends reflect these dates only.