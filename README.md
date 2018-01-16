# SCUT_HEAD_Dataset_Release
SCUT HEAD is a large-scale head detection dataset, including 4405 images labeld with 111251 heads.
# Description
SCUT HEAD is a large-scale head detection dataset, including 4405 images labeld with 111251 heads. The dataset consists of two parts. PartA includes 2000 images sampled from monitor videos of classrooms in an university with 67321 heads annotated. PartB includes 2405 images crawled from Internet with 43930 heads annotated. We have labelled every visable heads with xmin, ymin, xmax and ymax coordinates and ensured that annotations cover the entire head including the blocked parts but without extra background. Both PartA and PartB are divided into training and testing parts. Our dataset follows the standard of Pascal VOC. 

# PartA 
PartA includes 2000 images sampled from monitor videos of classrooms in an university with 67321 heads annotated. 1500 images of PartA are for training and 500 for testing.
Because classrooms in an university usually looks similar and the poses of people vary less, we carefully choose representative images to gain variance and reduce similarity. 
Representative images and annotations are shown in Fig.1, and the histogram of people counts is in Fig.2.

![image](https://github.com/HCIILAB/SCUT_HEAD_Dataset_Release/blob/master/example%20in%20Part_A.png)

<center>Fig.1</center>

![image](https://github.com/HCIILAB/SCUT_HEAD_Dataset_Release/blob/master/statistics%20of%20Part_A.png)

Fig.2

# PartB 
PartB includes 2405 images with 43940 heads annotated. 1905 images of PartB are for training and 500 for testing. The images are crawled from Internet (Baidu and Google), the urls of images are provided as followed.
Representative images and annotations are shown in Fig.3, and the histogram of people counts is in Fig.4.

![image](https://github.com/HCIILAB/SCUT_HEAD_Dataset_Release/blob/master/example%20in%20Part_B.png)

Fig.3

![image](https://github.com/HCIILAB/SCUT_HEAD_Dataset_Release/blob/master/statistics%20of%20Part_B.png)

Fig.4

# Comparision 
The comparision of SCUT HEAD between other people head detection datasets is as followed.

![image](https://github.com/HCIILAB/SCUT_HEAD_Dataset_Release/blob/master/Comparision.png)
