# DroneVsBirdDetection

## Technologies
<ul>
<li> Python </li>
</ul>

<br>

## Running This Program

This code writed with Colab. If you want run this program;
1) firstly you must install [this](https://drive.google.com/drive/folders/1-vqKCgFsalkntPOanfYlchQDqWTklH24?usp=sharing) files and
2) secondly you can run program from [here](https://colab.research.google.com/drive/1FEvEYh7k24wp6dRtr5vWPBkvR1YmJ-8H?usp=sharing).

<br>

The created model uses yolov4 weights. Coded for 2-class drone and bird detection. obj.data file content ; <br><br>
![1](https://github.com/SeymaAtmaca/DroneVsBirdDetection/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202022-11-29%20234506.jpg) <br>

In this file; The number of classes, the location of the train.txt and test.txt files, the obj.names file command containing the class names and the backup file extensions where the weights are saved are specified.

<br><br>

In obj.names file ; 
<br><br>

![2](https://github.com/SeymaAtmaca/DroneVsBirdDetection/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202022-11-29%20234543.jpg)
<br><br><br>

If you want to train your model with different number of classes, you should change the class names in obj.names, the number of classes in obj.data file, the number of yolov4 classes in the yolov4-tiny-custom.cfg file, and the number of filters found before the yolov4 layers. The filter value used before the Yolov4 layer can be found with the formula (classes_count + 5 ) * 3. The yolov4 layer used in this model and the filter size used before yolov4 are given below.

<br><br>

![3](https://github.com/SeymaAtmaca/DroneVsBirdDetection/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202022-11-29%20235556.jpg)


<br> <br>

The video detection output I made as a result of my model training is below. It is seen that a good determination has been made in the video, but there are also errors. This is because my dataset is very small. If you want a better result, you can enlarge your dataset.


 https://user-images.githubusercontent.com/54944249/204648035-23729cb9-5700-4f77-b2d3-5a2bc9eac294.mp4

<br><br>
The video I used for detection is also included in the downloaded file. You can run the program with colab by downloading this file directly to your drive.

<br><br>

## Contact

 My [LinkedIn](https://www.linkedin.com/in/%C5%9Feyma-atmaca-925b57195/) profile.


