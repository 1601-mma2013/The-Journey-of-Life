# The-Journey-of-Life

## I. Analysis

### 1. Research

### a. Scope

-	To let the parents to understand their autistic child.

### b. Audit

####1. Existing products

#####-Q Sensor 
###### A device  that can detect and record physiological signs of stress and excitement by measuring slight electrical changes in the skin.
###### *Cons: - Data acquisition is not very accurate.

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

- The notifications cannot reach to the users when the device or the users' phones is out of battery.
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
-	(user’s) attitudes -  They are willing to know the emotions and conditions of their child when they are not beside their child. They are willing to know their child well through consult the expert in autism field. 
-	(user’s) motivations – Know their children’s conditions all the times.
-	(user’s) environments - Anywhere that in good phone service range.
-	(user’s) tools - Mobile phone
-	(user’s) challenges - Unable to access the app at a bad phone service range area.


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
-	(user’s) motivations – Willing to communicate with their parents.
-	(user’s) environments - Anywhere that in good phone service range.
-	(user’s) tools - Wristband
-	(user’s) challenges - Unable to access the app at a bad phone service range area.



##2. Modeling

###a. Personas

#####Name : Susan
#####Gender : Female
#####Age : 31
#####Occupation : Lawyer

####Bio

- Susan is a lawyer. She is busy in her works. 
- Susan is a mother of an autistic child, Abby.  She is no expert of autism and she cannot accompany Abby all the time. She always phones the nanny of their child to know the emotion and activities of their child. However, she is willing to know the emotions and conditions of Abby when they are not beside Abby.

####1. Goals

- As a mother, she wants to understand about her autistic child, Abby.

####2. Patterns in user and customer behaviours

- She busy in her works all the time and she has no time to accompany her child. She always phones the nanny to get to know Abby's emotion and activities all the time.

####3. Attitudes

- She wants to understand Abby better. Besides professional autism therapy services, she and her husband bring Abby to interative with programs of autistic children once a month. Also, she and her husband attend to the training programs that teaches parents strategies for managing challenging behaviour in children with autism when they have free time.

####4.	Environments 

- Anywhere that in good phone service range.

####5. Tools 

- Mobile phone

####Challenges 

- Unable to access the app at a bad phone service range area.



##II. Synthesis
###1. Requirements Definition
###a. Context Scenarios

#####-Our persona is Susan Wong, a professional lawyer, whose goals are to understand her autistic child.
#####-Here is Susan’s context scenario:
######1.	While getting ready in the morning, Susan makes sure her child, Abby is wearing the E&F wristband before she is going to work.
######2.	When she is dealing with her client, her phone rings. She checks her phone and she received a notification from the app. Normally while she is in an appointment, she will mute her phone, but when Abby is experiencing emotional turmoil, the app will automatically send her a notification. 
######3.	The app suggests fews ways for Susan to answer the notification. The app is having the calling button that allow Susan to call the nanny of Abby or her husband. The app is also having the camera button and cancel button. 
######4.  Susan first chooses to call the nanny but the nanny did not answer her phone call. Then, Susan calls her husband but she gets a voicemail; he must out of service range. 
######5.  Susan failed to contact the nanny and her husband. So, she clicks on the camera button from the app. This camera button is allowing Susan to activate the camera of Abby's wristband and she can see what Abby is doing now. When the camera is activated, she sees that Abby is drawing in her room. After she made sure that Abby is safe, she closes the app and continues her meeting with her client.
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
#####The application gets the data that detected from the device.
#####The application provides features of contacting the emergency contacts.
#####The device provides features of sending notifications to primary users when secondary users in bad emotional condition.

####•	product vision: 
#####Users are able to observe the conditions of their children with autism all the time.

####•	business requirements
#####Collected Information

- Users prefer a simple and user friendly interface

#####Key Attributes of the Product

- A customized serviced specifically for autism.
- Primary users will receive an alert notification when the secondary user is in a bad emotional condition.
- Primary users can check the condition of the secondary user by activate the camera on the wristband.

#####Scope of the Project

- To let the parents to understand their autistic child.

#####Phases of the Project

- With alert messages, primary user will be informed when the secondary user is in a bad emotional condition.
- This device provides many ways for the primary users to observe the secondary users.


####Technology: 
#####EDA sensor, 3-axis accelerometer, Camera, Phone


###2. Design Framework
###a. Elements
####a. Form factor, posture and input methods

####Form factor:
        A sensor device and an application mobile phone.

####Posture:
        The mode of attention are emotions of autistic child.

####Input methods:
        This sensor detect the emotions and the application is uses mobile phone.

####b.Functional and data elements 

####Fundamental subjects :
     - Primary users get the data acquisition that detected by secondary users .

####Relationship between each other :
     -  After detect the emotion of secondary users, it will show the data in mobile application.

####Functional elements based on functional requirements:
     - Primary users can key in the emergency contacts and save the data of the secondary users.

####Accomplish user’s goals
     - Primary users can know their autistic child's(the secondary users) emotions all the time.
        
####Best fit the design principles
     - One screen design with simple button to let the users check the data easily.
     
####Fit within technology
     - This application is done by are using mobile phone and sensors as the technology.

####Differentiation of interaction from competitors
      - This application is specifically for parents by providing accurate data and information from the sensor device.
      - Primary users can observe secondary users' emotion all the time.

####c. Functional groups and hierarchy
[![Functional group and hierachy.jpg](https://s16.postimg.org/8pzf7bxbp/Functional_group_and_hierachy.jpg)](https://postimg.org/image/gvhh5hlkh/)

####Interaction patterns and principles
    - This application provide visible interaction design. The UI components such as buttons that are standard are easily understood for users to click and tap.
     - This application provide learnable interaction design, which users learn the functions.
     - This application provide consistent interaction design. Users able to focus on the context when the elements, behaviours and styles are consistent.

####Select primary views (screens or states)
     - By focusing user’s goal, the main view is the summarized emotional data of secondary users.

###Sketch

#####Device (E&F wristband)
[![14456728_599828330188338_906614571_o (1).jpg](https://s4.postimg.org/9z97ove1p/14456728_599828330188338_906614571_o_1.jpg)](https://postimg.org/image/pxhxf089l/)
[![Design sketch.jpg](https://s13.postimg.org/t0dn299jb/Design_sketch.jpg)](https://postimg.org/image/83hexlbib/)

###Key Path Scenario
1.	Susan actives the apps with her Android phone. At the homepage, Susan click in into the main page. Susan click the “call” page to key in the emergency contact to easily to find people.
2.	Next, Susan taps “Data Connect”. Susan can view, organize, access and download all the recorded data from her daughter Abby at “Secondary user’s data” tab. Susan will turn on her mobile phone and the sensor device’s Bluetooth to transfer the pervious data into the “History data” tab.
3.	In the “EDA” tab, Susan can see the graph of EDA from her daughter. Susan taps the “3-axis accelerometer” tab inside are the data of the movement and the activity of her daughter.
4.	Susan wants to see her daughter all the time, she wants to click the “Camera” tab to activate the camera of the sensor device. For the “Cancel” tab is to ignore the notification.

