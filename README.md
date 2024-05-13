# GIZ-Anti-Corruption-Training


# Data Analysis Report

## Data Overview

### Columns in the Dataset:
- **Course**: The type of course.
- **Type**: The type category of the course.
- **No. of participants**: The number of participants in each course.
- **Male**: The number of male participants.
- **Female**: The number of female participants.
- **Chisinau**: The number of participants from Chisinau.
- **Hancesti**: The number of participants from Hancesti.

### Data Info:
```plaintext
<class 'pandas.core.frame.DataFrame'>
Index: 5 entries, 19.02.2024 to 27.03.2024
Data columns (total 7 columns):
 #   Column               Non-Null Count  Dtype  
---  ------               --------------  -----  
 0   Course               5 non-null      object 
 1   Type                 5 non-null      object 
 2   No. of participants  5 non-null      float64
 3   Male                 5 non-null      float64
 4   Female               5 non-null      float64
 5   Chisinau             5 non-null      float64
 6   Hancesti             5 non-null      float64
dtypes: float64(5), object(2)
memory usage: 320.0+ bytes
```

### Data Preview:
| Date       | Course          | Type       | No. of participants | Male | Female | Chisinau | Hancesti |
|------------|-----------------|------------|---------------------|------|--------|----------|----------|
| 19.02.2024 | Course A        | Type 1     | 30.0                | 15.0 | 15.0   | 20.0     | 10.0     |
| 25.02.2024 | Course B        | Type 2     | 25.0                | 10.0 | 15.0   | 15.0     | 10.0     |
| 03.03.2024 | Course C        | Type 3     | 20.0                | 12.0 | 8.0    | 10.0     | 10.0     |
| 15.03.2024 | Course D        | Type 1     | 35.0                | 20.0 | 15.0   | 25.0     | 10.0     |
| 27.03.2024 | Course E        | Type 2     | 40.0                | 22.0 | 18.0   | 30.0     | 10.0     |

## Visualizations

### Participation Trend:
The following plot shows the trend in the number of participants over time:

[Participation Trend](sandbox:/mnt/data/participation_trend.html)

**Description**:
- The plot indicates the fluctuation in participant numbers across different dates.
- Notable peaks and troughs may correspond to specific events or times of interest.

### Gender Distribution Across Courses:
The following plot shows the gender distribution across different courses:

[Gender Distribution](sandbox:/mnt/data/gender_distribution.html)

**Description**:
- The bar chart displays the number of male and female participants for each course.
- This can help in understanding the gender diversity in different types of courses offered.

## Summary of Findings:
- **Participation Trend**: The trend line plot shows variations in the number of participants over different dates, which can help in identifying patterns or anomalies.
- **Gender Distribution**: The bar chart provides a clear representation of gender distribution across courses, highlighting areas with higher or lower gender diversity.

## Conclusion:
The data analysis reveals important insights into participation trends and gender distribution across courses. Such insights can be valuable for strategic planning, resource allocation, and enhancing gender diversity in future courses.
