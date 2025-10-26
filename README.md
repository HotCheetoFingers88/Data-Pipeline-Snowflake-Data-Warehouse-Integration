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

---

###  Web Crawler — JSoup Content Scraper

**Short Description:** A Java crawler that uses the JSoup library to extract and parse structured web content from target websites.

#### README_NEW.md

**Overview**
This lightweight Java application uses the JSoup HTML parser to crawl web pages, extract data, and process it for analysis or indexing. The crawler can be configured to target specific domains and HTML structures.

**Purpose**
Designed to simplify data collection from web pages, this project provides a foundation for building SEO tools, data mining scripts, or research crawlers.

**Tech Stack**

* **Language:** Java
* **Library:** JSoup 1.17.2
* **IDE:** Visual Studio Code / IntelliJ

**Usage / Setup**

1. Place the `jsoup-1.17.2.jar` file in your Java project classpath.
2. Compile using:

   ```bash
   javac -cp jsoup-1.17.2.jar WebCrawler.java
   ```
3. Run using:

   ```bash
   java -cp .:jsoup-1.17.2.jar WebCrawler
   ```
4. Edit the code to specify your target URLs or HTML tags to extract.

---

### AGV Backend — Spring Boot Fleet Management API

**Short Description:** A Spring Boot backend service managing Automated Guided Vehicle (AGV) data, routes, and operations through a RESTful API.

#### README_NEW.md

**Overview**
This backend application provides an API layer for controlling and monitoring AGV systems. It enables secure communication between AGV units, control software, and databases, ensuring reliable logistics automation.

**Purpose**
The goal of this backend is to manage fleet data, task assignments, and routing logic for AGV systems in industrial or warehouse environments.

**Tech Stack**

* **Language:** Java
* **Framework:** Spring Boot
* **Build Tool:** Maven
* **Configuration:** application.properties
* **Environment:** Cross-platform (Linux/Windows)

**Usage / Setup**

1. Ensure Java 17+ and Maven are installed.
2. Navigate to the project directory.
3. Build the project using:

   ```bash
   mvn clean install
   ```
4. Run the Spring Boot app:

   ```bash
   ./mvnw spring-boot:run
   ```
5. Access the API at `http://localhost:8080/api/`.
6. Refer to `HELP.md` for API endpoints and configuration notes.
