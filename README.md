# FriendZone - Real Time Chat Application

This is a real-time chat application built with React (client) and Node.js (server). It supports live messaging and integrates Google OAuth for user authentication.

## Features
- **Real-time Communication**: Instant messaging powered by WebSockets.
- **User Authentication**: Google OAuth integration for secure login.
- **Modern UI**: Clean and responsive interface.
- **Modular Codebase**: Separate client and server for scalability.

## Prerequisites
- **Node.js** (v14 or above)
- **npm** or **yarn**

## Installation

Follow these steps to set up and run the project locally.

### 1. Clone the Repository
```bash
git clone https://github.com/Ashwanisingh7930/FriednZone.git
cd realtime-chat-app
```

### 2. Setup the Client
```bash
cd client
npm install
```

### 3. Setup the Server
```bash
cd ../server
npm install
```

### 4. Configure Environment Variables
Create `.env` files in both the `client` and `server` directories and configure the following variables:

#### Client (`client/.env`)
```
REACT_APP_GOOGLE_CLIENT_ID=<Your Google Client ID>
REACT_APP_SERVER_URL=http://localhost:8000
```

#### Server (`server/.env`)
```
PORT=8000
URL=http://localhost:3000
SECRET=<Your Secret Key>
CLIENT_ID=<Your Google Client ID>
BASE_URL=http://localhost:3000
```

### 5. Run the Application

#### Start the Server
Open a terminal and run:
```bash
cd server
npm start
```

#### Start the Client
Open another terminal and run:
```bash
cd client
npm start
```

## Usage
1. Open your browser and navigate to `http://localhost:3000`.
2. Create an Account & Login
3. Start chatting in real time!

## Technologies Used
- **Frontend**: React, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB (optional, for storing chat history)
- **Authentication**: Google OAuth 2.0
- **WebSocket**: Socket.IO for real-time communication

## Screenshots
![Screenshot 2024-12-15 181151](https://github.com/user-attachments/assets/5d08a102-ff34-49f5-99cf-94f642ebec98)
![Screenshot 2024-12-15 181201](https://github.com/user-attachments/assets/6ed35b40-2197-4b4a-975b-7834c07be0aa)


## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Create a pull request.

## Connect with Me
- **LinkedIn**: [Ashwani Singh](https://www.linkedin.com/comm/mynetwork/discovery-see-all?usecase=PEOPLE_FOLLOWS&followMember=ashwanisingh09)
- **Instagram**: [ashwani_singh_09](https://www.instagram.com/ashwani_singh_09/)

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

Feel free to reach out if you have any questions or suggestions!
