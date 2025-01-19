# Vijayini
To ensure women's safety in the end-to-end process described, a combination of technologies needs to be employed, including **AI, IoT, Blockchain, Cloud Computing, and Mobile Applications**. Here's how these technologies are used and integrated:

---

### **1. AI-Powered Street Cameras**
   - **Technology Used:**
     - **Computer Vision**: Detect suspicious behavior using real-time video feeds.
- **Machine Learning (ML)**: Train models on datasets containing labeled examples of suspicious activities, such as aggression, stalking, or unauthorized vehicle entry.
     - **Object Detection Models**: Utilize frameworks such as YOLO (You Only Look Once), Faster R-CNN, or OpenCV for human, vehicle, and behavioral pattern identification.

   - **Integration Process:**
- AI algorithms monitor live video feeds from cameras installed all over the city.
Suspicious activities send alerts, which are then forwarded to the **nearest police control center** along with live video evidence.
Alerts are shared with connected systems, such as the **Himmat app backend** and **Distributed Storage Systems**, using APIs.

---


### **2. Distributed Storage Channels**
- **Technology Used:**
     - **Blockchain**: For storing video evidence on tamper-proof, decentralized storage platforms. Blockchain ensures transparency and immutability.
     - **IPFS (InterPlanetary File System)**: To share video evidence securely among entities like the Delhi Commission for Women (DCW) and NGOs.
- **Cloud Computing**: Other storage options include Amazon S3, Google Cloud Storage, or Azure Blob Storage.

   - **Integration Process:**
     Video clips captured by cameras are encrypted and stored on **blockchain nodes** or **cloud servers.
- Only the records are accessible through a read-only system to authorities like police and NGOs, for ensuring accountability while the evidence cannot be tampered with.

---


### **3. Himmat App Features
   - Technology Used:
    - **GPS and Geolocation APIs**: Track location in real-time
    - **Push Notifications**: Alerts emergency contact as well as nearby police station at the exact time.
- **Mobile Development Frameworks**: Develop the app using **React Native**, **Flutter**, or **Kotlin**.
     - **Real-Time Routing**: Utilize **Google Maps APIs** or **Mapbox** to indicate the safest route to shelters or hospitals.

   - **Integration Process:**
     - The app is connected to the city's central emergency response system.
- Upon panic button press
       - Application sends the user's location to his emergency contacts and the police station.
       - A database like Firebase or MongoDB retrieves the nearest **safe spaces** verified.
- The app uses **navigation APIs** to guide the user to safety with real-time routing.

---

### **4. AI-Powered City Surveillance for Tracking**
   - **Technology Used:**
     - **Vehicle License Plate Recognition (LPR)**: To track the movement of vehicles used in crimes.
     - **Facial Recognition**: To identify suspects based on their images.
Pattern Recognition: Detect suspicious movements, such as goons fleeing or taking unorthodox routes in their vehicles.
IoT: Connect and command AI-powered cameras spread over the city

   Integration Process:
AI models look at the video feeds of different cameras to detect incidents such as kidnapping or hostage situations.
- A centralized system receives all the incident alerts and tracks the path of the suspect on geotagged locations.
  - The action plan (e.g., vehicle and suspect location) is provided to the authorities through a dashboard or mobile app.
____________________
 
### **5. Police Response System**
   - **Technology Used:**
    - **Real-Time Communication APIs**: Twilio or Firebase Cloud Messaging for alerting police.
- **Emergency Dispatch Software**: Police vehicle deployment is managed with **AI-driven predictive models** for the best response time.
- **Incident Management Dashboards**: Built using web technologies like **ReactJS** or **Angular**.

   - **Integration Process:**
     - As soon as an alert is triggered, whether it's from AI cameras or the Himmat app, the police control center is immediately notified.
- Officers monitor the real-time streaming updates on their dashboards, be it the path of escape taken by the suspect or the location of the victim.
   - Emergency response teams can be activated, and their movements can be tracked through GPS.

---


### **End-to-End Integration**
The system will integrate all these technologies into one cohesive process:

1. **Data Flow:**
   - AI-enpowered cameras monitor video feeds and send alerts to the central system.
- Alarms prompting appropriate storage on blockchain-based channel network.
  - Integration of the Himmat app with the system for alerting emergency contacts and redirecting victims to safety.

2. **Communication between Components:**
  - APIs and Webhooks allow for real-time communication between cameras, the app, cloud systems, and police stations.
  - Secure video evidence sharing through blockchain networks.

3. **Cloud and Edge Computing:**
- Large data storage and processing are on the cloud servers, while real-time AI computation is on edge devices (cameras).

4. **User Interaction:**
   - Victims will interact with the Himmat app for alerts and routing.
   - Authorities will use dashboards for evidence review and response coordination.

---

### **Technology Stack**
- **AI Models**: TensorFlow, PyTorch, OpenCV, YOLO.
- **Backend**: Node.js, Python (Flask/Django).
- **Frontend**: ReactJS, React Native (for mobile).
- **Storage**: Blockchain, IPFS, Cloud Storage (AWS/GCP/Azure)
- **Maps/Geolocation**: Google Maps API, Mapbox
- **Communication**: Twilio, Firebase Cloud Messaging
- **Databases**: MongoDB, PostgreSQL

The integration of the above-mentioned technologies ensures an all-rounded, tamper-proof safety net for women in real time.


This approach abides by Laws of India that is
Bharatiya Sakshya Adhiniyam Act, evidences from government cameras act as strong proofs preventing the misuse of evidence along with Bhartiya Nagrik Suraksha Samhita to streamline the procedure with fast access to proofs. 
Bharatiya Nyay Sanhita to provide awareness among common public about crimes and their severity, The procedure to be followed in case of any crime as per Bhartiya Nagrik Suraksha Samhita. Rights under Protection of Women from Domestic Violence Act & Dowry Prohibition Act through the Himmat App. 

