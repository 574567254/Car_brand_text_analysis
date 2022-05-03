# Car_brand_text_analysis
## Real-word Trade-in Values of Car Brands

Inspired by the idea of using social mentions for movies to predict box office outcomes (reference link: https://www.socialmediatoday.com/content/two-thumbs-using-social-media-trends-anticipate-box-office-success), we constructed this project with the aim to explore insights based on the text analysis with regard to posts on a forum, and to form potential advice for brand manager, product manager and advertising manager based on our concrete analysis. This project is implemented in python and most of our analysis are conducted using the natrual language processing library - NLTK.

To avoid bias on a particular product or brand, we get started by parsing data from general topics forums. We target on the latest 5000 comments on a forum related to real-world vehicle trade-in values (data source: https://forums.edmunds.com/discussion/1212/general/x/real-world-trade-in-values).

To make this project organized and well-constructed, we break it into three main aspects:

- In the first session, we identify the top 10 brands frequently mentioned brands, and look into the association in between the brands by calculating lift ratios. Multidimensional scaling map is also employed in this session to discover the inter-relation between top 10 brands.

- In the second session, we look into detail about the post with regard to each top 10 brands and the related car attribute that have been mentioned during the conversation. Then we constructed a attribute frequency dataframe for each top 5 frequently mentioned brands. We also drew wordclouds for each brand so that we can closely examine some noteworthy attributes. After that, we further explored those attributes and developed marketing and product development insights based on the analysis.

- In the third session, we come up with the most aspirational brand in terms of people actually wanting to own and valuable business implications, based on the forum we choose.

#### See [car brand analysis](https://github.com/574567254/Car_brand_text_analysis/blob/78345e989e2c48c28000f65e0b78d9a6194477cc/Car_Brand_Analysis.ipynb) Jupyter Notebook for detailed analysis

#### All the external data used in our project are in the [data_used](https://github.com/574567254/Car_brand_text_analysis/blob/78345e989e2c48c28000f65e0b78d9a6194477cc/data_used) folder
