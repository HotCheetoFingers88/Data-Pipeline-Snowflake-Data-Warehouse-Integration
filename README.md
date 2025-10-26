# Data-Pipeline-Snowflake-Data-Warehouse-Integration
A Python-based ETL pipeline that collects, inspects, and loads Labatt datasets into a Snowflake data warehouse for scalable analytics

**Overview**
This project implements a modular ETL pipeline for processing Labatt datasets. It automates data extraction from local or remote sources, performs data inspection and validation, and integrates with a Snowflake Data Warehouse for storage and querying.

**Purpose**
The goal of this pipeline is to streamline Labatt's data ingestion workflow, enabling efficient data transformation and analytics using Snowflake as the cloud backend.

**Tech Stack**

* **Language:** Python 3
* **Data Warehouse:** Snowflake
* **Libraries:** Pandas, Snowflake Connector, Requests
* **Environment:** Virtual environment for isolated dependencies

**Usage / Setup**

1. Clone the repository and activate the Python virtual environment.
2. Run `datasetDownloadScript.py` to fetch and stage the datasets.
3. Use `inspectData.py` to validate dataset integrity.
4. Load validated data into Snowflake by running ETL scripts in `src/`.
5. Configure your Snowflake credentials in a `.env` file or environment variables.


This backend application provides an API layer for controlling and monitoring AGV systems. It enables secure communication between AGV units, control software, and databases, ensuring reliable logistics automation.

**Purpose**
The goal of this backend is to manage fleet data, task assignments, and routing logic for AGV systems in industrial or warehouse environmen
