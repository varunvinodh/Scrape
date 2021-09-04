This function was created on 25-08-2021.

Using this function You can get the data of all the latest,most popular or most viewed youtube videos from a particular channel.

Step 1:
First of all you have to set the path of your gekodriver in the function.


Step 2:
After that just copy the selected URL and save it to a variable like,
url='https://www.youtube.com/c/AmazonInOfficial/videos'
this is the Amazon India Videos url.


Step 3:
after that call the function using,
get_data(url)
to get the data.


Step 4:
You can store the data scraped into a DataFrame by,
df=get_data(url)


Step 5:
You can then save this DataFrame as an excel file into your local machine using the command,
df.to_excel('AmazonInOfficial.xlsx')


I created this function for my brother who was given a task on his company to retrieve data from 
multiple youtube channels and create a excel file.

