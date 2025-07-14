# DeepSeek Clone  

A full-stack AI chatbot built using **Next.js** and **DeepSeek API**, featuring secure user authentication via **Clerk** and persistent chat storage using **MongoDB**. This project mimics ChatGPT-like interaction and is aimed at learning full-stack development, API integration, and user management.

---

## 🚀 Features  
- ✅ **AI Chat Interface**: Interact with the DeepSeek API  
- ✅ **User Authentication**: Implemented via Clerk (Google OAuth & Email)  
- ✅ **Persistent Chat History**: Stored in MongoDB  
- ✅ **Responsive Design**: Mobile-first, fully responsive  
- ✅ **Environment Variables**: API keys and secrets securely stored  
- ✅ **Next.js 14 App Router**: Modern file-based routing  

---

## 🛠️ Tech Stack  

- **Frontend**:  
  - React.js  
  - Next.js (App Router)  
  - Tailwind CSS  

- **Authentication**:  
  - [Clerk.dev]([https://clerk.com/])  

- **Database**:  
  - MongoDB (via Mongoose or native driver)  

- **AI API**:  
  - [DeepSeek API](https://deepseek.com)  

---

## 📦 Installation  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/Omkeswani27/deepseek-clone.git  
   cd deepseek-clone  

2. **Install Dependencies**  
   ```bash  
   npm install  
   
3. **Configure Environment Variables**  
   ```bash  
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
   CLERK_SECRET_KEY=your_CLERK_SECRET_KEY
   MONGODB_URI=your_MONGODB_URI
   SIGNING_SECRET=your_signing_secret
   DEEPSEEK_API_KEY=your_deepseek_api_key


4. **Run the Development Server**  
   ```bash  
   npm run dev
   
 ## Usage

 1. Sign in with your Google or email account (Clerk)
 2. Start chatting with the AI
 3. Your chats are saved and persist between sessions

 ## Completed Enhancements

 1. Integrated Clerk-based authentication.
 2. MongoDB-based chat history persistence.
 3. Clean and modern UI with responsive layout.
 4. Next.js App Router + Tailwind integration.
 5. Secure .env environment setup

 ## Future Enhancements

 1. Add support for image or voice input.
 2. Theme toggle (dark/light mode).
 3. Export chat to PDF.

 ## Contributing

 To run this blog locally:

 1. Clone the repository:
    git clone https://github.com/Omkeswani27/deepseek-clone.git
 2. Navigate to the project directory:
    ```bash
    cd deepseek-clone

 ## Contact

 Creator's Name - [Om Keswani](https://www.linkedin.com/in/om-keswani-4995262a5/?originalSubdomain=in) - omkeswani6@gmail.com

 Project Link: (https://github.com/Omkeswani27/deepseek-clone)
