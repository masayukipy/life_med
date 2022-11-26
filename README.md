
## _Automating Healthcare_ 🩺

_**Our Mission is to automate Healthcare and make Health facilities available to everyone regardless of their limitations**_ <br />
Our Goals:

1.  Automate Healthcare Medical Appointments
2.  Online Disease Severity Prediction based on input symptoms through AI enabled chat-bots
3.  Online Medical Document Storage for Doctor-Patient Interactions
4.  e-Ambulance Tracking

## Module-Wise Description 🗒

-  _**Registration**_ 📝 <br/> 
_The web application would have a facility for the user's to register as either doctors or patients. Both of them would have access to specific features of the application.
The hospitals could manage the patient's appointments and assign appropriate slots for particular consultations._

- _**Appointment Scheduler**_ 📅 <br/> 
_The patient would be able to book appointments for the particular time slots he wishes to visit the hospital for._

- _**Disease severity prediction**_ 🤒 <br/> 
_This module would provide an automated, AI enabled chatbot which would provide inputs on the medical condition of the user, in case medical help is not accessible_

- _**Medical Record Storage**_ 📙 <br/> 
_This module would enable online storage of patient's documents, this will help preserve them and avoid the hassle of carrying them for every consultation._

- _**e-Ambulance Tracking**_ 🚑 <br/> 
_It would aid people in urgent need of medical help, the web app would provide the facility to book and track ambulances for essential help._

## How to run the project locally? [Using Scripts]

**Windows**<br />
```
$ cd scripts
$ sh startbackend.sh
$ sh startfrontend.sh
```

**Unix/Linux/Mac**<br />
```
$ cd scripts
$ chmod +x startbackend.sh
$ ./startbackend.sh
$ chmod +x startfrontend.sh
$ ./startfrontend.sh
```
<h2>Lint and Format 📜</h2>

- We use [Flake8](https://flake8.pycqa.org/en/latest/manpage.html) and [Black](https://pypi.org/project/black/) for linting & formatting source code of this project.
<br>
**Run QA checks on local environment ⚡** :
<br>

  - Run Shell script on Windows 💾 :

  ```
  ...\lifeMEDeasy> .\lifeMEDeasy_QA_checks
  ``` 

  - Run Shell script on Linux 👨‍💻 :

  ```
  .../lifeMEDeasy$ ./lifeMEDeasy_QA_checks
  ``` 
  
  - Alternate option ✔ :
    - Run this on terminal ⚡:
      - Windows 💾
        ```
        ...\lifeMEDeasy> black .
        ``` 
        ```
        ...\lifeMEDeasy> flake8 .
        ``` 
      - Linux 👨‍💻
        ```
        .../lifeMEDeasy$ black .
        ``` 
        ```
        .../lifeMEDeasy$ flake8 .
        ``` 
