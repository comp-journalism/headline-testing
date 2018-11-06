# A/B headline testing quant study - NYT pilot
A pilot analysis of headline data from the New York Times.

**Testing start date:** August 6, 2015
**Three years after:** August 6, 2018
**Three years before:** August 6, 2012

## Recent activity
11/6 - Visualized change over time of first-draft features in Tableau
11/5 - Moved data into Tableau
11/2 - Built and applied first-draft feature extraction pipeline to all data
10/31 - Started building out variables for testing hypotheses
10/30 - Commented code and documented project; committed to lab repo.

## Files
**NYT pilot.ipynb:** Jupyter notebook with commented code for data ingestion, cleaning, and manipulation.

**NYT-analysis.twb:** Tableau workbook for visualization and analysis.

**popular.txt:** List of common words for identifying jargon. Taken from https://github.com/dolph/dictionary/blob/master/popular.txt.

## Jupyter notebook contents
**Archive.org crawling:** Code to crawl Archive.org and find the point at which NYTimes.com started using Optimizely for A/B testing.

**NYT headlines:** Code to pull headlines from the NYT archive API, clean them, and write them into a PostgreSQL table.

**Generating variables:** Code to extract features from headlines and stored to database.
