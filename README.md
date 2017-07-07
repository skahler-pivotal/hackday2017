# Greenplum and AWS Kinesis/S3

This demo highlights the use of Kinesis to create streaming data which dumps to S3. The data can then be read by GPDB as S3 external tables

Requirements
 * GPDB Cluster ( running in S3 optional )
 * Kinesis pipeline using the demo ticker source output CSV to S3

TBD
 * Capture Kinesis pipeline setup steps

Assets
 * KinesisDemo.json - Zepplin Notebook with queries and setup steps
 * KinesisFilter.txt - Used as the filter in Kinesis analytics step to ensure rowtime is added to the CSV output
