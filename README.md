

# AI-Powered Blog App

**AI-powered full stack blog app** using **MongoDB, Express.js, React.js, Node.js**, **Google Gemini**, and **ImageKit API**.  
Built and deployed a blog application with an admin panel using React.js, and deploy it online using **Vercel**.

This full stack project includes:
- AI-powered content generation using Google Gemini
- Image uploads with ImageKit
- Admin dashboard to manage blogs and comments
- Deployment via Vercel

---

## Tech Stack

- **Frontend**: React.js, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **AI Integration**: Google Gemini API  
- **Image Hosting**: ImageKit  
- **Deployment**: Vercel  

---

## Project Structure

```
AI-Powered-Blog-App/
├── client/         # React frontend
│   └── src/pages/  # Blog pages, Admin UI
├── server/         # Express backend
│   └── routes/     # API endpoints
├── .env            # Environment variables
└── README.md
```

---

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shivam847/AI-powered-blog-application.git
   cd AI-powered-blog-application
   ```

2. **Set up the backend**
   ```bash
   cd server
   npm install
   # Add .env file with your keys
   npm run dev
   ```

3. **Set up the frontend**
   ```bash
   cd ../client
   npm install
   npm run dev
   ```

4. Open your browser and go to:  
   [http://localhost:3000](http://localhost:3000)

---

## Live Demo

> 🔗 [Visit the Deployed App](https://ai-powered-blog-application.vercel.app)

---


## Environment Variables

Make sure to add the following in your `.env` files:

```env
# MongoDB
MONGODB_URI=your_mongo_connection_string

# Google Gemini
GEMINI_API_KEY=your_google_gemini_api_key

# ImageKit
IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=https://ik.imagekit.io/your_imagekit_id
```

---

## Acknowledgements

- [Google Gemini](https://ai.google.dev/)
- [ImageKit](https://imagekit.io/)
- [Vercel](https://vercel.com/)

---
