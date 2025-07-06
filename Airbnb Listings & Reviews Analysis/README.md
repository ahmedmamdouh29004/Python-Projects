# Airbnb Paris Listings Analysis

This project explores Airbnb listings data in **Paris**, aiming to uncover pricing trends, host activity over time, and neighborhood-based patterns.

---

## Objective

To analyze Airbnb listings in Paris to answer key business and market questions like:
- Which neighborhoods are the most/least expensive?
- How does accommodation size affect price?
- How has the number of hosts evolved over time?
- Are prices increasing or decreasing over the years?

---

## Dataset

- Source: [Airbnb Listings & Reviews Dataset]
- File: `Listings.csv`
- Encoding: `ISO-8859-1`

Key columns used:
- `host_since`: when the host started on Airbnb  
- `neighbourhood`: area in Paris  
- `accommodates`: number of guests per listing  
- `price`: nightly price  
- `city`: used to filter Paris-only data

---

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Datetime

---

## Key Insights

- **Neighborhood Pricing**: Prices vary greatly by neighborhood. Some upscale areas like **Elysee** have significantly higher average nightly prices.
- **Accommodation Size**: Listings with more capacity (more guests) tend to have higher average prices, though with some exceptions.
- **Host Growth**: The number of new Airbnb hosts in Paris steadily increased over the years before COVID-19.
- **Pricing Trend Over Time**: The average nightly price showed some fluctuation over time — could indicate seasonality or market shifts.

---

## Visualizations

- Bar plots comparing **average price per neighborhood**
- Bar plots of **price vs. number of guests accommodated**
- Line plots showing **host count over time**
- Line plots for **price trends over time**

---

## Future Improvements

- Clean & normalize price values (e.g., remove € symbol if present)
- Consider adding listings availability or reviews
- Include seasonal analysis (monthly/yearly fluctuations)
- Map-based visualization (e.g., using Folium or Plotly)

---

## Conclusion

This project shows how a focused EDA (Exploratory Data Analysis) on Airbnb listings can help understand:
- Market pricing
- Customer demand by size
- Host behavior over time

Great for business strategy, host insights, and platform development.

---

## Author

**Ahmed Mamdouh**  
Junior Data Analyst | Python | Pandas | Visualization  


