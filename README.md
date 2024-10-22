# Building Modern Data Applications Using Databricks Lakehouse

<a href="https://www.packtpub.com/en-us/product/building-modern-data-applications-using-databricks-lakehouse-9781804612873"><img src="https://content.packt.com/B22011/cover_image.jpg" alt="no-image" height="256px" align="right"></a>

This is the code repository for [Building Modern Data Applications Using Databricks Lakehouse](https://www.packtpub.com/en-us/product/building-modern-data-applications-using-databricks-lakehouse-9781804612873), published by Packt.

**Develop, optimize, and monitor data pipelines on Databricks**

## What is this book about?
Learn the latest Databricks features, with up-to-date insights into the platform. This book will develop your skills to build scalable and secure data pipelines to ingest, transform, and deliver timely, accurate data to drive business decisions.

This book covers the following exciting features:
* Deploy near-real-time data pipelines in Databricks using Delta Live Tables
* Orchestrate data pipelines using Databricks workflows
* Implement data validation policies and monitor/quarantine bad data
* Apply slowly changing dimensions (SCD), Type 1 and 2, data to lakehouse tables
* Secure data access across different groups and users using Unity Catalog
* Automate continuous data pipeline deployment by integrating Git with build tools such as Terraform and Databricks Asset Bundles

If you feel this book is for you, get your [copy](https://www.amazon.com/Building-Modern-Applications-Databricks-Lakehouse/dp/1801073236/ref=tmm_pap_swatch_0?_encoding=UTF8&dib_tag=se&dib=eyJ2IjoiMSJ9.lgIecM0Ee0JST_roP0tVisdsDureV0zEHPilTJWeN50.92-jnQE1HVeLCm04AGkW20I1lWkPIHEdggtpMma0_oM&qid=1729572915&sr=8-1) today!
<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>
## Instructions and Navigations
All of the code is organized into folders. For example, chapter01.

The code will look like the following:
```
@dlt.table(
    name="random_trip_data_raw",
    comment="The raw taxi trip data ingested from a landing zone.",
    table_properties={
        "quality": "bronze"
    }
)
```

**Following is what you need for this book:**
This book is for data engineers looking to streamline data ingestion, transformation, and orchestration tasks. Data analysts responsible for managing and processing lakehouse data for analysis, reporting, and visualization will also find this book beneficial. Additionally, DataOps/DevOps engineers will find this book helpful for automating the testing and deployment of data pipelines, optimizing table tasks, and tracking data lineage within the lakehouse. Beginner-level knowledge of Apache Spark and Python is needed to make the most out of this book.

## To get the most out of this book
While not a mandatory requirement, to get the most out of this book, it’s recommended that you have
beginner-level knowledge of Python and Apache Spark, and at least some knowledge of navigating
around the Databricks Data Intelligence Platform. It’s also recommended to have the following
dependencies installed locally in order to follow along with the hands-on exercises and code examples
throughout the book:(Chapter 1-10).

### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-10 | Python 3.6+ | Windows, macOS, or Linux |
| 1-10 | Databricks CLI 0.205+ | Windows, macOS, or Linux |

Furthermore, it’s recommended that you have a Databricks account and workspace to log in, import
notebooks, create clusters, and create new data pipelines. If you do not have a Databricks account,
you can sign up for a free trial on the Databricks [website](https://www.databricks.com/try-databricks).

## Related products
* Databricks Certified Associate Developer for Apache Spark Using Python [[Packt]](https://www.packtpub.com/en-us/product/databricks-certified-associate-developer-for-apache-spark-using-python-9781804619780) [[Amazon]](https://www.amazon.com/Databricks-Certified-Associate-Developer-Apache/dp/1804619787/ref=sr_1_1?dib=eyJ2IjoiMSJ9.hz6OGLsadzx-xkkwOuNR86dhlhCOwiuIYWSoaaBoelPXbZhfgDsJiXPnB27ZybWK.ZcUq4e1bwTY8UdNiHszmcgRS6tUUTx-HFjq0iBDVQZI&dib_tag=se&keywords=Databricks+Certified+Associate+Developer+for+Apache+Spark+Using+Python&qid=1729573335&sr=8-1)

* Machine Learning Security Principles [[Packt]](https://www.packtpub.com/en-us/product/machine-learning-security-principles-9781804618851) [[Amazon]](https://www.amazon.com/Machine-Learning-Security-Principles-applications/dp/1804618853/ref=sr_1_1?crid=2T7PSUVLXNUZO&dib=eyJ2IjoiMSJ9.HtII74E_8N68kFc39-KHjVCw-cyq6-ojYfLL6WE_cdBzgvevpUnZbjqMzfOLKOXsQF-xtUYDFTlgJ7Dq9gjmhS0FvOMpIF96-X1dxzp6AtrmtwtJ1gQ_cems8xcAF-YEJg8lW3PhpbScOhQ0XnlHY2ZzIfmRcHIQa7kumw_Rzk0zdpYSVm07GJrJVYzhMUNCAUDpU5Di3SD2rWSxUJwI0A2rkTL8387gGXY-CTczRGc.WyHTg0002U9-nsQ8Zf6G7Lt7BjMZ6Us_c4f0lMT4ETo&dib_tag=se&keywords=Machine+Learning+Security+Principles&qid=1729573426&sprefix=machine+learning+security+principles%2Caps%2C386&sr=8-1)

## Get to Know the Author
**Will Girten** 
 is a lead specialist solutions architect who joined Databricks in early 2019. With over a decade of experience in data and AI, Will has worked in various business verticals, from healthcare to government and financial services. Will’s primary focus has been helping enterprises implement data warehousing strategies for the lakehouse and performance-tuning BI dashboards, reports, and queries. Will is a certified Databricks Data Engineering Professional and Databricks Machine Learning Professional. He holds a Bachelor of Science in computer engineering from the University of Delaware.
