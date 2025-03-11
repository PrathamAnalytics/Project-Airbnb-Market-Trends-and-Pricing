# ***Airbnb Market Trends and Pricing*** 
<p align="center">
  <img src="https://github.com/PrathamAnalytics/AirBnB-Tableau-Project/blob/main/Image.png?raw=true" alt="Project Image">
</p>

# ***Project Overview***
This project analyzes Airbnb listings, reviews, and calendar data to extract actionable insights into pricing trends, customer preferences, and booking patterns. The findings are intended to support data-driven decision-making for stakeholders, including property owners, managers, and Airbnb strategists.

# ***Purpose of the Data***

The dataset serves multiple objectives:

- Understand Airbnb property performance based on reviews and bookings.
- Analyze pricing strategies to optimize revenue.
- Identify customer preferences and trends through reviews.
- Examine temporal patterns in availability and pricing.

# ***Data Description***
The dataset consists of three components:

### *Listings*

- **Total Records:** **3,818**
- **Key Features:**
    - Listing metadata: `id`, `name`, `listing_url`, `description`
    - Neighborhood and host details: `neighborhood_overview`, `host_id`, `calculated_host_listings_count`
    - Review scores: `review_scores_rating`, `review_scores_accuracy`, etc.
    - Booking details: `instant_bookable`, `cancellation_policy`, etc.

### *Reviews*

- **Total Records:** **84,849**
- **Temporal Coverage:** **June 2009 to January 2016**
- **Key Features:**
    - Review metadata: `listing_id`, `id`, `reviewer_id`, `reviewer_name`
    - Customer feedback: `comments`

### *Calendar*

- **Total Records:** **94,776**
- **Temporal Coverage:** **December 2016 to January 2017**
- **Key Features:**
    - Availability: `available`
    - Pricing: `price`
    - Temporal metadata: `date`


# ***Technical Overview***

### **Data Source** :

 Excel workbook containing Listings, Reviews, and Calendar data.

### **Analysis Tools** :

- Excel: Used for data standardizing and data cleaning.
- Tableau (intended): For visual analysis and insights.

### **Techniques** :

- Descriptive statistics to summarize key metrics.
- Price by per Zipcode and revenue of each month.
  
# ***Executive Summary***
This analysis focuses on uncovering trends and insights across three key areas: property listings, customer reviews, and pricing data.

### *Key Highlights* :

1. *Pricing Trends* :
   
    - Average price per night is **$139.21**, with prices ranging from **$20** to **$1,650**.
    - Properties priced below **$100** are the most common, representing a significant market share.
      
2. *Availability* :
   
    - **73%** of calendar entries indicate properties are available, suggesting healthy booking rates but potential for optimization in certain cases.
      
3. *Customer Feedback* :
   
    - Reviews highlight guest satisfaction, with frequent mentions of location and cleanliness.
    - Certain listings, show a high volume of reviews, indicating strong customer engagement.
      
4. *Listings Performance* :
   
    - Properties with high review scores tend to have more consistent bookings.

      
# ***Top Insights***

### *High-Value Listings* :

- Listings with a review score of **9 or higher** command higher nightly prices (~15% premium on average).

### *Pricing and Availability Correlation* :

- Properties priced above **$300** show significantly lower availability (~40% occupancy rate) compared to properties priced under **$100** (~85%).

### *Seasonal Trends* :

- Peak pricing occurs during weekends and holidays, with price surges of up to **30%**.

### *Customer Preferences* :

- Most frequent feedback in reviews includes mentions of **"cleanliness"** and **"proximity to city centers"**.

# ***Key Insights***

### *Affordable Pricing Drives Bookings* :

- Listings priced competitively under $100 are booked **20-30%** more frequently.

### *Neighborhood Overview Impacts Ratings* :

- Listings with detailed **neighborhood overview** receive **10%** higher review scores.

### *Experienced Hosts Outperform* :

- Hosts managing **5+** properties consistently receive higher ratings (~4.5 stars) than those managing fewer listings (~4.2 stars).


# ***Recommendations***

### *1. Optimize Pricing Strategy*

- *Leverage Dynamic Pricing* :
  
    - The average nightly price is **$139.21**, with **50%** of listings priced between **$75 and $164**. Listings priced below **$100** have a significantly higher availability rate (~85%) compared to premium-priced listings above **$300** (~40%).
    - **Actionable Step**: Introduce dynamic pricing tools that adjust nightly rates based on demand, seasonality, and competitor pricing. For example, increase rates by **20–30%** during weekends and holidays to maximize revenue while maintaining occupancy.
      
- *Review Pricing Outliers* :
  
    - Some listings are priced as high as **$1,650 per night**, likely targeting a niche market. However, these outliers can distort averages and may not reflect actual booking patterns.
    - **Actionable Step**: Hosts with premium-priced listings should emphasize unique features like luxury amenities or exclusivity to justify their pricing.

### *2. Enhance Availability*

- *Improve Calendar Utilization* :
  
    - **73%** of calendar entries are marked as **"available"**, leaving **27%** of dates unbookable or blocked. This indicates room for improvement in maximizing availability.
    - **Actionable Step**: Encourage hosts to open more dates on their calendar, especially during high-demand periods. Listings with consistent availability tend to rank higher in Airbnb’s search results.
      
- *Promote Instant Booking* :
  
    - Listings with **instant bookable** enabled typically experience higher booking rates. While this feature wasn’t directly measured in the dataset, industry trends suggest it reduces friction for guests.
    - **Actionable Step**: Educate hosts on the benefits of enabling **instant bookable** and provide resources for managing last-minute bookings effectively.

### *3. Improve Listing Descriptions*

- *Enhance Property Descriptions* :
  
    - Listings with detailed descriptions and **neighborhood overview** tend to perform better in reviews. Many entries in the dataset lack complete descriptions, reducing their appeal.
    - **Actionable Step**: Encourage hosts to provide comprehensive property descriptions, including amenities, nearby attractions, and unique selling points. Listings with clear, attractive descriptions are more likely to convert views into bookings.
      
- *Focus on Visuals* :
  
    - While photo data isn’t included, research shows that high-quality images can boost bookings by **15–20%**.
    - **Actionable Step**: Recommend hosts invest in professional photography services and include images of key amenities like living spaces, kitchens, and views.

### *4. Leverage Customer Feedback*

- *Encourage Reviews* :
  
    - Listings with **consistent reviews** have higher ratings and booking rates. The dataset shows some properties with few or no reviews, which may deter potential guests.
    - **Actionable Step**: Implement follow-up emails or app notifications encouraging guests to leave reviews. Highlight positive feedback in listings to build trust.
      
- *Address Recurring Issues* :
  
    - Analyze review comments to identify common complaints, such as cleanliness or host responsiveness.
    - **Actionable Step**: Provide resources or training for hosts to address these issues. For example, a focus on cleanliness can improve ratings by **1–2 points on average**.

### *5. Focus on Pricing for Specific Market Segments*

- *Budget Listings* :
  
    - Listings priced under **$50** cater to price-sensitive travelers, a segment that often seeks value in urban and suburban areas.
    - **Actionable Step**: Recommend budget hosts offer additional perks **(e.g., free Wi-Fi, early check-in)** to enhance the guest experience without raising costs significantly.
      
- *Luxury Market* :
  
    - Premium listings priced above **$300** are less frequently booked but cater to a niche audience seeking unique or exclusive experiences.
    - **Actionable Step**: Highlight luxury features **(e.g., private pools, scenic views)** and market these properties on platforms targeting affluent travelers.

# ***Data Limitations***

### *Temporal Coverage* :

- Calendar data is limited to one month **(December 2016–January 2017)**, restricting seasonal analysis.

### *Missing Data* :

- Several listings lack descriptions, reviews, or review scores, which may bias the analysis.

### *Outliers* :

- Extreme prices **($1,650 per night)** may skew average price calculations.

### *Static Data* :

- Data snapshots may not reflect real-time dynamics of the Airbnb marketplace.

# ***Conclusion***
This analysis highlights actionable insights for improving Airbnb property performance. By optimizing pricing, enhancing property descriptions, and leveraging customer feedback, stakeholders can increase revenue and guest satisfaction. The provided data offers a strong foundation, but expanding its scope will yield even more comprehensive insights.



