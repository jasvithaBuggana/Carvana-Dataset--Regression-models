## Carvana Dataset Exploratory Data Analysis (EDA)

## Overview

This EDA focuses on the Carvana dataset, specifically the 'training.csv' file, providing insights into the dataset's characteristics and identifying potential leading indicators of a bad buy.

## Vehicle Year Statistics

- The mean vehicle year in the dataset is 2005.
- The range of vehicle years spans from 2001 to 2010.
- The average age of vehicles is 4.17 years, with the youngest being brand new (0 years old) and the oldest being 9 years old.

## Visual Analytics for Identifying Bad Buys

1. **Time-Series Analysis:**
   - Peaks observed on Sept 2009, Feb 2010, and Jan 2011 in the purchase date plot suggest potential patterns related to bad buys.

2. **Age of Vehicles and Bad Buys:**
   - Proportion of bad buys is low (0.04) for cars with an age of 1.
   - Proportion of bad buys increases to 0.3 for cars with an age of 9.
   - Indicates that bad buys are more prevalent in older cars.

## Recommendations

- Further investigate the patterns around peak purchase dates in 2009 and 2010 to understand potential factors contributing to bad buys.
- Consider age as a significant factor, especially for cars aged 9 years, when evaluating the risk of a bad buy.
