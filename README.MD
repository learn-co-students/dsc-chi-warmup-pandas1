# Pandas Warmup

Pandas out yer ears

## Data setup

Import: 

- Pandas under the alias 'pd'

- Matplotlib.pyplot under the alias 'plt'

Run:
- %matplotlib inline


```python

```

#### Make a dataframe by reading in the csv 'Chicago_Park_District__Movies_in_the_Parks_2019' which is in the "data" folder  

#### Assign the dataframe to the variable 'movies'

#### Look at the first five rows


```python

```

#### What kind of type is the data in the Date column?  Turn it into a datetime type if it's not already


```python

```

#### Replace the Day column with an integer for the day of the week derived from the datetime object in the Date column 

[*Hint*](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DatetimeIndex.dayofweek.html)


```python

```

## Data Exploration

#### What is the most frequent place to show a movie?  (Remember that there might be a tie!)


```python

```

#### Are there more 773 or 312 area codes for places where movies are shown?  


```python

```

#### Group the data by what day of the week the movies are shown using `.groupby()`

#### Assign to the variable "movies_grp_day" (what type of object is this?)


```python

```

#### Select just the movies shown on Monday (what type of object is *this*?)


```python

```

#### Using `movies_grp_day`, get the modal rating shown each day

*Hint: look at [the groupby documentation](https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.core.groupby.DataFrameGroupBy.agg.html) and write a function*


```python

```

## Strrretch Goal

#### Make a stacked bar chart showing the ratings of movies across days of the week using fig and ax objects

#### Title the x-axis "Days of the Week"

#### Title the y-axis "Number of Movies Shown"

#### Title the chart as a whole "Chicago Movies in the Park by Days and Rating"

[*Hint*](https://matplotlib.org/3.1.1/gallery/lines_bars_and_markers/bar_stacked.html)


```python

```


```python

```


```python

```


```python

```
