---
title: Data Engineer Code Wall
taxonomy:
    category: tutorials
author: "Himanshu Aggarwal"
description: "Code Notes or tutorials for a data engineer"
post_status: draft
---

 
> Code Tutorials -  Code blocks that are extensively required, while working as a data engineer.

<br/>

---
## Big Data 
---



<table>
<tr>
	<th align="left"> Bringing/Syncing data into your Big data Environment </th>
</tr>
<tr> 
	<td>
		<ul>
			<li>Fetching data from OLTP on daily basis into s3/hdfs</li>
			<li>Fetching data from cassandra into s3/hdfs</li>
		</ul>
	</td>
</tr>
</table>

<table>
<tr>
	<th align="left"> Creating Data Pipelines </th>
</tr>
<tr> 
	<td>
		<ul>
			<li>Creating your first ETL data pipeline on AWS</li>
		</ul>
	</td>
</tr>
</table>

<table>
<tr>
	<th align="left"> Making Data available for analysis </th>
</tr>
<tr> 
	<td>
		<ul>
			<li>Basics</li><li>Connecting Tableau with your DataMart [ RDS / Redshift ] via JDBC</li>
			<li>Connecting PowerBI with DataMart [ RDS / Redshift ] via JDBC</li>
		</ul>
	</td>
</tr>
</table>

<br />

---
## Tools
---

<table>
	<tr>
		<th align="left"> Azkaban </th>
	</tr>
	<tr>
		<td>
			<ul>
				<li>Setting up azkaban on your local</li>
				<li>Running selected azkaban jobs</li>
			</ul> 
		</td>
	</tr>
</table>

<table>
	<tr>
		<th align="left"> Spark </th>
	</tr>
	<tr>
	<td>
		<ul>
			<li>Your first program with spark</li>
			<li>Connecting databases via JDBC in pyspark
			<ul>
				<li>Connecting postgres.</li> 
				<li>Connecting Mysql</li> 
				<li>Connecting redshift</li> 
			</ul> 
			<li> Connecting Cassandra </li>
			<li> Loading data from Filesystem (local/HDFS/S3) </li> 
			<li> Working with UDFs </li>
		</ul>
		</td>
	</tr>
</table>

<table>
	<tr>
		<th align="left"> Redshift </th>
	</tr>
	<tr>
	<td>
		<ul> 
			<li> Creating a table (with efficient distribution style and sort keys) </li> 
			<li> Unload Query (downloading data from redshift table to s3) </li> 
			<li> Copying data to Redshift </li> 
			<li> Creating UDFs </li> 
			<li> Querying Data From S3 </li> 
			<ul> 
				<li> Redshift Spectrum </li> 
				<li> Creating External Schema </li> 
				<li> Creating External Table </li> 
			</ul> 
		</ul> 
		</td>
	</tr>
</table>


<table>
	<tr>
		<th align="left"> Redshift </th>
	</tr>
	<tr>
	<td>
		<ul> 
			<li> Creating a table (with efficient distribution style and sort keys) </li> 
			<li> Unload Query (downloading data from redshift table to s3) </li> 
			<li> Copying data to Redshift </li> 
			<li> Creating UDFs </li> 
			<li> Querying Data From S3 </li> 
			<ul> 
				<li> Redshift Spectrum </li> 
				<li> Creating External Schema </li> 
				<li> Creating External Table </li> 
			</ul> 
		</ul> 
		</td>
	</tr>
</table>


<table>
	<tr>
		<th align="left"> S3 </th>
	</tr>
	<tr>
	<td>
		<ul> 
			<li> Forecasting your S3 costs in a long term </li> 
			<li> Optimising S3 Cost </li> 
			<li> Archiving data into Glacier or Glacier Deep Archive</li> 
			<ul> 
				<li> Redshift Spectrum </li> 
				<li> Creating External Schema </li> 
				<li> Creating External Table </li> 
			</ul> 
		</ul> 
		</td>
	</tr>
</table>


<table>
	<tr>
		<th align="left"> EMR </th>
	</tr>
	<tr>
	<td>
		<ul> 
			<li> Basics </li> 
			<li> Creating Transient EMR clusters on daily basis (via AWS SDK) </li> 
		</ul> 
		</td>
	</tr>
</table>

