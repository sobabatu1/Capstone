# Capstone Project Summary

The project focused on creating a comprehensive end-to-end data processing system using the Google Cloud Platform (GCP). Utilizing GCP resources like Pubsub, Dataflow, BigQuery, and Looker Studio, real-time cryptocurrency data was sourced from coingecko.api and historical data from kaggle.com. The data underwent a six-step transformation process, which included reading from Pubsub, converting JSON to tuple structures, setting data types, computing rolling averages, predicting future prices using the Prophet ML library, and finally writing to BigQuery. The real-time data was stored in BigQuery for further analysis. For visualization, Looker Studio was employed, showcasing price changes over time using area charts and offering detailed tables with real-time cryptocurrency information, moving averages, and forecasted prices.
