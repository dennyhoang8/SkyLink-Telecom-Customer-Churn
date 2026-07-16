# Data Dictionary

# SkyLink Telecom Customer Churn Dataset

---

## Overview

This document defines each variable contained in the SkyLink Telecom Customer Churn dataset.

The data dictionary serves as a reference throughout the project by describing the purpose, data type, and business meaning of every column used during data exploration, statistical analysis, machine learning, and dashboard development.

---

| Column | Data Type | Description |
|---------|-----------|-------------|
| CustomerID | String | Unique identifier assigned to each customer. |
| Count | Integer | Reporting field used for counting customer records. |
| Country | String | Customer's country of residence. |
| State | String | Customer's state of residence. |
| City | String | Customer's city of residence. |
| Zip Code | Integer | Customer's ZIP code. |
| Lat Long | String | Combined latitude and longitude coordinates. |
| Latitude | Float | Customer's latitude coordinate. |
| Longitude | Float | Customer's longitude coordinate. |
| Gender | String | Customer gender. |
| Senior Citizen | String | Indicates whether the customer is a senior citizen. |
| Partner | String | Indicates whether the customer has a partner. |
| Dependents | String | Indicates whether the customer has dependents. |
| Tenure Months | Integer | Number of months the customer has remained with the company. |
| Phone Service | String | Indicates whether the customer subscribes to phone service. |
| Multiple Lines | String | Indicates whether the customer has multiple phone lines. |
| Internet Service | String | Type of internet service subscribed to by the customer. |
| Online Security | String | Indicates whether online security service is subscribed. |
| Online Backup | String | Indicates whether online backup service is subscribed. |
| Device Protection | String | Indicates whether device protection service is subscribed. |
| Tech Support | String | Indicates whether technical support service is subscribed. |
| Streaming TV | String | Indicates whether streaming TV service is subscribed. |
| Streaming Movies | String | Indicates whether streaming movie service is subscribed. |
| Contract | String | Customer contract type. |
| Paperless Billing | String | Indicates whether paperless billing is enabled. |
| Payment Method | String | Customer's payment method. |
| Monthly Charges | Float | Monthly amount charged to the customer. |
| Total Charges | Float | Total amount charged since becoming a customer. |
| Churn Label | String | Indicates whether the customer churned (Yes/No). |
| Churn Value | Integer | Numeric representation of churn (1 = Yes, 0 = No). |
| Churn Score | Integer | IBM-generated churn risk score. |
| CLTV | Integer | Estimated Customer Lifetime Value. |
| Churn Reason | String | Reported reason for customer churn (available only for customers who churned). |