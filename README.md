# MarkYourPresence

#### Demo video link : 
#### Hosted web application : 
 



### 📌 Table of Contents

<a id="features"></a>
## 🚀 Features

<a id="tech-stack"></a>
## 💻 Tech Stack Used/ Dependencies

<img alt="React" src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/><img alt="Express.js" src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB"/><img alt="TailwindCSS" src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"/><img alt="Visual Studio Code" src="https://img.shields.io/badge/VisualStudioCode-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white"/><img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/>![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

***React*** : Front-end JavaScript library for building user interfaces or UI components.

***React Router Dom*** : Responsibile for rendering UI components according to the URL paths.

***Express*** : Back end web application framework for Node.js (a JavaScript runtime environment).

***Opencv*** : Automatic face recognition is all about extracting those meaningful features from an image, putting them into a useful representation and performing some kind  

***Tailwind CSS*** : A utility-first CSS framework for rapidly building custom user interfaces. Used by adding the required styles as classes.

***CORS*** : A HTTP-header based mechanism that allows a server to indicate any other origins (domain, scheme, or port) than its own from which a browser should permit loading of resources. Used here for communicating between server and client side hosted.

***Flask*** :Flask is a small and lightweight Python web framework that provides useful tools and features that make creating web applications in Python easier


***Others*** : React icons and react-copy-to-clipboard.


## Setup/starting up

### 1. Install Front-end

To run the front-end:

- Clone the repository. 

- Navigate to the cloned repository and install dependencies by running: 
```sh
npm install
```
- Now, start the server
```sh
npm start
```

### 2. Install Back-end

- The project requires python 3.7. Other versions may create issues.

- Install [MongoDB ](https://www.mongodb.com/docs/guides/server/install/)using their documentation and start the MongoDB server.


- For starting server and stopping the server-
```sh
sudo systemctl start mongod

```
```sh
sudo systemctl stop mongod

```


- Navigate to `backend/` folder and install the python dependencies:
```sh
pip install -r requirements.txt
```
- Run main.py

### 3. Connect front-end to back-end

- Note the local host url the backend server is running at (as given in the terminal output). 
Paste this url in `config/api.js` eg: 
```sh
// End point of your flask api.
export const apiEndPoint = 'http://127.0.0.1:5000/';
```
<a id="agile"></a>
## ⚡️ Agile methodology followed during the build
The Agile methodology is a way to manage a project by breaking it up into several phases. It involves constant collaboration with stakeholders and continuous improvement at every stage. 

![7](https://user-images.githubusercontent.com/73706697/170858585-bac14181-c6f4-428d-b0e4-13954abccd63.png)





<a id="hosting"></a>
## ✅ Hosting 

- Frontend is hosted at 
- Backend server is hosted at 

<a id="challenges"></a>

## 💡 Timeline and itreations followed-
![9](https://user-images.githubusercontent.com/73706697/170859808-54aa155d-3dac-4a10-9d2e-0fe07d514c60.png)
![10](https://user-images.githubusercontent.com/73706697/170859809-f6c44748-a7f8-43a3-8976-3614d2c63745.png)


## 💡 Challenges faced and learnings



- Before the Microsoft Engage Program's qualification announcement, I had only a rudimentary understanding of React. After learning the new concepts associated with React, I began the design-build phase of this project.
- For my love of frontend styling,Improved my CSS skills vastly by practising them here.
-Never worked with OpenCV and ML database , learned it within a week and implemented and incoprated it within my application.
- learned about  how a low-complex, embedded friendly CNN architecture can be used for face recognition.
- I'm new to python and Opencv and I tried to save an image to my computer from my webcam , But when I try to open it, I find that the jpeg is empty i worked on small errors like these.
- Figured out how attendence  can be downloaded through webapp.
- Came across a memory-leak bug while building a socket connection from client side to server side. Couldn't get my doubt resolved even from Stack Overflow. Took me about one week to resolve it by thorough researching of the hints provided by my mentor. Saved my project from getting disqualified because this bug was a barrier in implementing the minimum requirement feature of the Engage'21 Challenge.
- Deployed a full stack app with frontend, backend and database for the first time. Struggled through it but documentations and tutorials came to the rescue as always. 
- Learnt about Cross-Origin Resource Sharing (CORS) and proxies.


<a id="scope"></a>
## 🚧 Future Scope/ What's next?

- [ ] Dark theme toggler.
- [ ] Password resetting and email verification on sign up.
- [ ] Voice calling within the app feature
- [ ] Fee payment after authentication through face ID
- [ ] Student portal
- [ ] Multiple and simultaneous login from different accounts of the same user.

<a id="resources"></a>
## 📚 Resources

- [React Router Dom Guide](https://reactrouter.com/web/guides/quick-start)
- [Tailwind CSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)
- [React Icons Documentation/Guide](https://react-icons.github.io/react-icons/)
- [Heroku Documentation](https://devcenter.heroku.com/categories/reference)
- [Netlify Docs](https://docs.netlify.com/)

<a id="bug"></a>
## 🐛 Bug Reporting
Feel free to [open an issue]
<a id="feature-request"></a>
## ⭐ Feature Request
- Feel free to [open an issue] on GitHub to add any additional features you feel could enhance this project.  
- You can also discuss and provide suggestions to me on [LinkedIn]












