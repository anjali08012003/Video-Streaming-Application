

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



### 🚀 Features

1. **🎥 Netflix-Inspired UI**:  
   The user interface is designed to resemble Netflix, offering an immersive experience with a modern, responsive layout. Users can easily browse through available videos, view detailed information about each video, and stream them directly within the app.

2. **🔐 Secure Authentication**:  
   The app uses session-based authentication to ensure secure access for registered users.  
   - **Express-Sessions**: Users remain logged in during their session without requiring constant re-authentication. Session data is securely stored in MongoDB.
   - **Password Hashing with Bcrypt**: User passwords are never stored in plain text. Using `bcrypt`, passwords are hashed and salted to enhance security, ensuring that even if the database is compromised, user credentials remain safe.

3. **📡 Video Fetching with YouTube Developer API**:  
   The app integrates with the **YouTube Developer API** to fetch video data in real-time.  
   - Users can view trending videos and get detailed metadata such as video duration, likes, views, and comments.
   - The API enables smooth loading and streaming of videos directly within the platform.

4. **🔍 Advanced Video Search**:  
   Users can search for videos based on title, description, or genre. The search functionality is optimized to return relevant results quickly by leveraging YouTube API's search capabilities.

5. **💬 User-Friendly Dashboard**:  
   The app includes a user dashboard where users can:
   - View their watch history.
   - Mark videos as favorites for quick access later.
   - Keep track of previously watched videos with timestamps to continue watching from where they left off.

6. **📂 Playlist Management**:  
   Users can create custom playlists of their favorite videos:
   - **Add to Playlist**: Add any video to one or more custom playlists.
   - **Organize Playlists**: Rename, edit, or delete playlists as needed to keep their video library organized.

7. **📊 Analytics & Watch Stats**:  
   Each user can view analytics of their streaming habits, including:
   - Total videos watched.
   - Total time spent streaming.
   - Video watch time for individual videos.
   This feature gives users insight into their viewing habits and helps them track progress on their playlists.

8. **🌐 Real-Time Streaming**:  
   The app leverages efficient caching and buffering strategies to ensure smooth, real-time video streaming even on slower internet connections. Videos are progressively loaded, ensuring minimal buffering.

9. **🔒 Role-Based Authorization (Future Scope)**:  
   The project is designed to easily support role-based authorization, where different users (admins, premium users, regular users) can have varying access levels and features. Premium features like HD/4K streaming can be added for premium users in future updates.

10. **🌟 Responsive & Cross-Platform Compatibility**:  
    The application is designed with responsiveness in mind, ensuring it works seamlessly across devices:
    - Mobile, tablet, and desktop compatibility.
    - A consistent user experience no matter the screen size.

11. **🛠️ Scalable Backend**:  
    Built with **Express.js** and **MongoDB**, the app’s backend is optimized for high scalability:
    - The non-blocking nature of Node.js ensures that the server can handle multiple simultaneous requests efficiently.
    - MongoDB is used for storing both user session data and video metadata, ensuring fast and scalable database operations.

12. **💬 User Feedback and Ratings (Planned Feature)**:  
    A planned feature is allowing users to leave feedback and rate videos, helping to improve the app’s content recommendations.



## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, submit issues, or open pull requests.



## 📧 Contact

- **Name**: Anjali Mittal
- **Email**: anjalimittal320@gmail.com


