# Zimpilo

## Inspiration
- The Covid-19 pandemic had an adverse effect on Indian Healthcare  infrastructure.
- As India has a huge population many people were not able to have access to medical facilities owing to the lockdown. In such a situation the need of a remote platform arose which would provide easy medical access to people who need it the most. Hence **Zimpilo** was created to solve the above problem.
- Among all the emergency services, most affected are the health services on which almost every citizen is dependent.
- Due to the adverse effects and lack of online platforms for health services, both the covid patients and non-covid patients are suffering by getting untimely treatment or no treatment at all.
- Lockdown has also limited communication between hospitals which are operating on the traditional methods data storage.
- To address the above stated problems, we have decided to build an online platform for the healthcare services.


## What it does
- Prompt medical attention
- Get a second opinion
- Access to specialists
- Privacy & availability
- Comfort and convenience
- Cost-effective and time-saving
- No need to save all the medical reports
- Fewer chances of catching a new illness
- One of the features incorporated is nearby hospital search which would show the bed vacancy, blood bank availability, ambulance services, speciality and - ICU availability
- Availability of diagnostic reports and prescriptions will be completely online and personalized with each patient’s location for automated home delivery.


## How we built it
1. Frontend
    - HTML
    - CSS
    - Bootstrap
    - JavaScript
2. Backend
    - NodeJS
    - ExpressJS
3. Database
    - Mongodb
4. WebRtc
    - Socket.io
    - Peerjs


## How To Run
1. Clone the directory from the github repository.
2. Run npm install.
3. Run nodemon.
4. To enable video calling, run “peerjs --port 3001”
5. To run SMS service, add fast2sms API key as environment variable (recommended step to avoid any unnecessary errors)

## Few Insights
![Landing Page](/assets/images/READMEimages/landingPage.jpeg)

![Dashboard Page](/assets/images/READMEimages/dashboard.jpeg)

![Donation Index Page](/assets/images/READMEimages/organDonationIndex.jpeg)

## What's next for Zimpilo
We are planning to add- 
- A Notification Alert System
- Live tracking
- Portal to Order Medicines from nearby Medical Stores
- We will extend the the limit of our platform by involving other
services.
- We will add functionality to directly import data from various
health related electronic devices to our database.
- Currently Zimpilo connects the database of hospitals within a city. We are trying to increase our reach and will be developing our database further to handle atomic data.

