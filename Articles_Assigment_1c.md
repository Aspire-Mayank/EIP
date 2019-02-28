```
 Name: Mayank Sharma 
 Batch: 4th 
 Email id: 61mayanksharma@gmail.com
```



# Epochs

Epochs means how many times you gone through full dataset. we can say epoch is an **iteration or looping** process for Dataset to read as number of cycle. epoch helps in process of learning the data to increase efficiency of model as per dataset.

![](D:\study\EIP\Session 1\Assigment_1_c\Epoch.png)

1 epoch is equals to one complete tracing of training Data as 1 forward + 1 backward pass.

Example: if you have 100 training examples, and your ***batch size*** is 50 then it will take 2 ***iteration*** to complete 1 ***Epoch***.



# Filters/Kernels/Mask/

Kernel or filters words came from Image processing, its kind of small matrix or mask which we can move or slide on top of actual image as pixel by pixel, to get image information can say features or information, main objective of filters to get bunch of different features from same actual image. we can get blur,edges detected,smooth images as end result after masking.

![](D:\study\EIP\Session 1\Assigment_1_c\kernal_visually.png)

kernels will give you different features of same input image. it helps CNN to give all features to merge and find complex information, helps to improve prediction.

![](D:\study\EIP\Session 1\Assigment_1_c\filters_image.png)



# Receptive Field

Object which willing to accept information or able to receive signals called "receptive". Eye have special neuron which stimulates and activates if it gets any seen object and pass those signals to mind as information. so For mind that special field is called "Receptive Field". 

![](D:\study\EIP\Session 1\Assigment_1_c\receptive_field1.gif)

In CNN by increases layer(depth) you get more receptive fields, Main objective of Receptive Field in CNN to get more information out of any input  Image, and how can we do it ?? ..with help of no. feature extractor, dense Layer, striding, pooling, dilation.

![](D:\study\EIP\Session 1\Assigment_1_c\receptive_field.png)



# Feature Map

The main foundational items of CNN is convolution layer, main idea is to extract all set of information and merge at the end to finalize or identify what object actually is using kernels or feature extractor we get bunch of feature Layers or information layers in extraction process, so those exact information which comes in process called "Feature Map" and after merging only this maps we get final detected object in image by process of Convolution with help of Filters.

![](D:\study\EIP\Session 1\Assigment_1_c\feature_Map1.png)

A ***feature map*** is a method which links a **data vector** to **feature space**. commonly used **mask/kernels/filters/feature extractor** achieve and return inner products of features that would be impossible to calculate manually as mostly have infinite dimensions of features.

Note: Feature map also know as activation map.

![](D:\study\EIP\Session 1\Assigment_1_c\feature_Map.png)



# Activation Function

The idea is to segregate information of relevant and non-relevant from input data. so in actual world if you want get relevant information from non-linear input, so you need mechanism which will give help to suppress non-relevance information, and highlighted which requires for you called "Activation Function".

![](D:\study\EIP\Session 1\Assigment_1_c\activation_function.png)

 They basically decide whether a part should be activated or not. Whether the information that part is receiving is relevant for the given information or should it be ignored.

![](D:\study\EIP\Session 1\Assigment_1_c\StepFunction.png)

The activation function is the non linear transformation that we do over the input signal. This transformed output is then sent to the next layer of neurons as input. 