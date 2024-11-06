
# E-commerce User Activity Analysis

**Project Overview**

This project analyzes user activity logs from an e-commerce website to gain insights into user behavior, conversion funnels, and retention rates. 

**Tools and Technologies**
* Google Sheets
* Formulas (VLOOKUP, TEXT, DATEDIF, custom formulas)
* Pivot Tables

**Data Description**

The dataset consisted of a single Google Sheet named "raw_user_activity" with the following columns:

* `user_id`: Unique identifier for each user.
* `event_type`: Type of user activity (e.g., "view_product", "add_to_cart", "purchase").
* `category_code`: Category of the product being viewed or purchased.
* `brand`: Brand of the product.
* `price`: Price of the product (USD).
* `event_date`: Date of the user activity (YYYY-MM-DD format).

**Assumptions**

* The data accurately reflects user activity on the e-commerce website.
* Missing values represent a negligible portion of the data.
* Users with multiple purchases are counted as one unique user for each purchase event.
* Discounts and promotions are not explicitly accounted for in the analysis.

**Findings**
* **Conversion Funnel:** Identified areas for optimization.
* **Purchase Behavior:** Analyzed patterns in product categories, brands, and prices.
* **Retention:** Identified opportunities to improve customer engagement and loyalty.

**Recommendations**
* Enhance user experience on product pages and checkout process.
* Tailor marketing efforts to specific user segments.
* Implement strategies to improve retention rates.

**Future Work**
* Segment user data by demographics or other factors.
* Analyze user behavior across different marketing channels.
* Incorporate external data sources.
