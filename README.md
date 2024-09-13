# ReadMe
Question 1:
 1. Sensor Specifications:<br>
   a. Specify that heart rate detection uses the smartphone's rear camera with flash on by having the user tap their finger on the lens to record a 45-second video.<br>
   b. For respiration rate detection, specify that the smartphone's accelerometer or orientation sensor is used to calculate respiration rate by detecting the rise and fall of the user's chest.<br>
 2. Data Collection and Processing Algorithms:<br>
    a. Specify how to process heart rate data extracted from the camera video to infer heart rate by analyzing changes in red in the image.<br>
    b. Define how to extract respiration rate from accelerometer or orientation sensor data to analyze the rise and fall of the user's chest.<br>
 3. Data Storage:<br>
    Heart rate and respiration rate data need to be stored locally in a database (e.g., using RoomDB or RealmDB). The data structure should include the user's vital signs data (heart rate, respiration rate) as well as symptom data.<br>
 4. UI Design:<br>
    a. Page 1: Collect heart rate and respiratory rate data.<br>
    b. Page 2: Collect symptom data and provide a scoring system, where users can score each symptom and store the data in the database.<br>
    c. The UI should also provide buttons to start/stop data collection, and an "Upload Symptoms" button to upload symptoms to the local database.<br>
 5. Context Awareness and Data Feedback:<br>
    Explain how the system provides feedback to users based on the collected data, such as providing suggestions based on detected vital signs.<br>
 6. Health Report Generation:<br>
    The Health-Dev system should be designed to generate health reports, analyze heart rate and respiratory rate data through long-term trends, provide health suggestions, and help users improve their health (healthDev).<br>

Question 2:
 1. Symptom data integration:<br>
    By combining symptom data (collected through the second page) with physiological signals (such as heart rate and respiration rate), the app can provide more personalized feedback. For example, if a user reports fatigue (a symptom), the app can analyze the physiological data to assess whether the user is showing signs of stress or fatigue.<br>
2. Provide feedback through health reports:<br>
  Based on the analysis of heart rate and respiration rate signals and the symptoms reported by the user, the app can generate a health report. The report can provide feedback to the user indicating whether they are within a healthy range or recommend specific actions to improve health.<br>
3. Innovative context-awareness and feedback:<br>
  To improve the context-awareness of the app, a new algorithm can be developed that monitors changes in the user's breathing and heart rate and provides real-time feedback. For example, if the respiration rate indicates that the user is breathing shallowly, the app can recommend relaxation exercises.<br>
4. Adaptive context-aware:<br>
  The app can be further developed to adjust feedback in real time based on changes in symptoms and physiological signals. For example, if the user's heart rate continues to rise after reporting stress symptoms, the app can suggest mindfulness or breathing exercises (bhealth-1).<br>

Question 3:<br>
&nbsp;&nbsp;&nbsp;&nbsp;Yes, my perspective has changed after completing Project 1 and reading the two papers. I think mobile computing is not just about application development, but a complex system involving context awareness, real-time data processing, and hardware integration. According to the two papers "bHealthy" and "Health-Dev", mobile computing is not just about developing front-end applications, it also involves deep integration of sensors with smartphones, and context awareness based on physiological feedback. For example, in the "bHealthy" application, the system obtains physiological data through sensors such as ECG and EEG, and provides personalized suggestions based on the user's psychological and physiological state. This shows that mobile computing requires not only developing interfaces, but also processing complex real-time data and generating feedback. "Health-Dev" shows how mobile computing can achieve automatic code generation through a framework, generate code for sensors and mobile phones from high-level specifications, and optimize the system's energy management, communication protocols, etc. These contents show that mobile computing not only deals with the functional development of applications, but also involves hardware optimization and dynamic adjustment of context. In Project 1, the process of detecting heart rate through a camera and measuring breathing rate through an accelerometer made me understand that mobile computing involves how to integrate multiple sensors and process the data collected by these sensors in real time. bHealthy and Health-Dev show that mobile computing goes beyond simple application development. The core of mobile computing is how to make the system perceive the user's state and provide feedback adaptively. Therefore, based on these two papers, the core of mobile computing is context awareness and real-time feedback, combining hardware, sensors and real-time data processing, not just front-end application development (bhealth-1) (healthDev).
