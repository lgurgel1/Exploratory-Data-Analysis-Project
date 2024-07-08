# Exploratory-Data-Analysis-Project

(See the project in detail in the project.ipynb file, where all the steps are there.)

## Connecting with the Data Analytics Journey

This project is part of my Data Analytics learning journey, as described in my original repositorie [Data-Analytics](https://github.com/lgurgel1/Data-Analytics). This repository covers topics from basic Python to cloud computing and big data, and includes several hands-on projects to consolidate learning. Explore the repository to follow the evolution of this and other projects!

# Data Analysis Project: Exploratory Data Analysis of Logistics

## Topics
1. Contexto
2. Pacotes e Bibliotecas
3. Coleta de Dados
4. Exploração de Dados
5. Verificação da Estrutura
6. Enriquecimento dos Dados
7. Visualização dos Dados

## 1. Context
Loggi, a Brazilian tech startup focused on logistics, began operations in 2013 with document deliveries and expanded to e-commerce in 2015 and food deliveries in 2017. Facing challenges such as route optimization and efficient delivery allocation, this project aims to address these issues in Brasília through exploratory data analysis.

## 2. Packages and Libraries
Packages used:
```python
import geopandas
import geopy
from geopy.extra.rate_limiter import RateLimiter
from geopy.geocoders import Nominatim
import json
import matplotlib.pyplot as plt
import numpy as np
import os
import pandas as pd
import seaborn as sns
```
## 3. Data Collection
We collect the data necessary for exploration and manipulation

## 4. Data Exploration
Initial analysis

## 5. Structure Verification

Verification of the DataFrame's integrity and consistency:
<ul>
<li>Inspection of the schema and structure.</li>
<li>Checking for null values.</li>
</ul>

## 6. Data Enrichment
Transformation of longitude and latitude coordinates into textual descriptions (reverse geocoding) of hub and delivery columns.

## 7. Data Visualization
Visualization of delivery data:
<ul>
<li>Maps and charts to reveal patterns and insights.</li>
<li>Analysis of geographic distribution and hub locations</li>
</ul>
