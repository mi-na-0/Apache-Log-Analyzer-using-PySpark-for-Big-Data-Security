# Apache Log Analyzer Using PySpark

## Project Description

This project presents a scalable solution for analyzing web server logs using Apache Spark through its Python API, PySpark. Designed as part of a Big Data Security initiative, the application processes large volumes of Apache HTTP access logs to extract actionable insights relevant to system monitoring and cybersecurity.

The log data, typically unstructured, is parsed using regular expressions to extract meaningful fields such as IP address, timestamp, HTTP request method, requested URL, response status code, and data transfer size. PySpark’s distributed computing capabilities enable efficient processing, making the solution suitable for high-volume log environments.

Following data extraction, the system performs several analytical operations, including identification of high-frequency IP addresses, most requested resources, and error code distributions. Results are visualized using Matplotlib to support interpretability and reporting. The project emphasizes anomaly detection by filtering client- and server-side error codes (4xx and 5xx), which are often indicators of malicious activity or system misconfiguration.

The solution is implemented in Google Colab for accessibility and ease of deployment, requiring no local Spark installation. This project demonstrates how big data frameworks can support cybersecurity analysis by transforming raw server logs into structured intelligence.

## Technologies Used

- Apache Spark
- PySpark
- Google Colab
- Regular Expressions (Regex)
- Matplotlib
- Pandas
- Apache HTTP Access Logs

## Author

**Mina Fatima**  
BS Cyber Security and Digital Forensics  
Semester Project: Big Data Security - Log Analyzer using Apache Spark

