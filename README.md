# Web-Marketing-Dashboard

**1)Objective**
The purpose of this Tableau dashboard is to provide a comprehensive analysis of our web marketing performance. By leveraging key performance indicators (KPIs) and various visualizations, we aim to identify trends, optimize user experience, and enhance overall marketing effectiveness.
**2)Visualizations and Analysis**
**I)Key Performance Indicators (KPIs)**
Total Sessions: The total number of visits within the date range. Each session represents a single user's interactions with your site within a specified timeframe.
Average Page Load Time: The average time it takes for a page to load completely. This metric helps in understanding the speed and performance of your website.
Average Time on Page: The average duration users spend on a single page. It indicates how engaging the content on a page is.
Total Exits: The total number of times visitors leave your site from a specific page.
Total Bounces: The total number of single-page sessions where the user left without interacting further with the page.
Total Unique Pageviews: The number of sessions during which a page was viewed at least once, ignoring multiple views of the same page within a session.
Exit Rate: Calculated as (Total Exits / Total Pageviews) * 100, it indicates the percentage of exits from a page.
Bounce Rate: Calculated as (Total Bounces / Total Sessions) * 100, it represents the percentage of single-page sessions.


**II)Charts** 
**i)Bounce Rate Over Three Years (Weekly):**
Chart: Line Chart
Explanation: Compares weekly bounce rates over three years, ranging from 8% to 30%.
Advantage: Identifies patterns and periods with high bounce rates to improve user engagement.

**ii)Top 5 Page Load Times by Page Title:**
Chart: Horizontal Bar Chart
Explanation: Displays the top 5 pages with the longest and shortest load times.
Advantage: Helps identify pages that may need optimization for faster load times.

**iii)Monthly Exit Rate:**
Chart: Line Chart
Explanation: Shows the exit rate for each month, ranging from 10% to 36%.
Advantage: Highlights months with high exit rates, indicating potential issues that need addressing.

**iv)Monthly Sessions and Peak Sales:**
Chart: Dual Axis Line Chart
Explanation: Combines monthly sessions and peak sales using a calculated field ‘window_max’ and the sum of sessions.
Advantage: Correlates sales performance with website traffic, helping to understand seasonality and peak periods.

**v)Pageviews by Page Title and Country:**
Chart: Vertical Bar Chart
Explanation: Compares pageviews by page title across different countries.
Advantage: Identifies popular content in different regions to tailor marketing strategies accordingly.

**vi)Average Time on Page by Devices:**
Chart: Packed Bubble Chart
Explanation: Displays average time spent on pages across different devices (desktop, tablet, mobile).
Advantage: Understands device usage patterns to improve mobile and desktop experiences.

**vii)Top 5 Page Titles by Sessions:**
Chart: Text Table
Explanation: Lists the top 5 pages with the highest number of sessions.
Advantage: Identifies the most visited content to focus on optimization and updates.

**viii)Device Category by Bounces and Sessions:**
Chart: Text Table
Explanation: Shows the count of bounces and sessions by device category.
Advantage: Reveals which devices contribute most to bounces and sessions, guiding device-specific optimizations.
Bounces and Sessions Over Time:

**ix)Chart: Dual Axis Line Chart**
Explanation: Plots bounces and sessions over time with synchronized axes.
Advantage: Provides a comprehensive view of user engagement trends over time.

**3)Technical Details**
Calculated Fields: Custom fields created using Tableau’s calculation language to derive new data from existing data.
Dual Axis: A feature in Tableau that allows you to layer two different measures on the same chart with separate y-axes.
Synchronized Axis: Ensures that the scales of the two y-axes are aligned, providing a clear comparison between the two measures.

**4)Problem Solving:**
The dashboard addresses the need for visualizing key web marketing metrics, identifying trends, and making informed decisions to optimize website performance and user engagement.

**5) What I Learned in Tableau:**

**1.Creating Interactive Dashboards**: I acquired the skill to design and export interactive dashboards that provide dynamic data visualization and insights.
   
**2. Chart Variety**: I learned to create a diverse array of charts, including bar charts, line charts, packed bubble charts, text tables, and dual-axis charts. This variety allows for comprehensive and visually appealing data representation.

**3. KPIs and Calculated Fields**: I developed the ability to create key performance indicators (KPIs) and calculated fields, such as SUM, to perform custom calculations and derive meaningful metrics from raw data.

**4. Connecting to Data Sources**: I became proficient in connecting Tableau to various data sources, including Excel and CSV files. This skill is crucial for importing and working with data from different origins.

**5. Containers and Layouts**: I learned to use vertical and horizontal containers, as well as blanks, to structure and organize the dashboard layout effectively, ensuring a clean and intuitive user interface.

**6. Filtering Data**: I mastered the art of filtering data within Tableau, allowing users to focus on specific subsets of data and derive more targeted insights.

**7. Dashboard Formatting**: I gained expertise in formatting dashboards, including adjusting labels, text colors, and other visual elements. This enhances the readability and overall aesthetic appeal of the dashboard.

**6) Conclusion:**
This Tableau web marketing dashboard provides an in-depth analysis of website performance, helping to identify trends, potential issues, and opportunities for optimization. By leveraging various charts and calculated fields, the dashboard offers a comprehensive view of web marketing metrics, supporting data-driven decision-making.
