# data_engineering_spotify_glue_snowflake
In this project, I created an ETL pipeline that efficiently extracts, transforms, and loads data from the Spotify API.

## Project Overview:
I utilized AWS Lambda to extract data from the Spotify API and stored the raw data in Amazon S3. By setting up AWS EventBridge, I scheduled Lambda functions to automatically extract data at specific intervals. To transform this data, I used AWS Glue, writing transformation jobs that automatically move processed data from raw to transformed folders in S3. Finally, I set up a Snowpipe in Snowflake for automated data ingestion, enabling further analysis and serving as a robust data warehouse.
