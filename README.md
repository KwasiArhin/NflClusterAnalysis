# NFL Receiver Clusters 


## Introduction

The NFL has transitioned to a passing league over the last decade. More than ever before pass records are being broken. In this project I wanted to see if I could make useful clusters using the Air Yards and Yards after catch statistics.  



## Data Overview
This dataset was scrapped from the website profootballrefrence with the aid of Ryurko R wrapper which makes simple to pull stats from the website. I used the play by play data of three seasons. 

The dataset contains 45546 plays and is accompanied by 256 columns.


![Distribution of YAC](README/Distribution%20of%20YAC.png)

![Cluster_means](README/table_clust.png)



## Introduction

Image segmentation is a common and crucial task in image processing. It consists of clustering the elements of an image into different groups. Although there are different ways of doing image segmentation, the most popular by far is k-means clustering. The main issue with using traditional k-means clustering for image segmentation is that it does not only affects the resolution of the image but it also completely neglects the background and makes it almost an impossible task to reconstruct it.

In this project, I provide you with the methodology necessary to reconstruct the background of a video (if the video meets certain assumptions) without having a significant negative impact on the quality of the image. After rebuilding the background, you'll be able to quickly isolate the foreground objects by subtracting the background from the rest of the video.



## Methodology

Removing the background from a video is a pretty trivial task when we have a known background. Unfortunately, there will be situations in which the background is unknown, and it has to be modeled using video data. The approach presented in this project is experimental and only works under particular assumptions, but when a video meets those assumptions, it yields satisfactory results.

**Assumptions:**





**Background Reconstruction**





**Background Removal**





**Foreground Extraction**




## Future Work

This project could be further improved by considering the following enhancements:
- Acquiring route data 
- Do a team by team analysis to see if various offensive systems lean toward certain types of receivers 



## References

1. https://www.4for4.com/fantasy-football/2018/preseason/air-yards-explained
2. https://nextgenstats.nfl.com/



