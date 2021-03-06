# MED-ASSIST

This application was developed using flutter by the following people:
- Vardan Saini
- Meharpreet Singh Nanda
- Bhavnoor Kaur
- Kartik Ohri
  
This is an app designed with a very intuitive and simple UI/UX interface keeping the **senior citizens** as the target user in mind. This app aims to assist the older people manage their health by giving them reminders to take their medicines on time, monitor their daily activity, and give them access to resources in case of emergency.

---

### INSPIRATION

Among the Canadian population, living alone becomes increasingly more common as people age, especially for older women. According to the 2011 census, 31.5% of women aged 65 and over lived alone compared to 16% of senior men. Most of the medical problems rise with increase in age and so does the need of immediate help for people living alone.

We wanted to make a platform where anyone living alone (especially older people) with a medical conditions can get reminders for taking medicines on time, can have a record of their medical history at one place, and can ask for help if and when required.

With severe medical conditions and growing old, taking required medicine on time, become increasingly important especially for people living alone. Also, sometimes it becomes really hard for patients and doctors to keep track of the past and current health/medical conditions specially when people tend to go to different doctors for different health issues. If the history of medical conditions is not known by the doctor, this can result in serious concerns as some medications should not be provided to people with specific health issues. On top of that, we wanted to focus on the fact that for someone living alone, getting help when required can be difficult for things like getting medicine or even a medical emergency. So, we thought of a system, where people who are in need of help can be connected to community volunteers around them. The volunteers will get access to their surrounding community map and location of the person who needs help including basic details of that person.

Keeping a check and providing help when required is even more concerning these days because of COVID-19 pandemic when we cannot physically be in touch with our near and dear ones.

### WHAT IT DOES

The mobile application "MedAssist" that can send these people reminders about medications, keeps a record of all the medical conditions they have had in the past (which are then automatically sent to the health authorities in case of emergency) and also connects them to volunteers in case they need help with anything. This application also features an emergency button, which when prompted sends an alert with the person's location to all the family members and nearby volunteers to assist the person. The person needing help is matched with the closest volunteer that is available.

### HOW WE BUILT IT

The frontend was built using flutter for compatibility with both Android and iOS. We integrated Google Maps API to implement volunteer matching system which tracks the location of the nearby volunteers and also sends them the location of the the person in need of help. We used Google Cloud services to store our data at the backend and then use it to implement functionality.

### CHALLENGES WE RAN INTO

Integrating both frontend and backend was a challenge in itself for us. We had limited access to free resources to implement full functionality. Flutter being a fairly new language had limited resources to resolve some of the errors we had. Integrating maps to track and send location was also a big challenge

### WHAT WE LEARNED

We as a team identified and solved the problem of combining a lot of complex thoughts into a very simple user interface by timely monitoring our progress and narrowing our focus to our motivation and the solution that we came up with. We developed good communication skills and learnt to manage a project from both a developer’s and a user’s perspective through collaborative work. By working in a team we also learned a a lot about GitHub collaboration and learnt how to solve issues like merge conflicts that we ran into very often as we all were working at the same time. We learnt the integration of backend and frontend and integrating google cloud services in our app.

### WHAT'S NEXT FOR MED-ASSIST

We believe this application has a lot of potential. We further want to build a platform (like a website) connected to this application from which doctors can upload any medical documents to their profile and leave comments about their health conditions. This platform will also enable the doctors to access their patients profile with all the history of medical conditions that the person has had. Another feature that we are looking forward to is going to be Reminders through automated calls instead of notifications as we believe reminders are more effective through interactive communication. We plan to add the following features as well:
- Collect user’s past medical data and send it with the alert to 911 by using Text-to-911 through just a simple click on the app. This will also help in sending requests to 911 for non-medical emergencies by contacting the police and fire department based on the need.
- Add reminders for appointments and ordering medication (with automation).
- Monitor fluctuations in BP and Sugar levels and sending reminders.
- Send information about nearest senior citizen clubs and activities to the user.
- Send reminders to the user in the form of text, audio, and flashing light considering that problems like impaired vision and hearing problems are common in aged people.
- Save the time of volunteers by notifying all receivers of an alert of one volunteer responding to the situation.

### FEATURES
<img alt = "Flutter" src = "https://img.shields.io/badge/Flutter-57585D?style=for-the-badge&logo=flutter"> <img alt = "Android" src = "https://img.shields.io/badge/android-57585D?style=for-the-badge&logo=android"> <img alt = "ios" src = "https://img.shields.io/badge/ios-57585D?style=for-the-badge&logo=ios"> <img alt = "Android-Studio" src = "https://img.shields.io/badge/android%20studio-57585D?style=for-the-badge&logo=android%20studio">  <img alt = "Dart" src = "https://img.shields.io/badge/dart-57585D?style=for-the-badge&logo=dart"> <img alt = "firebase" src = "https://img.shields.io/badge/firebase-57585D?style=for-the-badge&logo=firebase"> <img alt = "google cloud" src = "https://img.shields.io/badge/google%20cloud-57585D?style=for-the-badge&logo=google%20cloud">


---
[DEVPOST](https://devpost.com/software/medassist-uo9avc)