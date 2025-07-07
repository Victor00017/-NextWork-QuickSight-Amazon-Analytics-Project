## 📥 Setup Guide

1. **Clone this repo**
   ```bash
   git clone https://github.com/Victor00017/NextWork-QuickSight-Amazon-Analysis-Project.git
   cd NextWork-QuickSight-Amazon-Analysis-Project

   Upload dataset to S3
   aws s3 cp netflix_titles.csv s3://your-s3-bucket/path/

   Create QuickSight data source

In QuickSight Console: Manage data → New data set → S3

--Point to the S3 CSV file and import.

Build analyses in QuickSight

--Open the dataset in QuickSight

Create visuals:

--Bar chart: count by type or release_year

--Donut chart: distribution of movie vs TV show

--Table: top N directors or genres

--Line chart: time-series of releases or trends

Publish dashboard

--Use Publish dashboard option in QuickSight for sharing or embedding.








 ## Resources
NextWork QuickSight guide – Step-by-step tutorial on linking S3 to QuickSight 
community.nextwork.org
+9
medium.com
+9
link.nextwork.org
+9

AWS Documentation – QuickSight User Guide
