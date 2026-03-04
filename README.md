                                                  

First Implemented the Python operations , While Loop , Looping statements 

DATA MANIPULATION 

Pandas is an essential, open-source Python library for data manipulation and analysis, providing fast, flexible, and expressive data structures, primarily the DataFrame.

NumPy (Numerical Python) is the fundamental library for numerical computing in Python, providing high-performance, multi-dimensional array objects (ndarray) and a large collection of routines for fast operations on these arrays

First step is to load the dataset      

data=pd.read_csv("/content/iris.csv") 

Performing Data Analysis : 

Tail() # It shows the last few rows of the dataframe or series

data["species"].value_counts() #It performs the total count of the species

data.info() # It provides the concise summary of the dataframe , printing information about dtype,no.of col/rows,Non-null values.

data.describe()   #It performs the descriptive statistics like mean,count,min,max,percentile.

data.shape   #It shows the no.of rows and columns

data.columns # No.of columns return with a list

data.isnull().sum() #used to find the null values

data.dropna() # Removes the rows which contain which has null values , it get executed when it is found the Null values


DATA VISUALIZATION 

Matplotlib and Seaborn are the two most popular Python libraries for data visualization, and they are often used together to create anything from quick data checks to publication-quality figures.

Matplotlib is the base library. It provides low-level, granular control over every element of a plot (axes, labels, ticks, etc.).

Seaborn is built on top of Matplotlib. It acts as a high-level "wrapper" that makes it easier to create complex statistical graphics with better default aesthetics. 

Line plot

Scatter plot

Histogram

Barplot 

Pie Chart 

Box plot

Histplot

Violinplot

Countplot

HeatMap

Created a feature for experimenting by creating a new columns, Binning the values and Categorizing the data 

We cannot process the data which is Object . So we change into Numerical Values.

Featuring Scaling is implemented using the sklearn preprocessing library from scikitlearn to ensure numerical feature are on a similar scale.

And also perform Min-Max preprocessing from scaled data.








