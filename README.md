# Mohamed Ftouh – Data Analyst Portfolio

**Live site:** https://momoft07.github.io

My personal portfolio as a Data Analyst in Business Intelligence, based in Berlin. It shows the BI work I did at ALBA Süd, KUKA and Eiffage, my master's thesis on polyglot database architectures, and an interactive rebuild of my thesis Power BI report, including the DAX and M code behind it.

## What's on the site

**Toolkit and profile**
My tools grouped by pipeline stage: collect, transform, model and present. Hovering or tapping a tool shows where I used it in practice.

**Selected work**
Six projects told as a scroll story. As you scroll, a visual next to each project animates to show the problem and the result, for example Python ETL automation that cut manual reporting from 50 to 15 hours per week.

**Master's thesis**
An interactive architecture diagram. You can switch between the polyglot design (PostgreSQL, TimescaleDB, MongoDB behind a Python data access layer) and the monolithic PostgreSQL 15 baseline it was benchmarked against.

**Interactive dashboards**
The Power BI report from my thesis, rebuilt for the web with the same data, measures and relationships:

- Four report pages (Executive overview, Container fill, Fleet and emissions, Incidents) with working filters and cross-filtering.
- A **DAX** button on every visual that shows the measure behind it.
- A note under each visual explaining which filters reach it and why, based on the model's relationships.
- A **Thesis benchmark** page comparing query times for polyglot against baseline, including scalability from 1× to 10× data volume.
- A **Data model** page with a clickable star schema, showing each table's columns, relationships and Power Query (M) steps.
- An **Original in Power BI** switch showing screenshots of the report as it looks in Power BI Desktop.

## Data

All dashboard data is **synthetic**. It was generated for my master's thesis and does not contain real company data. The depot names refer to ALBA because the thesis was written in cooperation with them.

The data, DAX measures, M queries and relationships were extracted directly from the thesis `.pbix` file, so the web version uses the same logic as the report.

## How it's built

- One self-contained `index.html` file: HTML, CSS and vanilla JavaScript, with the data and images embedded.
- All charts are custom SVG drawn in JavaScript, with no chart libraries.
- Responsive layout for desktop and mobile, with light and dark mode.
- Keyboard accessible, and animations are turned off for visitors who prefer reduced motion.
- Hosted for free on GitHub Pages.

## Run it locally

1. Clone the repository:
   ```
   git clone https://github.com/momoft07/momoft07.github.io.git
   ```
2. Open `index.html` in any modern browser. No build step or server is needed.

## Tech stack behind the projects

Power BI, DAX, Power Query (M), SAP Analytics Cloud, Python (pandas, SQLAlchemy, PyMongo), SQL, PostgreSQL, TimescaleDB, MongoDB, IBM Cognos, RONA ERP, Celonis.

## Contact

- Email: momoftouh@outlook.com
- LinkedIn: https://www.linkedin.com/in/moftouh
- GitHub: https://github.com/momoft07

I'm open to Data Analyst and BI roles in Berlin or remote.
