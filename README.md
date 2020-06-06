# CLPD_dataset (China License Plate Dataset)

## description

The LP images in the proposed CLPD dataset are collected from a variety of real-scene image sources, for example, searched from the Internet, taken by mobile phones or captured by car driving recorders. When taking LP photos, we also diversify the photographing angles, shooting times, resolutions and background so as to cover different conditions.


The proposed dataset includes multiple vehicle types, such as trucks, cars, police cars and new energy vehicles.
Note that new energy vehicles in China have license plates with eight letters, while other vehicles have seven-letter license plates. We also allow occluded license plates which have less than seven visible letters. The variation in the length of license plate letters increases the recognition difficulty as well, and makes the rule based recognition methods infeasible. 
The bounding boxes and license plate letters are annotated manually. 
In summary, the CLPD dataset contains 1200 LP images from all 31 provinces in mainland China. 
## download
It can be downloaded from  [BaiduYun Drive(code: dt11)](https://pan.baidu.com/s/1iqEucjhfKXbB0tdduRz8xA )


The annotation information of the picture is in CLPD.csv, each line contains the picture path, the upper left corner point (x1, y1) the upper right corner point (x2, y2), the lower right corner point (x3, y3), the lower left corner point (x4, y4) and label.


Please note that the label contains Chinese characters and is encoded in ‘GBK’ format on Windows 10. If you are using it in a Linux system, please convert the label to ‘UTF-8’ format.

