# Cricket World Cup 2022 - Playing 11 Predictor

## Project Overview
The aim of this project is to leverage data analytics techniques to determine the best playing 11 for the upcoming ICC Cricket World Cup 2022. The project involves web scraping data from the ESPN Cricinfo website, transforming the data using Python and Pandas, and creating interactive dashboards using Power BI for insightful visual representation.

## Key Steps
1. **Web Scraping Data from ESPN Cricinfo:**
   - Utilized the third-party web scraper "Bright Data" to effectively gather information from the ESPN Cricinfo website, including match data, results, player batting data, and bowling data.
   - The scraped data was stored in the form of JSON for further processing.

2. **Data Transformation and Conversion:**
   - Leveraged Python and Pandas to transform the JSON data into CSV format.
   - Ensured the data was in a suitable format to be directly used in Power BI, simplifying the process of joining tables.

3. **Power BI Dashboard Creation:**
   - Utilized Power Query in Power BI to further transform and clean the data for analysis.
   - Created dynamic dashboards with interactive charts and visualizations, presenting measures for various aspects, such as power hitters, middle-order batsmen, and bowlers.
   - These dashboards provide valuable insights into player performance, team strengths, and areas of improvement.

4. **Forming the Best Playing 11:**
   - Applied data-driven analysis and decision-making techniques to form the best playing 11 based on the requirements and insights obtained from the dashboard.
   - The combined playing 11 was determined to optimize team performance and increase the chances of success in the ICC Cricket World Cup 2022.

## Technologies Used
- Web Scraping: Bright Data (Third-party Web Scraper)
- Programming Language: Python
- Data Manipulation: Pandas
- Data Visualization: Power BI

## Outcomes
The project's dynamic and informative dashboards provide actionable insights for cricket team management, coaches, and enthusiasts to strategize and select the best playing 11 for the ICC Cricket World Cup 2022.

## Getting Started
1. Clone the repository: `git clone https://github.com/riteshrajsharma/cricket-world-cup-2022.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the data scraping script: `python scrape_data.py`
4. Transform the data using Pandas: `python data_transform.py`
5. Open the Power BI file to explore the interactive dashboards: `cricket_world_cup_2022.pbix`

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please create a pull request or raise an issue in the repository.

