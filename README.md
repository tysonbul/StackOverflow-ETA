# StackOverflow-ETA

This is the replication package for the paper written on estimating StackOverflow  response times based on a questions tags. The following are the steps required to replicate the methodology.

## Data Collection

Use these queries for the desired time range in which you wish to collect data. Some may require that you gather your data in chunks as the Data Explorer only allows 50,000 rows to be returned at a time.

- Median response time: http://data.stackexchange.com/stackoverflow/query/738312/custom-median-of-stackoverflow-questions
- Calculate ASR: http://data.stackexchange.com/stackoverflow/query/736161/custom-active-subscribers-for-a-tag
- Calculate RSR: http://data.stackexchange.com/stackoverflow/query/736158/custom-responsive-subscribers-for-a-tag
- Response times: http://data.stackexchange.com/stackoverflow/query/738333/custom-questions-between-time-and-response-times

Save the results to CSV's and save them in the data folder

## Producing results

Use the Jupiter Notebooks supplied in the src/ folder. Replace the file names with your newly respective collected data. Run the Notebooks and customize as needed.