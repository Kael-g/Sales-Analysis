# Sales Analysis
Sales analysis in python as a part of my studies in Data Science based on [this video](https://www.youtube.com/watch?v=eMOA1pPVUc4).

## Installation and Setups
This code was made using Jupyter Notebook
- Python version 3.10.12
- Pandas
- Matplotlib
- Os

## Data
The data used in this project refers to the sales of a eletronic store for all months of 2019, that contains informations as product,  quantity ordered, price each, date and adress.

### Data Processing
- Concatenate all 12 files into a new DataFrame
- Drop NaN values from DataFrame
- Change the type of columns to the proper type
- Create new columns according to the needs

### Chalenges
- Finding out what was the best month of sales and how much was earned in that month
- Finding out which city had the highest number of sales
- Finding out what products are most often sold together
- Finding out what product sold the most

## Results
### The best month of sales was december (U$D 4.613.443,34), followed by october (U$D 3.736.726,88) and april (U$D 3.390.670,24)
![Bar graph of sales by month](https://github.com/Kael-g/Sales-Analysis/blob/dev/Images/Sales%20by%20month.png)

### San Francisco (CA) was the city with the highest amount of sales, with U$D 8.262.20,91. The lowest was Portland (ME), with U$D 449.758,27
![Bar graph of sales by city](https://github.com/Kael-g/Sales-Analysis/blob/dev/Images/Sales%20by%20city.png)

### Products most often sold together
- In progress

### Top 5 selling products was AAA Batteries(4-Pack), AA Batteries(4-Pack), USB-C Charging Cable, Lighting Charging Cable and Wired Headphones
![Bar graph of products selling amount](https://github.com/Kael-g/Sales-Analysis/blob/dev/Images/Product%20amount.png)