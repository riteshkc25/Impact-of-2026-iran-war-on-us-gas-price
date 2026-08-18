# Impact of 2026 Iran War on U.S. Gasoline Prices.

1. Wayback Machine was used to scrape archived snapshots from AAA page for the past dates.
2. Scraper was built to find the archived snapshot for each date and to extract state level gas prices (regular, midgrade, premium, diesel)
3. The dates used in this analysis were from Jan 1, 2024 to July 23, 2026. For some dates, Wayback machine was not able to find any snapshot. In those cases, linear interpolation was used to estimate the price.
4. To make sure the scraped data is correct, GitHub repo (lykmapipo/US-Gas-Prices) was used for comparison for few dates. 
5. The scraped data were cleaned and transformed in python. For example,  handling time formatting, converting price fields to numeric, adding US regions to each state, and reshaping the dataset into a long format for better tableau analysis.
   
<img width="2440" height="1570" alt="aaa_gasprice_tableau_image" src="https://github.com/user-attachments/assets/3ee29409-5cd1-4f6c-a9f9-f32db3f48380" />
Tableau Link:(https://public.tableau.com/app/profile/ritesh.kc/viz/aaa_oilprice_analysis/Dashboard2)
