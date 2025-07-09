
# Mock2Win🎙️🤖

This is a full-stack real-time AI-powered voice interview web application that lets users practice mock interview questions via voice along with feedback. Built using React, Node.js, Socket.io, OpenAI (for speech-to-text and GPT), and MongoDB, this project allows users to have seamless voice interactions with an AI interviewer.

---

## 🚀 Features

- 🎤 Real-time voice recording and streaming
- 🧠 AI-generated questions and follow-ups (via GPT-4)
- 📝 Speech-to-text conversion (via OpenAI Whisper)
- 👤 User authentication (login/signup)
- 📊 Session storage and history tracking
- - 🧾AI-generated performance feedback at the end of each interview session based on candidate responses
- 🌐 Full deployment ready (Vercel + Render/Heroku)


---

## 🧰 Tech Stack

| Layer        | Technology                          |
|--------------|--------------------------------------|
| Frontend     | React, Tailwind CSS, Socket.io-client |
| Backend      | Node.js, Express, Socket.io          |
| AI Services  | OpenAI Whisper API + GPT-4 API       |
| Auth         | JWT (JSON Web Tokens)                |
| Database     | MongoDB (via Mongoose)               |
| Deployment   | Vercel (Frontend) + Render/Heroku (Backend) |

---

## 🛠️ Installation

### Prerequisites

- Node.js v16+
- MongoDB (local or Atlas)
- OpenAI API key
- Git

### Clone the Repository

```bash
git clone https://github.com/SwiftCoder05/Mock2Win.git
cd Mock2Win
````

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` folder with the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
```

Start the backend server:

```bash
npm run dev
```

### Frontend Setup

```bash
cd ../frontend
npm install
npm start
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 🧭 Project Structure

```
ai-voice-agent/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── .env
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
├── README.md
```






---

