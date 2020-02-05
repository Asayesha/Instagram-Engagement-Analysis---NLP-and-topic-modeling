# Instagram Engagement
 
## Image Analytics : NatGeo page on Instagram

### Introduction :  
Considering that in 2014 social users posted an average of 1.8 billion photos to the internet daily and the growth of image-centric platforms like Instagram, Snapchat and Pinterest makes analyzing visual data also very important to understand your audience.

### Business problem : 
What should National Geographic do to increase engagement on its Instagram page?

### Dataset : 
Data scraped from the Instagram page of NatGeo

### Toolkit : 
Google Vision Cloud, Python

### Approach :
1.	We extracted the image URLs, post caption(the text description of a post) and the number of likes and comments to the post
2.	Using the image URLs, obtained image labels from Google Vision cloud
3.	Created a metric called ‘engagement score’ =   .4*# likes (normalized) + .6*# comments (normalized).
4.	Defined High (1) and Low (0) engagement based on whether the engagement score is above or below the median value.  
5.	Perform topic modeling on image labels

