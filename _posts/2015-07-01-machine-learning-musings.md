---
published: true
layout: post
category: posts
---





## Machine Learning Musings

Machine Learning is an area of computing that focuses on building a model from given data so as to apply the model and evaluate new unseen data to a certain degree of accuracy that accounts for outliers and prevents overfitting of data. This learning can take various forms depending on the end objective. Problems of classification, clustering, regression, dimensionality reduction can all be solved using various machine learning algorithms. 

The image below illustrates very well the scope of machine learning.


### Deluge of Data
Getting past this introduction, the learning landscape is changing extremely rapidly as people are beginning to embrace this technology as they begin to see its merits. One remarkable application of this technology is for business owners to better understand their customers and tailor their services. The primary cause for this is the growth of massive data sets. People are surrounded by sensors and trackers - on smartphones, online, roads. Huge amounts of data are being collected on a daily basis and this allows for the creation of fairly accurate learning models.

### Storage and Computational Prowess
With everincreasing datasets, storage and computation becomes a prime concern. Storage media and algorithms need to provide more storage, efficiently quash redundancy and further ensure speedy read-write cycles. Computationally, computers must be able to handle massive datasets with a suitable time complexity that ensures solutions in meaningful time intervals.

### Scalability
The above two points bring about the notion of scalability. Algorithms must be dynamic in the sense that they can cope with the deluge of data while remembering that computational improvements follow Moore's Law. There are many discussions about the eventual demise of this law, but lets assume it holds for the time being. If data size exhibits an exponential increase annually, computational power cannot hope to keep up because Moore's Law stipulates that computational power doubles roughly every 18 months - a linear increase.

### The Way Out
Not to worry however, because some people anticipated this problem years ago. Google in particular, began handling issues such as this over a decade ago when it really exploded and a search engine. It had to do its best to maintain its advantage as the fastest and most relevant lookup service there is. 

In 2005, Google published the [MapReduce paper](http://research.google.com/archive/mapreduce.html), a critical development in techniques used to effectively handle and process Terrabytes of data. This was followed by the release of Hadoop and now various other tools. [Spark](https://spark.apache.org/) a creation by Apache is a fairly recent addition to this toolset and from what I hear, is extremely fast - 10 to 100 times the speed of Hadoop MapReduce depending on the type of deployment. Spark has libraries that are dedicated to cluster driven machine learning among other applications involving large amounts of data.

I'm very curious to see how this works for myself. More information as and when I finish experimenting!
