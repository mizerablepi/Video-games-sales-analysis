# [Video-games-sales-analysis](https://github.com/mizerablepi/Video-games-sales-analysis/blob/main/Project_Video_game_sales_analysis.ipynb)
A quick analysis of openly available [dataset](https://www.kaggle.com/datasets/gregorut/videogamesales) on video game sales in the past few decades
See instructions on how to run the notebook in [installation.md](https://github.com/mizerablepi/Video-games-sales-analysis/blob/main/installation.md)
<hr>

Video games have become very popular these days, each year they progress in technology and bring new genres to the industry. Video game industry is one of the biggest and fastest growing industry in the world, there is no shortage of games being released every year on all the different platforms. This project aims to do some basic data analysis on video game sales throughout the years, to find some interesting patterns and answer some basic questions about the data. The analysis will be based on [this](https://www.kaggle.com/gregorut/videogamesales) free dataset from kaggle. The dataset contains the sales for various games along with the platform, year. The sales are further classified on the basis of regions.<br>

### Here's some basic statistics of our dataset:<br>
![image](https://user-images.githubusercontent.com/41267142/227131340-4d68329c-d73a-473e-b7f0-cd49c00a3ebd.png)

### The 5 oldest and the five latest games in our dataset are:<br>
![image](https://user-images.githubusercontent.com/41267142/227140594-5231ec0b-b213-4a9d-b379-9f58f3d709ac.png)

![image](https://user-images.githubusercontent.com/41267142/227140657-8f329bd3-01a5-4b8e-89ce-d68f47f7e332.png)

### Number of games by genre:<br>
![image](https://user-images.githubusercontent.com/41267142/227141036-8c693d65-bd03-47d7-9aff-126b8613f48d.png)<br>
_Action games are the most sold games till 2015_

### Region with most games sold:<br>
![image](https://user-images.githubusercontent.com/41267142/227142386-bf839cdb-d850-4948-a72b-93872ae56759.png)<br>
_From the pie chart we can see that most of the games are sold in NA. There is a huge market for video games in NA and publishers probably focus on NA more than any other region_

### Which game is the most sold?<br>
![image](https://user-images.githubusercontent.com/41267142/227142770-00c62f79-f8d5-480c-9d81-d62384e38dca.png)<br>
_Wii sport has double the sales than the second best selling game. There is a lot of demand for unique games like wii sports_

### Corelation between columns:<br>
![image](https://user-images.githubusercontent.com/41267142/227143156-fa303b86-2212-4050-afef-456d8eae4f43.png)

### Questions that are answered using this data:
1. Which are the top publihers?
2. How do the top publishers compare in terms of regional sales?
3. Are Sales increasing or decreasing every year?
4. What are the average sales globally?
5. Which console has the most games sold?

#### Q1 Which are the top publihers?
![image](https://user-images.githubusercontent.com/41267142/227144317-1b7e1c18-3199-4342-af62-c02640249d39.png)<br>
The above plot shows the top publishers in terms of sales: it is clear to see that nintendo is doing way better than its competition in terms of sales, but let us see how it does in terms of number of games published<br>
![image](https://user-images.githubusercontent.com/41267142/227144384-f2116c0c-e189-4c60-8717-036ab767c143.png)<br>
The above plot shows the top publishers in terms of most games: Comparing the two graphs we can see that the top selling publishers are not necessarily also creating a lot of games, some publisher have few games but lots of sales others have lots of game but comparitively fewer sales.

#### Q2 How do the top publishers compare in terms of regional sales?
![image](https://user-images.githubusercontent.com/41267142/227144605-9e8a2240-1a4f-4e3d-888c-93ef6b58a022.png)<br>
The amount of sales in each region seems proportionate to the total number of sales, except a few cases like namco bandai, Sega, konami having more sales in japan compared to Electronic Arts and Activision. Nintendo also has a lot more japan sales compared to EA and Activision

#### Q3 Are Sales increasing or decreasing every year?
![image](https://user-images.githubusercontent.com/41267142/227144925-83e63784-a3ba-4adb-a142-c49826042b9c.png)<br>
This is very interesting! The sales according to our Dataset seem to be decreasing after 2010. This Could be due to various reasons like:
* Decrease in number of games released every year
* Lost of interest in video games
* Incomplete Dataset

![image](https://user-images.githubusercontent.com/41267142/227144875-329de5bc-80fb-48d0-b388-b18f8a8df148.png)<br>
It seems that NA has a lot of sales that increase in huge amount after 1995, EA follows a similiar trend but with less magnitude, JP on the other hand seems to be constant from 1995 in terms of sales and other region see increase after 2000, this is because these regions were introduced to video games later.<br>
![image](https://user-images.githubusercontent.com/41267142/227145151-ed592acc-8e63-45dc-ae1a-ccf08e9abc24.png)<br>
Here we can see that there are a lot of spikes, these are probably around the time a new game was released by the respective publisher, causing an increase in sales. all the publisher seem to have an increase in sales over time, however sony seems to be relatively constant in sales We have a huge spike in nintendo sales at 2006, this must mean a very big game or lots of games were released that year by nintendo,

#### Q4 What are the average sales globally?
![image](https://user-images.githubusercontent.com/41267142/227145350-72dd0137-1461-4d90-8cf4-40358f203d7b.png)<br>
There were lots of sales done between 1986 and 1990 but there also seems to be a lot of variance so the we cant really be sure if there indeed was a lot of sale that year or if it is an error in the dataset

#### Q5 Which console has the most games sold?
![image](https://user-images.githubusercontent.com/41267142/227145568-ddffd3b9-cf08-4b55-987f-6bc92e88b966.png)<br>
The above plot shows consoles with most sales<br>
![image](https://user-images.githubusercontent.com/41267142/227145623-447a11b4-c5d6-4c4a-82f5-6739de92baac.png)<br>
The above plot shows consoles with most games


### Inferences and Conclusions<br>
After completing just this basic analysis we can already say a lot about our data. In terms of success with making games we can clearly see that nintendo is way ahead of its competitors, out of the 10 best selling games it has 7 games. It is also the top publisher in terms of global sale, even though it doesn't have the most games published, it still has more games sold than, say, Electronic Arts.

Out of all the paltforms **PS2** is by far the most popular and best selling game console. The number of games for the console also reflect it's popularity. The other console that comes close to the **PS2** is the **DS**. Being one of the first game console in the market it shows how many indie developers were making games for the **DS**. Out of all the popular regions, **NA** plays the most games, games have been sold there since the 1980's, it also contributes the most to the global sales and the global market. So much so that the graph for _NA sales_ and _Global Sales_ look pretty much identical. Among the genre of games Action games have been and still are the most popular, this could be mostly due to the fact that a lot of children play video games and action is thier favourite genre. The video game industry has grown a lot over the past few decades and continues to do so. 
