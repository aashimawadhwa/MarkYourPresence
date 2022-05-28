# MarkYourPresence


## Setup

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

- Install MongoDB using their documentation and start the MongoDB server.

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
