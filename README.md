# Vehicle_Detection

## Environment
-Pyhton      
-OpenCV       
-Sklearn       
-Scipy      
-Numpy      




## Steps       
1. Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images     
vehicle:                
![Image text](https://github.com/Yunying-Chen/Vehicle_Detection/blob/master/img/vehicle.png)              
non-vehicle:            
![Image text](https://github.com/Yunying-Chen/Vehicle_Detection/blob/master/img/non-vehicle.png) 
2. Apply a color transform(from RGB to YCrCb) and append binned color features, as well as histograms of color, to your HOG feature vector.                
![Image text](https://github.com/Yunying-Chen/Vehicle_Detection/blob/master/img/ImageFeature.png) 
3. Train a classifier by using SVM with 'rbf' kernel with vehicle and non-vehicle images.                        
The accuracy of the classifier reaches 99.2%     
4. Implement a sliding-window technique and use trained classifier to search for vehicles in images                                       ![Image text](https://github.com/Yunying-Chen/Vehicle_Detection/blob/master/img/SlidingWindow.png)   
5. Create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.      
6. Estimate a bounding box for vehicles detected          
![Image text](https://github.com/Yunying-Chen/Vehicle_Detection/blob/master/img/heatmap.png)
 
 
 
 ## Performance
 ![GIF](https://github.com/Yunying-Chen/Advanced_Lane_Line_Detection/blob/master/img/Animation.gif)

