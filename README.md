

# 🎬 Video Streaming App

![Next.js](https://img.shields.io/badge/Next.js-v13.0-blue?style=for-the-badge)
![Express](https://img.shields.io/badge/Express-v4.18-green?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-v5.0-brightgreen?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-v18.0-yellowgreen?style=for-the-badge)
![Bcrypt](https://img.shields.io/badge/Bcrypt-Security-orange?style=for-the-badge)

A Netflix-inspired full-stack **Video Streaming App** built with **Next.js**, **Express**, **MongoDB**, and **Node.js**. This project features an interactive user interface with secure authentication to provide a smooth video streaming experience.

## 🚀 Features

- **Interactive UI**: Netflix-like user interface for browsing and watching videos.
- **Secure Authentication**: Session-based authentication using `express-sessions` and password hashing with `bcrypt`.
- **YouTube Integration**: Videos fetched and managed using the **YouTube Developer API**.
- **Scalable Backend**: Built on **Express.js** and **MongoDB** for handling multiple user requests and data storage.
  
## 🛠️ Tech Stack

- **Frontend**: Next.js
- **Backend**: Express.js, Node.js
- **Database**: MongoDB
- **Authentication**: Bcrypt for hashing passwords, Express-sessions for session management
- **External API**: YouTube Developer API for fetching video data

## ⚙️ Installation

### Prerequisites

- Node.js (v16+)
- MongoDB (v5.0+)
- YouTube Developer API Key

### Clone the repository

```bash
git clone https://github.com/your-username/video-streaming-app.git
cd video-streaming-app
```

### Backend Setup

1. **Install Backend Dependencies**:
    ```bash
    cd backend
    npm install
    ```

2. **Set up MongoDB**:
   Ensure MongoDB is running locally or on a server. Create a `.env` file in the `backend` directory and add the following:

    ```
    MONGODB_URI=your_mongodb_uri
    SESSION_SECRET=your_session_secret
    YOUTUBE_API_KEY=your_youtube_api_key
    ```

3. **Start the Backend**:
    ```bash
    npm run dev
    ```

### Frontend Setup

1. **Install Frontend Dependencies**:
    ```bash
    cd frontend
    npm install
    ```

2. **Start the Frontend**:
    ```bash
    npm run dev
    ```

The app will be running on `http://localhost:3000`.

## 📚 Usage

1. Sign up or log in with your account.
2. Browse through the video library powered by YouTube API.
3. Enjoy seamless video streaming with a Netflix-like experience.


## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, submit issues, or open pull requests.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 📧 Contact

- **Name**: Anjali Mittal
- **Email**: anjalimittal320@gmail.com


