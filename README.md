# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The dataset chosen for this project is a dataset about video games sales extract from kaggle website with more than 16500 games. The source is https://www.kaggle.com/datasets/gregorut/videogamesales. On this data set, there were no need to perform none wrangling process other than read the csv file downloaded from the site. The information what we have on this dataset are the name, platform, year, genre, publisher, north america sale, europe sales, japan sales, other region sales and global sales, all sales information are in milions dollars scale.  


## Summary of Findings

> First finding was that DS and PS2 are the most popular plataform

> In second place we could see that 2009 in particular were the year with more release, and the 2000's were the decade with more sales of all. 

> Than we saw that Action were the genre more popular off all times and all that it represents almost 20% comparing with other genres. The second place was Sports that have almost 15%. 

> After that we saw the 25th more frequent publisher on the data set, and Electronic Arts were the more popular with more than 1300 games, followed by Activision, Namco, Ubisoft, Koname, THO than Nintendo (with almost 700 games) and it goes. 

> the next step was to take a look on the sales data, form the three regions, NA, EU, JP together. At first the aspects that it was possible to sse were, we had some outliers and the bigger part of the data was near to a low sale. That's was the reason for a scale transformation and it was used a log scale to obeserve better the distibution of sales. It turns out that the most part of the data set presente video games with low sales, what should be expected, another point was how the distribution is of the other games that have more sales.

> Trying to observe only the outliers on sales, we had filtered the data set and plot to see how it goes. At first no change on the scale were made, and the analysis results are that it was not too different from the previus analysis with all data set. Then we used a log scale to confirm that, and that's were we could see almost a binomial distribution on the regions. 

> With the purpose to find a better visualization of this corelaction, a histogram was plot, but now good understanding was made. 

> Then  it was used a heatmap, and with this plot it was possible to see by number which region have more corelaction with the global sales. But trying to see some trending lines, it was plot a visualizing with regression models.

> Then it was time to plot genre x global sales. and the result was not the most popular genre but the second one, sport were the best seller while action weer on 9th position.

> After that analyses, we filtered the data set to observer better how the best sellers in general distribuite. We saw that the best selleer games is a outlier, but if it did not exist, sport would still be the genre more sold on a global scale.]]

> Going to the end, comparing not just the genre and sales, we looked also to the publisher. And as turned out, Actvision were not the best seller, instead of Actvision, Nintendo got the first place on a global scale. 

> As expected, we did split the plot on the regions to see if the analyses were the same for genre and publisher, and as we could see Nintendo got the first place on all regions observed, but sports only took place on NA and EU, letting JP with Role Playing being the best seller genre.


## Key Insights for Presentation

> On this project, a insights to better present and see the results, on few steps it was used a filter on the dataset to see only the outliers what made the visualizations much more clear and with a high dark int ratio. Other point, was to compare the results as it was evoluating to the initial result, what has shown to have different results depend of the perpective.