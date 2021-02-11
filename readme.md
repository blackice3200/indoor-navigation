This project aim to help blind people identify the different type of rooms in home by taking frames from a real-time video and process this frame and identify the type of the room and pronounce it loud to be heard.  

To solve the problem in this project I used a transfer learning technique like Resnet50 and Mobilenet v2 , so to use the transfer learning you need preprocess the data like converting all the dataset into 4D tensor array by loading the data and converting it to numpy array and then expand the dimension. After creating the model and train it , I have implemented an algorithm to take real-time frames from the camera and pronounce the result of the classification loud using speakers.


1-Dataset URL used in the project:

http://web.mit.edu/torralba/www/indoor.html

http://groups.csail.mit.edu/vision/datasets/ADE20K/ 


2.Following are the details of Software environments with version details 

 Python 3.6.6: Anaconda Navigator 1.8.7 (X64)
 
 Tensorflow GPU 1.8
 
 Keras GPU 2.2.0
 
 tqdm 4.23.4
 
 opencv 3.3.1

