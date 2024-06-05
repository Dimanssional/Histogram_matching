# Histogram matching 

This project presents implementation of histogram matching algorithm. Histogram matching is a process where a time series, image, or higher dimension scalar data is modified such that its histogram matches that of another (reference) dataset. A common application of this is to match the images from two sensors with slightly different responses, or from a sensor whose response changes over time. <br/>

<p align="center"><img src="http://paulbourke.net/miscellaneous/equalisation/diagram1.jpg"></p><br/>

First function ```adap_hist_matching``` performs histogram matching on the whole image. Second function ```partial_adap_hist_matching``` performs histogram matching on the some part of the image, by means of ```crop_hist_match``` function, which crop image of DxD size.<br/>

<p align="center"><img src="https://user-images.githubusercontent.com/67442675/120545876-7a37a800-c3ef-11eb-8a50-aaeb7fbcf39e.png">result of histogram matching</p>

[More theoretical info about histogram matching](http://paulbourke.net/miscellaneous/equalisation/)

