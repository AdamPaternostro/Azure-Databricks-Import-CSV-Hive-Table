# Azure-Databricks-Import-CSV-Hive-Table
Import data from a CSV into a Hive partitioned and non-partitioned table

## To view the Databricks Notebook
http://htmlpreview.github.com/?https://github.com/AdamPaternostro/Azure-Databricks-Import-CSV-Hive-Table/blob/master/Ingesting-CSV-File-To-Hive%20(generic).html

### Notes
Hive column names cause errors if you use Camel case.  All lowercase column names with underscores seems to work the best.  I have fought too many Hive errors where libraries and such get confused.
