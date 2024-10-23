# 🕵️ Crime Data Exploratory Data Analysis (EDA) 🗺️

#### Welcome to the Crime Data EDA project! In this analysis, we dive into a dataset filled with crimes, uncovering key trends and insights that can help us better understand patterns of criminal activity. From visualizing the most common offenses to exploring crime hotspots, this EDA sheds light on how crime fluctuates across time and location. Ready to uncover the data mysteries? Let’s get started!

## ⚡ Tools Used:<br>
<br>

**Pandas & NumPy:** For data manipulation and transformation.<br>
**Seaborn & Matplotlib:** For creating insightful visualizations like bar charts and heatmaps.<br>
**Jupyter Notebook:** For executing and documenting the analysis.<br>
**SQL:** Could be used for database queries (optional).<br>

## 1. 🎯 Purpose of the Analysis <br>
The aim of this analysis is to: <br>

Identify common and rare crimes based on offense types and descriptions.<br>
Explore patterns of crime based on time (hour, day, month, and year).<br>
Analyze geographic trends by district and reporting areas.<br>
Use visualizations to represent complex crime patterns clearly.<br>

## 2. 📋 Understanding the Data<br>
The dataset contains information about crime incidents, such as:<br>
<br>
**INCIDENT_NUMBER:** A unique identifier for each crime.<br>
**OFFENSE_CODE and OFFENSE_DESCRIPTION:** Describes the crime.<br>
**DISTRICT and STREET:** Location-based information for each incident.<br>
**OCCURRED_ON_DATE:** The date and time when the crime took place.<br>
**Lat and Long:** Coordinates of the crime.<br>
**SHOOTING:** Whether a shooting was involved in the crime.<br>
<br>
Data Shape:<br>
Total rows: 319,050<br>
Columns: 17<br>

## 3. 🔧 Challenges Faced<br>
Working with real-world data is always tricky! Here’s how we tackled the challenges:<br>
<br>
**Handling Missing Data:** Columns like "SHOOTING," "Lat," and "Long" had missing values. We either dropped or filled them as necessary.<br>
**Data Transformation:** Converted date columns into datetime format for easier analysis.<br>
**Duplicates:** Removed 23 duplicate records to ensure clean data.<br>
**Encoding:** Tested different encodings to correctly read the dataset without errors.<br>

## 4. 📈 Key Performance Indicators (KPIs)<br>
To get an overview of the crime data, we focused on these KPIs:<br>
<br>
**Most Common Offense Groups:** Identify the crime categories that happen the most.<br>
**Least Common Offense Groups:** Crimes that rarely occur, such as human trafficking.<br>
**Crime Trends by Year, Month, and Day:** Analyze how crimes change over time.<br>
**Crime Hotspots:** Which districts and streets see the most crime.<br>
**Hourly Crime Patterns:** When are crimes most likely to occur during the day?<br>

## 5. 🔍 Detailed Analysis & Insights<br>
<br>

**🏆 Most Common Crimes:** <br>
Motor Vehicle Accident Response is the most common crime, making up 11.6% of all incidents.<br>
Recommendation: Focus on traffic management and safety to reduce motor vehicle incidents.<br>
<br>

**🔬 Least Common Crimes:** <br>
Human Trafficking - Involuntary Servitude and Biological Threat are among the rarest, with just 2 incidents each.<br>
<br>

**📅 Crime Trends by Year:** <br>
2017 had the highest number of crimes (100,884), while 2018 saw a decline (65,685 incidents).<br>
Recommendation: Investigate why crime declined in 2018 to replicate successful strategies.<br>
<br>

**🕑 Crime by Day and Hour:** <br>
Friday is the busiest day for crime, followed by Wednesday and Thursday.<br>
Crimes peak during the afternoon and evening hours (12–6 PM).<br>
Recommendation: Increase police presence on Friday afternoons and evenings to deter crime.<br>
<br>

**📊 District-Wise Heatmap:** <br>
The districts B2 and D4 report the most crimes.<br>
Recommendation: Focus law enforcement efforts in these districts to improve safety.<br>

## 6. 🎯 Creative Business Insights <br>
<br>

**Actionable Insights for Crime Prevention:** <br>
**Targeted Policing:** Focus on high-crime districts like B2 and D4, especially during peak crime hours.<br>
**Traffic Safety Programs:** Reduce vehicle accidents, which are the most common type of crime.<br>
**Community Engagement:** Since crimes are less common on Sundays, this could be a good day for community-building events.<br>
