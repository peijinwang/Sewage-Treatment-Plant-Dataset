# Sewage Treatment Plant Dataset

Currently, there are already some datasets for object detection in remote sensing imagery. For example, [COWC](https://gdo152.llnl.gov/cowc/), [VEDAI](https://downloads.greyc.fr/vedai/), and DLR 3K Munich Vehicle are used for vehicle detection. UCAS-AOD consists of vehicles and planes and HRSC2016 contains ships. As for generic object detection, [DOTA](https://captain-whu.github.io/DOTA/dataset.html) dataset and NWPU VHR-10 have 20, 15 and 10 class, respectively. However, there is a lack of dataset related to composite objects.


To apply object detection methods on composite objects, we create a new sewage treatment plant dataset, which is a kind of typical composite objects with various shapes and sizes. The resolution and sensors are used as factors to impact the quality of the dataset. To eliminate the deviation, we collected large-scale remote sensing images with sewage treatment plants from Google Earth, which includes seven cities of Yangtze valley: Chongqing, Nanchang, Nanjing, Panzhihua, Shanghai, Suzhou, andWuhan. The dataset covers roughly 127165 square kilometers.

To improve the quality of annotations, each image has a resolution of 0.5 meters. The locations of sewage treatment plants in these images were labeled with bounding boxes `(xmin, ymin, xmax, ymax)`, where `(xmin, ymin)` and `` (xmax, ymax)``   are the top-left and bottom-right point, respectively. We provide some samples of the dataset in `Examples`.

 The dataset will be available when the paper PBNet: Part-based Convolutional Neural Network for Complex Composite Object Detection in Remote Sensing Imagery is published. Looking forward to your support.

`Visualization of annotations:`
![image-20200908100011779](https://i.loli.net/2020/10/17/Ld3uQqMYo7TcJkN.png)
