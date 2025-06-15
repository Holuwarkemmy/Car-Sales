
# Car Sales Analysis

## Introduction  
This project delivers an in-depth analysis of car sales data using a custom-built dashboard. It examines key variables that influence vehicle pricing, demand, and overall marketability. The goal is to equip dealerships, analysts, and stakeholders with practical insights to improve pricing strategies, inventory optimization, and feature-based upselling.

---

## Aim  
To uncover actionable business intelligence from car sales data and present it through an interactive dashboard that supports decision-making in dealership operations.

---

## Objectives  
1. Analyze the pricing patterns across fuel types, transmission types, and vehicle conditions.  
2. Understand how technical and non technical attributes (e.g. mileage, colour, features) influence resale value.  
3. Provide strategic recommendations to maximize profitability and streamline vehicle offerings.

---

## Insights  

### 1. Fuel Type Significantly Affects Price  
- Petrol vehicles command an average price of $201K, which is significantly higher than other fuel types. This spike is largely due to premium or luxury vehicles in the dataset.

- Electric, Diesel, and Hybrid cars are positioned in the mid-tier price range (~$45K–$47K), indicating standardization in alternative fuel options.

- Gasoline-powered cars, averaging $23K, represent the lowest-value segment, likely appealing to economy-conscious buyers or representing older models.

### 2. Colour Impacts Perceived and Market Value  
- Silver, White, Black, Blue, and Green cars average $57K–$60K, indicating strong market preference for neutral and classic shades.
- Conversely, Gray, Orange, Brown, and Yellow cars sit at the bottom with prices around $23K, despite similar technical specs.

### 3. Transmission Type Affects Price Marginally  
- Automatic cars make up 51% of the sample and are priced at $47K on average.
- Manual cars account for 49% and sell for $45K.

### 4. Vehicle Condition Holds Strong Influence  
- “Like New” cars have the highest average price ($47K), slightly outperforming both “New” ($46K) and “Used” vehicles ($46K).
- This indicates that high-quality used vehicles can rival new models in price, especially when they are well-maintained.

### 5. Accident History Severely Impacts Resale Value  
- Vehicles with no accident history average $86K, while those with a recorded accident drop sharply to $37K.
- Interestingly, accident-flagged vehicles have higher mileage (74K) than non-accident cars (61K), compounding their depreciation.

### 6. Feature Count Distribution Is Skewed  
- **8007 vehicles** have **only 1 feature**  
- Far fewer cars have multiple features (only ~5000 for each 2 - 4 feature category)  
*Low feature count suggests untapped upselling potential through feature bundles.*


## Recommendations  

1. **Segment Petrol Cars Further**
Create subcategories (e.g. “Luxury Petrol” vs. “Standard Petrol”) to ensure more accurate pricing analysis and prevent distortions caused by outliers.
2. **Prioritize Popular Colour Inventory**  
Increase sourcing of silver, white, and black vehicles. Bright colours should be discounted or bundled with extras to attract niche buyers.
3. **Emphasize Automatics and Feature-Rich Models**  
Align marketing with demand for automatic transmissions. Upsell low-feature cars with bundled accessories or tech packages.
4. **Acquire and Certify Accident-Free Vehicles**  
Focus procurement on clean-history cars and advertise this heavily. Certified “Accident-Free” tags can justify higher price points.

5. **Leverage High-Quality Used Inventory**  
Push “Like New” used vehicles as premium alternatives to new, with added savings. Improve reconditioning processes to meet this tier.

6. **Introduce a Feature-Package Strategy**  
Standardize and promote tiered feature bundles (e.g. Safety+, Comfort+, Tech+) to raise average selling price and improve perceived value.

7. **Use Dynamic Pricing Models**  
Apply variable pricing based on accident history, condition, transmission, and colour to reflect value more accurately and boost competitiveness


## Tools Used  

- Microsoft Excel
- Pivot Tables, Charts, Slicers  
- Data Cleaning and Aggregation Logic
