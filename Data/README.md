# Data folder

The raw NYC TLC Yellow Taxi Trip Record data is not stored in this repository
because the files are very large.

Official data source:

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Download instructions

1. Open the official TLC data page.
2. Download the selected Yellow Taxi Parquet files.
3. Place the downloaded files in this local data/ folder.
4. Do not upload the large raw files to GitHub.
5. Update the file path in the PySpark script if necessary.

Expected file pattern:

data/yellow_tripdata_2024-01.parquet
data/yellow_tripdata_2024-02.parquet
