# In this excercise we are using a library that belongs to pandas and not directly to python
import pandas
travel_df = pandas.read_excel('./cities.xlsx')
# We call the pandas.read_excel method and pass through the string './cities' as the file is called cities.xlsx. By saying './' we are saying that the file sits in the current folder
cities = travel_df.to.dict('records')
cities[0]

