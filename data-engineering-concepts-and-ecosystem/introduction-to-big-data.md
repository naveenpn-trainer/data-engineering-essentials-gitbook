# Introduction to Big Data

## Introduction

> **Big Data** refers to the data which is a **large, fast** and complex type of **structured, semi structured, unstructured data** generated from a variety of different sources, which becomes **difficult to store and process using a traditional processing system**.

## Classification of Big Data

Big Data is classified into 3 different categories.

1. **Structured Data** - Refers to the data that has a proper structure associated with it. For example, the data that is present within the databases, the CSV files, and the excel spreadsheets can be referred to as Structured Data.
2. **Semi-Structured Data** : refers to the data that does not have a proper structure associated with it. For example, the data that is present within the emails, the log files, and the word documents can be referred to as Semi-Structured Data.
3. **Unstructured Data** : refers to the data that does not have any structure associated with it at all. For example, the image files, the audio files, and the video files can be referred to as Unstructured Data.

<img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXclO1e088KB30AOEm6TgHYFE8vTQRfoM2MzcretViuraLKUGIvAIAuNNowZhmvv1hGDsEOUBaKYy7C2B8oufHxa8jTHQscq5Cya6Js5AUTPDiDpFzkcBg4tnKZY7C2tIY7dq0pWzzla32uGkSovYw8kPQs?key=WVTBLSgKP1xKDvxfmnhf1w" alt="img" style="zoom:50%;" />

## Characteristics of Big Data

Big Data is categorized by 3 important characteristics.

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdhDkzwrnLxtLrmvgrUG0dZ3shG4HJ0fT7kF67E0is4elj0sdTP-3QY33Pr8siIUtBK3oGSHrzy6hQLA8ZRtFWUNj1BDJ0yucUvmKBuRacy5zAijTSKpNlkVlDs_nSdInZ9jaNZ5eAd2d5PVhsL5eM5hjBt?key=WVTBLSgKP1xKDvxfmnhf1w)

1. **Volume** : refers to the amount of data that is getting generated.
2. **Velocity** : refers to the speed at which the data is getting generated.
3. **Variety** : refers to the different types of data that is getting generated.
4. **Veracity** : refers to messiness and trustworthiness of the data. the quality and validity of the data.

## Traditional Processing System

- Relational database management systems (RDBMS) have been the one-stop solution to all storage needs. They support Structured Query Language (SQL) to make changes to the database. 
- Data in an RDBMS is stored in the form of tables with rows and columns. 

**Drawbacks of RDBMs**

1. They cannot accommodate huge volumes of data. To handle large volumes of data, RDBMSes have to add more storage or more processing units to scale up vertically. Horizontal scalability involves adding new servers and spreading the load across them. **It is difficult to run read/write operations in parallel in an RDBMS; so, it is scaled vertically.**
2. Most of the data generated today are in a semi-structured or an unstructured format. Relational databases cannot store unstructured data because RDBMSes are schema-oriented and can store only structured data in the form of tables.
3. Big data is generated at a very high velocity. Relational databases cannot provide high velocity, i.e., they cannot deliver the optimal speed at which big data is generated and needs to be processed.

## Traditional Approach for Storing and Processing Big Data

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXf6Y-NEzaUBM5YXp5fhOG0Dh2uBF-yrngDVPuOqRN-kQabZSmv_ZXX51rjAE84HTLCFj63e_74kjoREtPBOihzYxy0jKfWKQEDwLHccmzMbR_THUsj2OiM5mA3Lt6eyHRAg-YmVbMfC0y417B97O3_apBp_?key=WVTBLSgKP1xKDvxfmnhf1w)

1. The data generated out of the organizations, financial institutions such as banks or stock markets and the hospitals is usually given as an input to the ETL system.
2. The ETL system then extracts the data and converts the data into a proper format. This data is then loaded into the database.
3. The end users can generate reports and perform analytics by acquiring this data.
4. As the data grows it becomes difficult to manage and process it using the traditional approach. This is a fundamental drawback of using the traditional approach.

**Drawbacks of using traditional approach:**

1. **Expensive** - It is an expensive system. It requires a lot of investment for implementing or upgrading the system. So, it is generally used by large companies.
2. **Scalability** - As the data grows expanding the system becomes a challenging task.
3. **Time-consuming** - It takes a lot of time to extract and process valuable information from this data.

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdNfQoK0mtsuCdCVcc-aQuGQR4NPzVovPh3_23fkEqcYAkq8BjLFtgFhHwDtapOK2uNZKnyUp9XFsEnFsp17LvVImyevUHw0xL_lHrbpd_Yb6I9uJDqM42jh9CPn5oqBATCUpaIUhbTLdaupzd7c57zyQHt?key=WVTBLSgKP1xKDvxfmnhf1w)