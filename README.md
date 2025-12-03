# Identifying-Key-Patterns-Platform-Genre-ESRB-for-Global-Video-Game-Sales
Identify patterns that determine whether a game is successful. This will enable you to detect promising projects and plan advertising campaigns.

## Requirements
The libraries are listed in the file requirements.txt.

## Analysis
- Platforms showed high sales around the year 2010 after being launched in 2005, as is the case with X360.
- It subsequently experienced a decline, reaching its minimum in 2015.
- The PS4 platform (which launched around 2013, as PS5 launched later), peaked around 2015, which is 2-3 years after its launch.
- Platforms that reached their peak sales did so after 2-3 years from their launch, followed by a dramatic decrease in sales.
- Platforms that started in the 80s persisted until 2016-2017.
- The line chart was chosen to observe the platform's growth cycle.

<img width="998" height="574" alt="image" src="https://github.com/user-attachments/assets/da5b9059-8a43-4678-8b5a-c59e5374c0fe" />

- The platform with the most outliers is DS, but it shows less variation (lower spread) within the data.
- PS2 is the platform with the highest total sales, having a mean of approximately 0.25 million USD in total sales. Other platforms such as X360, PS3, and PS have similar means (around $0.25 million USD), but with a larger range (higher variability).
- The platforms Wii, DS, GBA, and PS4 have average sales below $0.25 million USD.
- It can be observed that the data distribution for each platform is positively skewed, with a tail to the right.
- It can also be determined that the majority of sales for these platforms are concentrated in small amounts, rather than large amounts, as shown in the graphs.

<img width="1000" height="553" alt="image" src="https://github.com/user-attachments/assets/1c50645b-5bf4-40c6-9360-6da16bee160f" />

Correlation on the Wii platform.
- Correlation between sales and critic score: 0.17
- Correlation between sales and user score: 0.11
- The charts look similar; there is an outlier with an approximate total sales value of 80. What differs is the scale of both scores (critic and user); however, they appear to have the same distribution.
- The correlation between sales and score for each is less than 0.2, which indicates a weak positive correlation between sales and the score.
- The analysis could be improved if we remove the outliers from sales above approximately 20 to 90, to calculate a correlation based on the average of the sales data.
  
<img width="998" height="485" alt="image" src="https://github.com/user-attachments/assets/4de1431b-112d-496a-ae11-2233a5a658f9" />




