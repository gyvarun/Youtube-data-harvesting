**YOUTUBE DATA HARVESTING AND WAREHOUSING**

**INTRODUCTION**

The objective is analyzing the YouTube channels data by extracting form YouTube using YouTube API key. The application gives the various information about channels and their video analysis.

**Python Libraries**

The following mentioned libraries are used to build the application

**YouTube API libraries**:	import googleapiclient.discovery, from googleapiclient.discovery import build

**File handling libraries**:	import json, import re

**MongoDB**:	import pymongo

**SQL libraries**:	import mysql.connector, import sqlalchemy, from sqlalchemy import create_engine, import pymysql

**Pandas, Numpy**:	import pandas as pd, import numpy as np

**Dash board libraries**-**Streamlit, Seaborn, Matplotlib**:	import streamlit as st, import seaborn as sns, from matplotlib import pyplot as plt

**GUIDE** 

**1.	Data Collection** – The data collection tab on the dashboard is for collecting the channel data from YouTube and store it in the MongoDB.
<img width="960" alt="DC" src="https://github.com/gyvarun/Youtube-data-harvesting/assets/162896993/d4f01691-c1d3-4dc0-8001-4e49ae75215e">

**2.	Data Migration** – The data migration tab on the dashboard is for migrating the channel data from MongoDB to MySQL.
<img width="952" alt="DM" src="https://github.com/gyvarun/Youtube-data-harvesting/assets/162896993/93bace4d-e38e-4351-86d0-c4adffd144f0">

**3.	Channel Analysis** – The channel analysis tab on the dashboard gives the information of the migrated channels for the set of predefined questions.
<img width="959" alt="CA" src="https://github.com/gyvarun/Youtube-data-harvesting/assets/162896993/641f2212-bf8d-4744-a78f-895e64ed8d0b">

