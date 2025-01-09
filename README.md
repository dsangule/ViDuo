# ViDuo by Dev n Dev

ViDuo is a video-sharing platform being developed by Dev n Dev. The project is still in its early stages, but the vision is to provide users with a seamless experience for discovering, uploading, and watching videos, powered by machine learning for personalized recommendations.

**Project Status**: Work in progress. Nothing has been fully implemented yet.

## Live Demo
Currently, the demo of ViDuo is available at:  
[https://viduo.vercel.app](https://viduo.vercel.app)  
*Note: The current demo might be limited as development is ongoing.*

## Features Completed
- **Frontend Setup**: Next.js and Tailwind CSS have been initialised.
- **Hosting**: The frontend is hosted on Vercel for easy deployment and testing.

## Future Plans (In Progress)
- **Machine Learning-Powered Recommendations**: Integrating a recommendation engine that will suggest personalized videos to users.
- **Video Upload**: Implementing a feature that allows users to upload their own videos.
- **Search Functionality**: Building an efficient search feature to find videos quickly.
- **User Profiles**: Allow users to create accounts and customize their profiles.
- **Backend Setup**: Setting up Flask for handling API requests, video storage, and more.

## Tech Stack
- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Flask (for handling API requests and ML model integration)
- **Database**: Meilisearch (for fast and efficient search)
- **File Storage**: Cloudinary (for storing and serving video content)
- **Hosting**: Vercel (for frontend) and Render/Railway (for backend)
- **Machine Learning**: Custom recommendation model (in development)

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/dsangule/viduo.git
cd viduo
```
### 2. Install dependencies
For frontend:
```
cd frontend
npm install
```
For backend:
```
cd backend
pip install -r requirements.txt
```
### 3. Run the project locally
For frontend:
```
npm run dev
```
For backend:
```
python app.py
```
The frontend will be available at http://localhost:3000, and the backend at http://localhost:5000.
