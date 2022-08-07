# IBM-PROJECT
### IBM IOT BASED TRAFFIC SIGNS BILLBOARD PROJECT

## Project Summary :
A digital LED display based traffic sign will be attached at every road junction. Depending on the weather, visibility, rain, stagnant water, quality of road and traffic conditions, the sign changes the recommended speed limit, redirects traffic and allows emergency vehicles to pass through without delay.

## Milestones :

### **Open Weather API** 
>    - Assigned to **Yuvasri**
>    - Explore the Open Weather API to find out how accurately the API can provide the weather of a certain region.
>    - Write a python program to access the API and output the weather condition at a particular place)


### **Location API -> IP/Manual based**
>  - Assigned to **Yuvasri**
>  - Even if there are no GPS devices, we can find the approximate location of any device on the internet using thier IP address
>  - Explore this field and findout how accurate IP based location is and try to use this location as the input to the Open Weather API
>  - Write a python program to obtain the location of the device using it's IP and use the location to get the weather there.


### **Speed Prediction**
>  - Assigned to **Yuvasri**
>  - Calculate the optimum speed for 2 wheelers, 4 wheelers and heavy vehicles in different conditions like foggy weather, rainy weather, curvy road, straight road
>  - Write a python program to print the speed for various types of vehicles given a weather condition. Use the output of the Open Weather API as the input for this speed prediction program.


### **Optimum Display Procurement**
>  - Assigned to **Yuvasri**
>  - There are verious LED displays in the market.
>  - Analyse the cost, size and compatibility with microcontroller and find an optimal display for the project.
>  - Report the various options in the IBM Project group once completed.


### **Rain Measurement -> Image/Sensor based**
>  - Assigned to **Yuvashree**
>  - Build an AI/ML based model to check the amount of stagnant water in a given image of any road.
>  - Input will be the path of a image and output must be any of the following
>     - Dry road 
>     - Wet road
>     - Stagnant Water
>     - Flooded


### **Fog/Visibility Measurement -> Image based AI/ML**
>  - Assigned to **Yuvashree**
>  - Build an AI/ML based model to check fog/mist/visibility in a given image.
>  - Input will be the path of a image and output must be a number where
>     - Maximum visibility is denoted by 100
>     - Minimum visibility is denoted by 0

### **Dashboard, GUI and remote server control**
>  - Assigned to **Ulagaraja**
>  - Design the UI and front end for the project and make it so that the sign boards can be controlled remotely

### **Image Transmission**
>  - Assigned to **Pervez**
>  - Program the microconrrollers to transmit images to a remote server for processing
>  - Trnasmit the humidity and temperature along with the images for speed prediction


### **Programming the LED Display**
>  - Assigned to **Pervez**
>  - Program the microconrrollers to control the LED display on command from the server
>  - Program various signs and shapes for the Display

### **Hardware & Software Integration**
>  - Assigned to **Pervez**
>  - Connect all the pieces of the puzzle to complete the project.

## Optional Milestones :
- **Route planning -> Image based/ Manual/ Google maps API**
- **Intelligent Path processing**
- **Road Quality Measurement**
- **Emergency Vehicle Assistance**
- **School Zone Acknowledgement**
- **Intelligent Traffic based speed and redirection control**

### Task Submission Schema

> Python is the preferred programming language except for (Ulagaraja) web development and algorithm development

> Each task must be submitted as a single file python program. In case of ML/AI based assignment (Yuvashri and Yuvashree) The entire task must be submitted as 2 files atmost. One **`.py`** file [strictly no **`.ipynb (jupyter notebook files)`**]. One file for the trained model of any type.

> Program file structure must be as below

```
#all library imports
import a,b,c

# subfunctions
def subfunction1():
  return(blah)
  
def subfunction2():
  return(blahblah)
  
def subfunction3():
  return(blahblahblah)

# a main function named run must be madatory in the file you submit
def run(input1, input2):
  subfunction1()
  subfunction2()
  subfunction3()
  return( result )
  
# comments section explaining what the input variables of run function are and their data types
# #input1 is the latitude ,datatype is string
# #input2 is the longtitude ,datatype is float

# comments section explaining what the output variables of run function are and their data types
# #result is the weather condition at the given latitude and longtitude, datatype is list os floats

```
