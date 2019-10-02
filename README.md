# **SelfStudy_OpenCV**

## **Overview:**
    Learn OpenCV using python, through this process of learning we are going to understand concepts of image processing using OpenCV. Also we are going to learn functionalities of OpenCV. This session includes hands on with OpenCV and Python.
    
    OpenCV - https://opencv.org/

## **Day 1 : 30/09/2019**
 - Chapter 1 : Introduction to Course
 
 - Chapter 2 : Introduction to OpenCV
        
        CV is a tech used to understand images. To computer images are pixels made up of colours red, green and blue.
    Grey scale images are 2 dimensional arrays, each pixel denotes the amount of black scale used in numbers. Where as coloured images made up of 3 dimensional array, also the colour of a pixel is defined by amount of red, green and blue in numbers.
    
        There are factors that can affect image understand such as angles, colour composture and other optical disortions.
  
  Hands on:
    Here we are using Oracle VM VirtualBox Manager to open Ubuntu environment to test code in python.


## **Day 2 : 01/10/2019**
 - Chapter 3 : Environment setup & running first code
        Completed settings up environment to run sample codes from jupyter notebook and also ran few examples.

 - Chapter 4 : Introduction to machine learning and neural networks, here we say different types of superised learning.

 **Types of machine learning modules:**
   - Supervised learning (with expected segrigation)
   - Unsupervised learning (with unexpected segrigation, involves clustering)
   - Self supervised learning (lables data)
   - Reinforced learning (learning from failures, when ever module faces failure it will learn not to fail in same scenario)

Also we learned how nodes process weigths, seeing into the topic we learned of a term called bias.

## **Day 3 : 02/10/2019**

 - Chapter 4 : Contin....  
 
 Introduction to activation function:
 
 Rectified Linear Unit (ReLU)
  - Biases : Shift values left and right in curve by adding biase values to weights (xi+b)
  
  Neuron only triggers only when threshold value is reached (Basics of NNs)
  
  ###Training NNs:
  
  - Assign random weights and biase
  - Pass values into hidden nodes
  - Compare expected output and obtained output by using Mean Squared Error method (Expected Output - Obtained Output )2
  - Adjust weigths based on loss calcualted using back propagation
  - Repeat process with more data
  - Stop whenn loss is minimal
  
  (To decrease loss introduce -ve gradients)
   