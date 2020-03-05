# ML-PySpark-California-Housing
In this notebook, I have done big data processing, analysis and ML with PySpark. Firstly, I have explored and preprocessed the dataset that I loaded in at the first step the help of DataFrames. About the dataset: It appeared in a 1997 paper titled Sparse Spatial Autoregressions, written by Pace, R. Kelley and Ronald Barry and published in the Statistics and Probability Letters journal. The researchers built this data set by using the 1990 California census data.
The data contains one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people). In this sample a block group on average includes 1425.5 individuals living in a geographically compact area. You’ll gather this information from this web page or by reading the paper which was mentioned above and which you can find here.
These spatial data contain 20,640 observations on housing prices with 9 economic variables:
Longitude refers to the angular distance of a geographic place north or south of the earth’s equator for each block group;
Latitude refers to the angular distance of a geographic place east or west of the earth’s equator for each block group;
Housing median age is the median age of the people that belong to a block group. Note that the median is the value that lies at the midpoint of a frequency distribution of observed values;
Total rooms is the total number of rooms in the houses per block group;
Total bedrooms is the total number of bedrooms in the houses per block group;
Population is the number of inhabitants of a block group;
Households refers to units of houses and their occupants per block group;
Median income is used to register the median income of people that belong to a block group;
Median house value is the dependent variable and refers to the median house value per block group.
