# The-Journey-of-Life

## I. Analysis

### 1. Research

### a. Scope

-	To let the parents to understand their autistic child.

### b. Audit

####1. Existing products

#####-Q Sensor 
###### A device  that can detect and record physiological signs of stress and excitement by measuring slight electrical changes in the skin.
###### *Cons: - Data acquisition are not very accurate.

#####-E4 Wristband
###### A wearable wireless device designed for continuous, real-time data acquisition in daily life.

- Record in the lab or at home with no hassle.
- Empower your research with accurate data from everyday life.
- Access and analyze your raw data with our secure cloud platform.
- Use our mobile API to access real-time E4 data in your app.

###### *Pros: - Users can monitor and understand their physiological signals better in real-time.
###### *Cons: - High cost.


####2. relevant technologies

#####-	EDA Sensor (GSR Sensor)
######EDA: Used to measure sympathetic nervous system arousal and to derive features related to stress, engagement and excitement.
#####-	3-axis Accelerometer
######Captures motion-based activities

####3. Competitors /alternatives/ replacements
######We will have the same concept with the competitors of these products but the uses might be different. 
######Pros- For the parents to understand more about their autistic child.
######Cons- Poor family cannot afford.



### c. Stakeholder Interviews (internal / external)

Product vision: 
Users are able to observe the conditions of their children with autism all the time.

####Risks

- The notifications cannot reached to the users when the device or the users' phones is out of battery.
- Users do not notice the messages when they are answering a call.

####Obstacles

- Needs to be in a good phone service range.

####Constraints

- The app cannot call out if in a bad phone service range.
- The app is useless if secondary users do not wear the wristband.

####Opportunities

- Parents can get to know their children's condition in real-time.

### d. User observations

####Primary Users

-	potential users – Autistic children’s parents
-	(user’s) behaviours - They are busy in their works, they cannot accompany their children all the time. They always phone the nanny of their child to know the emotion and activities of their child. They always attend to the classes or programs that they can learn the strategies to communicate with their child. 
-	(user’s) attitudes -  They are willing to know the emotions and conditions of their child when they are not beside their child. They are willing to know their child well through consult the expert in autism theraphy field. 

####Secondary Users
-	potential users – Autistic children
-	(user’s) behaviours     

######Infant to Six Months,                                  
-does not smile back at you                           
-makes no eye contact                             
-does not look towards loud noises                               
-Unresponsive to people                                         
-Tendency to focus on one item for a long period of time                           
-Resistance to being touched                                
-High sensitivity to sound, touch.                                   

######By One Years Old,                                
-Not responding to their name                               
-No joyful expressions                                
-Lack of babbling                            
-Lack of eye contact                           
-Staring for a long time at items which aren't moving                                
-No gestures, such as pointing, showing, reaching, or waving.                     

######By Toddler Age,                    
-Delayed speech                              
-avoidance of making eye contact with people                           
-poor imitation skills (inability of imitating simple gestures or facial expressions)                          
-Non responsive to their name                   
-Does not express concern or understanding to people in distress                 

-	(user’s) attitudes - They are willing to communicate with their parents through action, using pictures and echolalia which means the repetition of other people's words.


##2. Modeling

###a. Personas

#####Name : Susan
#####Gender : Female
#####Age : 31
#####Occupation : Lawyer

####1. Goals

- As a mother, she wants to understand about her autistic child, Abby.

####2. Patterns in user and customer behaviours

- She busy in her works all the time and she has no time to accompany her child. She always phones the nanny to get to know Abby's emotion and activities all the time.

####3. Attitudes

- She wants to understand Abby better. Besides professional autism therapy services, she and her husband bring Abby to interative with programs of autistic children once a month. Also, she and her husband attend to the training programs that teaches parents strategies for managing challenging behavior in children with autism when they have free time.

###b. Other Models

Represent domain factors beyond individual users and customers 1. Workflows among multiple people

####1. Environment

####2. Artifacts


##II. Synthesis
###1. Requirements Definition
###a. Context Scenarios

#####-Our persona is Susan Wong, a professional lawyer, whose goals are to understand her autistic child.
#####-Here is Susan’s context scenario:
######1.	While getting ready in the morning, Susan makes sure her child, Abby is wearing the E&F wristband before she is going to work.
######2.	When she is dealing with her client, her phone rings. She checks her phone and she received a notification from the app. Normally while she is in an appointment, she will mute her phone, but when Abby is experiencing emotional turmoil, the app will automatically send her a notification. 
######3.	The app suggests fews ways for Susan to answer the notification. The app is having the calling button that allow Susan to call the nanny of Abby or her husband. The app is also having the camera button and cancel button. 
######4.  Susan first chooses to call the nanny but the nanny did not answer her phone call. Then, Susan calls her husband but she gets a voicemail; he must out of service range. 
######5.  Susan failed to contact the nanny and her husband. So, she clicks on the camera button from the app. This camera button is allowing Susan to activate the camera of Abby's wristband and she can see what Abby is doing now. When the camera is activate, she sees that Abby is drawing in her room. After she made sure that Abby is safe, she closes the app and continues her meeting with her client.
######6.	Five minutes later, the phones sounds a brief tone. Susan receive an instant message from the nanny:" Don't worry, Abby is scared by a rat just now. I had killed the rat and Abby has now calmed down."


###b. Requirements
Describe necessary capabilities of the product

####•	Functional and data needs: 
#####Mobile App
1.	Calling buttons: The user can set your emergency contacts here so that the user can call the one immediately when emergency.
2.	Camera button: To activate the camera of the wristband so that you can observe what your child is doing.
3.	Cancel button: To ignore the notifications.
4.	Data connect button: Users can view, organize, assess, and download all of the secondary users’ recorded data on a secure cloud platform. Users can also view graphs of Electrodermal Activity (EDA) also known as Galvanic Skin Response (GSR), Blood Volume Pulse (BVP), Acceleration, Heart Rate (HR), and Temperature.

#####Device (E&F Wristband)
1. Flash memory: Store data                           
2. Camera: Can be activate by the primary users through the app. Secondary users can use it to snap pictures and send the pictures to the primary users.                               
3. Sensor: Detect the emotions of the secondary users by detecting Electrodermal Activity (EDA) also known as Galvanic Skin Response (GSR), Blood Volume Pulse (BVP), Acceleration, Heart Rate (HR), and Temperature.      

####•	user mental models:
#####Primary users can observe the condition of secondary users all the time and get notifications when secondary users in bad emotional condition.

####•	design imperatives: 
#####The application get the data that detected from the device.
#####The application provides features of contacting the emergency contacts.
#####The device provides features of sending notifications to primary users when secondary users in bad emotional condition.

####•	product vision: 
#####Users are able to observe the conditions of their children with autism all the time.

####•	business requirements
#####Collected Information
- Users prefer a simple and user friendly interface

####•	technology: 
#####EDA sensor, 3-axis accelerometer, Camera, Phone


###2. Design Framework
###a. Elements
####a. Form factor, posture and input methods

####Form factor:
        This a sensor device and an application mobile phone.

####Posture:
        The mode of attention are emotions of autistic child.

####Input methods:
        This sensor detect the emotions and the application is uses touchscreen .


#####functional and data elements 
#####information - so that the user know how the sensor is performing
#####functions - to display the heartbeat rate and stress level of the user
#####mechanisms - performance rational thinking
#####actions - 
#####domain object models - sport watch


###Sketch

#####Device (E&F wristband)
[![14456728_599828330188338_906614571_o (1).jpg](https://s4.postimg.org/9z97ove1p/14456728_599828330188338_906614571_o_1.jpg)](https://postimg.org/image/pxhxf089l/)
