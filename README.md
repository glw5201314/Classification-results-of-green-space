# Classification-results-of-green-space

### NEWS !!!
* **`May. 04th, 2024`:** :rocket: Provide land classification data extracted using U-net,RF,SVM based on 2-meter resolution!
In the future, relevant data such as training model and training data will be uploaded gradually

* **`May. 11th, 2024`:** :rocket: Provide part 2 two-meter remote sensing image, unet model file, validation data!

In the future, relevant data such as training model and training data will be uploaded gradually
In addition, if you encounter any technical problems or need further guidance while using this open source file, please send an email to the following address:
- Email: ahnu_glw@foxmail.com
I will reply to your questions as soon as possible. Thank you for your support and contribution to this project.

## <div align="center">Introduction</div>
In this study, an in-depth comparative experimental framework is established to scrutinize the effects of remote sensing image data sources and machine learning algorithms on the social functional classification of green spaces. The high-resolution CBERS-04A imagery (2m) is juxtaposed with medium-resolution data from Landsat TM (30m) and Sentinel-2 (10m), ensuring a level playing field by utilizing identical input parameters across the board. This meticulous approach allows for a clear delineation of the advantages and limitations inherent in various data resolutions for the purpose of green space analysis.The U-Net deep learning model, central to the research, is rigorously compared with established algorithms such as the Support Vector Machine (SVM) and the Random Forest (RF), as well as the ENVINet5 model, which shares its foundational U-Net architecture. The SVM, known for its robust classification capabilities, is fine-tuned with hyperparameters including the RBF kernel, cost, and sigma, set in accordance with the latest scholarly recommendations. Similarly, the RF algorithm, celebrated for its ensemble learning approach, is optimized with parameters ntree and mtry, calibrated to leverage the model's predictive power effectively.The inclusion of ENVINet5 in the comparative analysis provides a unique perspective, as it operates within the ENVI Deep Learning 1.2 environment, which, while similar to ArcGIS Pro, imposes restrictions on network customization. The study ensures a fair assessment by aligning the training parameters of ENVINet5 with those of ArcGIS Pro 3.1, thus offering a transparent view of each model's performance under identical conditions.The comprehensive nature of this experimental design not only seeks to identify the most effective methodologies for green space classification but also aims to contribute to the broader understanding of how machine learning algorithms can be harnessed to enhance the utility of remote sensing data. By providing a detailed comparison, the study serves as a valuable reference for researchers and practitioners in the field, potentially influencing the direction of future technological developments and applications in remote sensing and machine learning for urban planning and environmental management.

![对比图](https://github.com/glw5201314/Classification-results-of-green-space/assets/74762812/5e328ab1-f698-4553-a933-a94d1d537fd2)


## Download

U-net:[[Baidu Netdisk](https://pan.baidu.com/s/13UOxfzTdiZu2Ya-bAXOVfg)] password:qpzm

SVM:[[Baidu Netdisk](https://pan.baidu.com/s/1PdZOreC8289BSNZPWwMvhA)] password:qpzn

RF:[[Baidu Netdisk](https://pan.baidu.com/s/1WtH7EuBkDLzDK5SuLzcyrQ)] password:qpzb

model file:[[Baidu Netdisk](https://pan.baidu.com/s/1E7nN-S4okaCsT8BpnbNIGQ)] password:qpza

Part of the remote sensing image:[[Baidu Netdisk](https://pan.baidu.com/s/1smAxZCNMXfsH-7RBeNd9Tw)] password:qpzc

Part of the remote sensing image:[[Baidu Netdisk](https://pan.baidu.com/s/15uSqIh-scB6wmkapMx_Yhw)] password:qpzo
