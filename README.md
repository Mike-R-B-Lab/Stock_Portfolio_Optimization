# Stock Portfolio Optimization

In this project, I optimized the S&P 500 stock portfolio by only selecting the 15 most influencial companies within the index.

The correlation values of all stocks in the S&P 500 from 2010 to 2020 were used to produce a minimum spanning tree (MST). 

Within that tree, I was able to find the 15 stocks with the highest average degree of centrality and betweeness centrality (red nodes). They were placed in the Central Portfolio.
The 15 least influential stocks were identified by selecting those with the greatest average distance from the most central stocks on the basis of 3 criteria: degree of centrality, eigenvector centrality and closeness centrality (green nodes). The were added to the Peripheral Portfolio.

![image](https://github.com/user-attachments/assets/9a469928-6e17-41c3-a9c2-6e3b4a8fafa8)

I was then able to graph the 2021 returns for each respective portfilio:

![image](https://github.com/user-attachments/assets/10af7349-10cb-4b00-8c4f-080e18cf3fd9)

There was only one short period of about 2 weeks that saw the S&P 500 outperform the Central Portfolio before being surpassed once more.
When comparing the returns on an investment of $100k over a 12-month period, the Central Portfolio generated $5.4k more than the S&P 500.

![image](https://github.com/user-attachments/assets/1e862a2a-5d76-4345-9eb3-98c5980d6eb4)

