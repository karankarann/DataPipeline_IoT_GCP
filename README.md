# Building an IoT Analytics Data Pipeline on Google Cloud Platform

This project focused on creating a robust and scalable pipeline for analyzing IoT data streams using Google Cloud services. The workflow involved:

## Connecting and Managing Devices:

Used Cloud IoT Core to connect and manage simulated MQTT-based devices (using simulated devices)

## Data Ingestion:

Utilized Cloud Pub/Sub to ingest streams of data from Cloud IoT Core. This setup enabled real-time messaging and facilitated the seamless flow of data through the pipeline.

## Data Processing:

Implemented Cloud Dataflow to process the ingested data in real-time. This involved applying various transformations and aggregations, ensuring the data was ready for analysis.

## Data Analysis:

Used BigQuery to analyze the processed data. Leveraged its powerful SQL-based querying capabilities to generate insights and visualizations that demonstrated the value of IoT data in understanding device behavior and performance.

The project showcased how Google Cloud’s fully managed services can be effectively integrated to manage and analyze data from millions of globally distributed IoT devices. By utilizing Cloud IoT Core, Pub/Sub, Dataflow, and BigQuery, the project provided a comprehensive solution for transforming raw IoT data into actionable insights.

--

## Information on project key-terms

--

The term Internet of Things (IoT) refers to the interconnection of physical devices with the global Internet. These devices are equipped with sensors and networking hardware, and each is globally identifiable. Taken together, these capabilities afford rich data about items in the physical world.

Cloud IoT Core is a fully managed service that allows you to easily and securely connect, manage, and ingest data from millions of globally dispersed devices. The service connects IoT devices that use the standard Message Queue Telemetry Transport (MQTT) protocol to other Google Cloud data services.

Cloud IoT Core has two main components:

A **device manager** for registering devices with the service, so you can then monitor and configure them.
A **protocol bridge** that supports MQTT, which devices can use to connect to Google Cloud.

We will perform the following:

- Connect and manage MQTT-based devices using Cloud IoT Core (using simulated devices)

- Ingest a stream of information from Cloud IoT Core using Cloud Pub/Sub.

- Process the IoT data using Cloud Dataflow.

- Analyze the IoT data using BigQuery.
