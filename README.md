# DeepLearningFileProcessTools
用于深度学习（ultralytics-Yolo训练）数据集文件整合与预处理小工具
这个是我之前用python编译的一个文件处理小工具，

![image](https://github.com/wcelll/DeepLearningFileProcessTools/blob/main/%E7%89%88%E6%9C%AC%E9%A1%B5%E9%9D%A2%E6%88%AA%E5%9B%BE/v1.0.1FileBeta/001.png)

第一页的功能是合并多文件夹图像到一个文件夹中。从多个文件夹中复制其中的bmp格式的图像文件，“添加源文件夹”选取指定的多个存放有图像的文件夹，“选择目标文件夹”选择要复制到的目标文件夹，然后把多个图像文件夹中的bmp图像统一复制到目标文件夹中，如遇两个源文件夹（如cam0文件夹中有一个111.bmp，cam2中也有一个111.bmp那么对这两个进行复制或者移动，就会有该机制）重名文件，会自动重命名。

![image](https://github.com/wcelll/DeepLearningFileProcessTools/blob/main/%E7%89%88%E6%9C%AC%E9%A1%B5%E9%9D%A2%E6%88%AA%E5%9B%BE/v1.0.1FileBeta/002.png)

第二页是对存放于同一个文件夹中删除不匹配不同等数量的txt文件或者图像文件，在进行深度学习训练过程中，最后的train文件夹内需同时存放同等数量的图片文件和label标签文件，因此有多少张图片就需要多少个txt文件，需要一一匹配，这个在以前是比较耗费时间的，需要手动去删除多余图片或者多余标签。

![image](https://github.com/wcelll/DeepLearningFileProcessTools/blob/main/%E7%89%88%E6%9C%AC%E9%A1%B5%E9%9D%A2%E6%88%AA%E5%9B%BE/v1.0.1FileBeta/003.png)

第三页功能是对来自划分数据集以后的[图片]这种train.txt类似的txt里面存放的多行路径下的图片文件进行逐行读取，然后将里面的图片存放到指定的文件夹中。使用该功能需要先选择txt文件，然后选择目标文件夹，然后点击开始即可。后续将加入更多新功能，目前这三个就能应对深度学习的数据集处理了

![image](https://github.com/wcelll/DeepLearningFileProcessTools/blob/main/%E7%89%88%E6%9C%AC%E9%A1%B5%E9%9D%A2%E6%88%AA%E5%9B%BE/v1.0.1FileBeta/004.png)
