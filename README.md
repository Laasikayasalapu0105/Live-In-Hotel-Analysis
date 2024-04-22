

# Live-In Hotel Analysis - Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMTliZGYzMjgtOWMxZS00MDRjLWFiOGYtMjQ2YWEyMTczYTZkIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Dashboard Overview

The Live-In Hotel Analysis dashboard provides a comprehensive view of key performance indicators and insights aimed at rejuvenating Live-In Grands' position in the luxury hotel business category. Leveraging business and data intelligence, this dashboard offers strategic insights derived from historical data to support revenue management and decision-making processes.

## Problem Statement

Live-In Grands, a prominent player in the hospitality industry with multiple 5-star hotels across India, faces challenges stemming from increased competition and ineffective decision-making. Over its 20-year tenure, Live-In Grands has witnessed a decline in market share and revenue due to strategic moves by competitors. The Managing Director seeks to regain market dominance by incorporating business and data intelligence to inform strategic decisions and drive revenue growth.

## Data Sources

- Date.csv: Contains date-related information for analysis and visualization.
- Hotels.csv: Provides details about Live-In Grands' multiple 5-star hotels across India.
- Rooms.csv: Includes information about room types, availability, and capacity.
- Fact Aggregated Booking: Aggregate data on bookings, revenue, and occupancy rates.
- Fact Booking: Detailed data on individual bookings, including booking status and customer information.


## Key Metrics

- RevPar (Revenue per Available Room): Total revenue divided by the total number of rooms.
- ADR (Average Daily Rate): Total rooms revenue divided by the number of rooms sold.
- Occ% (Occupancy Percentage): Total rooms occupied divided by the total number of rooms available.
- DSRN (Daily Sellable Room Nights): Daily basis assessment of sellable room nights.
- Realization: Utilized room nights (URN) divided by booked room nights (BRN), providing insights into room utilization efficiency.

## Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Clean the data by removing null values, unwanted columns and errors.
- Step 5 : when It was observed that in none of the columns errors & empty values were present load the data.
- Step 6 : Calculate key metrics including RevPar, ADR, Occ%, DSRN, and Realization.
- Step 6:  Design a user-friendly interface to visualize insights and trends.

# Snapshot of Dashboard 

![Screenshot 2024-04-22 003242](https://github.com/Laasikayasalapu0105/Live-In-Hotel-Analysis/assets/167681389/dd7c711a-f071-4238-8bf7-f65e93c4f72d)

## Insights and Recommendations:

- Revenue Optimization: Utilize RevPar and ADR metrics to optimize room pricing strategies for maximum revenue generation.
- Occupancy Management: Improve occupancy rates by analyzing trends in occupancy percentage and implementing targeted marketing and promotion campaigns.
- Realization Enhancement: Increase room utilization efficiency by addressing factors contributing to unrealized room nights.
- Competitive Analysis: Conduct regular competitive analysis to stay informed about market trends and competitor strategies.
- Customer Experience Enhancement: Focus on enhancing the overall customer experience to drive customer loyalty and repeat business.

## Conclusion:
The Live-In Hotel Analysis dashboard equips Live-In Grands with actionable insights and strategic recommendations to regain market share and revenue in the luxury hotel business category. By leveraging business and data intelligence, Live-In Grands can make informed decisions and implement effective revenue management strategies to drive sustainable growth and maintain a competitive edge in the hospitality industry.



        
