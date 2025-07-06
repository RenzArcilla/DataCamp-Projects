# Exploring London’s Travel Network

This project analyzes public transport journey data in London using a dataset from Transport for London (TfL). The data includes monthly journey volumes across various transport types, such as Underground, DLR, buses, and the Emirates Airline cable car.

Using SQL queries on a Snowflake database, the project investigates which transport modes are most used, when the Emirates Airline was most popular, and which years saw the lowest Underground & DLR usage.

## Project Objectives
- Identify the **most popular transport types** in London.
- Find the **top 5 months** for Emirates Airline journey volume.
- Discover the **least active years** for Underground & DLR usage.

## Dataset
- **Snowflake Table: `TFL.JOURNEYS`**
  - Data includes monthly journey counts (in millions) by transport mode.
  - Key columns: `MONTH`, `YEAR`, `JOURNEY_TYPE`, `JOURNEYS_MILLIONS`, `REPORT_DATE`, `DAYS`


## Tools Used
- SQL (Snowflake)  
- Data aggregation and filtering  

---

> This project provides insight into how Londoners use public transport, helping to understand demand trends across different services.
