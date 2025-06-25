

## 1. Histogram of Sales

**Visual Summary:**
- The distribution is highly right-skewed.
- The majority of sales transactions are below ₹500.
- There are very few transactions exceeding ₹20,000, indicating the presence of extreme outliers.

**Inference:**
- Most transactions involve low-value sales, suggesting that customers frequently purchase inexpensive items.
- High-value sales are rare and likely represent bulk purchases or high-end products.
- The presence of extreme outliers causes the mean to be significantly higher than the median, which could distort average-based decision-making.
- For better analysis and visualization, a log transformation might be helpful to normalize the distribuio.

---

## 2. Histogram of Quantity

**Visual Summary:**
- The quantity ordered per transaction mostly ranges between 1 and 3 units.
- The distribution shows a clear peak at 2 and 3.
- Orders with quantities above 10 are very rare.

**Inference:**
- The majority of customers order small quantities, indicating a retail-focused operation rather than bulk sales.
- A small number of transactions involve larger quantities, which may be associated with corporate or institutional buyers.
- Business strategies such as quantity-based discounts could be used to encourage larger orders and improve overall sales volume.

---

## 3. Histogram of Discount

**Visual Summary:**
- Sharp peaks at 0.0 and 0.2, indicating these are the most commonly applied discount rates.
- Smaller spikes appear around 0.3, 0.4, and 0.7, with very few values in between.

**Inference:**
- The business likely uses standardized discount levels, with 0%, 20%, and 70% being most frequent.
- The gap between discount levels implies fixed policies or promotional tiers.
- A smaller number of high discounts (> 0.5) may negatively impact profit margins and should be reviewd for cost-effectiveness.

---

## 4. Histogram of Profit

**Visual Summary:**
- Highly right-skewed with a dense spike around zero.
- Contains both positive and negative values, with long tails on both sides.

**Inference:**
- Most orders generate low or modest profit, but a noticeable portion of transactions results in losses.
- A few high-profit transactions significantly increase the overall spread.
- This suggests inconsistency in profit margins across products or categories, possibly due to discounting or pricing inefficiencies.

---

## 5. Correlation Matrix of Numeric Features

**Visual Summary:**
- Sales and Profit have a moderately positive correlation (0.48).
- Discount and Profit have a negative correlation (-0.22).
- Quantity has weak or negligible correlation with other variables.

**Inference:**
- Higher sales are generally associated with higher profits, but the correlation is not strong, implying that other factors (e.g., discount, category) influence profit.
- Discounts tend to reduce profit, which aligns with expectations.
- Quantity does not significantly influence profit or sales individually.

---

## 6. Pairplot of Numeric Features

**Visual Summary:**
- Sales vs Profit shows a positive trend with considerable scatter and outliers.
- Discount vs Profit shows a negative trend, especially for discounts above 0.2.
- Distributions along diagonals match the histograms — right-skewed for Sales and Profit.

**Inference:**
- Positive but inconsistent relationship between Sales and Profit — not all high-sales items are profitable.
- Discounts above 0.4 appear to drive significant lo7ses.
- Multiple outliers are present across all numeric features.

---

## 7. Total Profit by Category

**Visual Summary:**
- Technology contributes the highest profit.
- Office Supplies performs moderately well.
- Furniture has the lowest total profit among the three categories.

**Inference:**
- Focus should be placed on growing Technology sales, which appear to be the most profitable.
- Furniture might require a review — possibly due to high costs, ineffective pricing, or discounting issues.
- Resource allocation and marketing efforts can be optimized using these trends.

---

## 8. Profit by Sub-Category

**Visual Summary:**
- Sub-categories like Copiers, Phones, and Accessories generate high profit.
- Sub-categories like Tables, Bookcases, and Supplies are consistently loss-making.

**Inference:**
- Copiers and Phones should be prioritized for marketing and promotions.
- Tables and Bookcases may need pricing restructuring or cost optimization to reduce losses.
- Avoid excessive discounting or bundling low-performing items with high-performing ones.

---

## 9. Sales vs Profit by Category (Scatter Plot)

**Visual Summary:**
- Technology has several points in the high-sales and high-profit zone.
- Furniture shows many negative profit points, even at medium sales levels.
- Office Supplies is spread mostly around low to mid-profit range.

**Inference:**
- Technology is the only category showing strong profit potential with increasing sales.
- Furniture's low-profit behavior across all sales levels is concerning.
- Sales without profit growth suggests margin compression or operational inefficiencies.

---

## 10. Discount vs Profit by Category

**Visual Summary:**
- Higher discounts are consistently associated with lower or negative profit across all categories.
- Points cluster around 0.2 and 0.7 discount values.

**Inference:**
- Discounts beyond 20% are not yielding positive returns.
- Aggressive discounting in Furniture and office Supplies may be causing sustained losses.
- A discount threshold should be enforced to safeguard profitability.

---

## 11 Profit by Region

**Visual Summary:**
- West region leads in total profit.
- East region follows closely.
- Central and South regions lag behind.

**Inference:**
- Marketing and expansion strategies can be focused on the West and East regions for bettCentral and South regions lag behind.
