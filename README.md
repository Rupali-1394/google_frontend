# 🚀 Google_Girls_hackathon_Frontend  

## 🌐 Live Demo  
🔗 **[Visit the Deployed Website](https://google-frontend-9d7i.onrender.com)**  

---

## 📌 Overview  
This is a frontend project built using **React** (bootstrapped with [Create React App](https://github.com/facebook/create-react-app)). It provides a smooth user experience with modern UI components.  

## 🌟 Features  
✅ **Responsive UI** – Works seamlessly on all devices  
✅ **Fast & Optimized** – Uses best practices for performance  
✅ **Modular Codebase** – Easy to understand and extend  

---

## 📂 Folder Structure  
```
google_frontend/
│── public/              # Static assets (index.html, icons, etc.)
│── src/                 # Main React source code
│   ├── components/      # Reusable components
│   ├── pages/           # Page-specific components
│   ├── assets/          # Images, icons, and styles
│   ├── App.js           # Main app entry
│   ├── index.js         # Renders the React app
│── .gitignore           # Files to ignore in Git
│── package.json         # Project dependencies & scripts
│── README.md            # You are here 😊
```

---

## ⚙️ Setup & Installation  
Follow these steps to set up the project on your local machine:  

### 🔹 Prerequisites  
Ensure you have **Node.js** and **npm** installed. Check by running:  
```sh
node -v
npm -v
```

### 🔹 Clone the Repository  
```sh
git clone https://github.com/your-username/google_frontend.git
cd google_frontend
```

### 🔹 Install Dependencies  
```sh
npm install
```

### 🔹 Start Development Server  
```sh
npm start
```
🔹 Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🚀 Deployment  
To build and deploy the project for production, use:  
```sh
npm run build
```
This creates an optimized `build/` folder, ready for hosting.  

### 🌍 Deploying to Render  
The website is hosted on **Render**. Follow these steps to deploy:  
1. Create a free account on **[Render](https://render.com/)**.  
2. Connect your **GitHub repository** in Render's dashboard.  
3. Select **Static Site** as your deployment method.  
4. Choose the **build command**:  
   ```sh
   npm install && npm run build
   ```
5. Set **Publish Directory** to:  
   ```
   build
   ```
6. Deploy and get your **Live URL**!  

🔗 Your deployed website: **[google-frontend-9d7i.onrender.com](https://google-frontend-9d7i.onrender.com)**  

---

## 🧪 Running Tests  
To test the application:  
```sh
npm test
```
See more details in the [testing documentation](https://facebook.github.io/create-react-app/docs/running-tests).

---

## 📜 License  
This project is open-source and available under the **MIT License**.  

---

## 🎯 Contributing  
Want to improve this project? 🤩 Feel free to open an issue or submit a pull request!  

🔹 **Fork the repository**  
🔹 **Create a new branch** (`feature-branch`)  
🔹 **Commit changes**  
🔹 **Push and create a pull request**  

---

## 💬 Contact  
📩 **Email:** mrupali1394@gmail.com  
🔗 **GitHub:** (https://github.com/Rupali-1394)

🎉 Happy Coding! 🚀✨  

**__Here i have merged the frontend with my backend___**

### **Google_Girl_Hackathon_Backend** 🚀  
This is the backend service for the **Google Hackathon Project**, providing APIs for authentication, data handling, and integration with the frontend.  

## **🛠 Tech Stack**  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT  
- **Other Dependencies:** dotenv, bcrypt, mongoose  

## **📂 Project Structure**  
```
/controllers   --> Handles business logic  
/models        --> Defines database schemas  
/routes        --> API endpoints  
/services      --> Utility functions  
node_modules   --> Installed dependencies  
.env           --> Environment variables  
.gitignore     --> Files to be ignored  
package.json   --> Project metadata & dependencies  
server.js      --> Entry point  
```

## **🚀 Installation & Setup**  
### **1️⃣ Clone the repository**  
```sh
git clone https://github.com/Rupali-1394/google_backend.git
cd google_backend
```

### **2️⃣ Install dependencies**  
```sh
npm install
```

### **3️⃣ Set up environment variables**  
Create a `.env` file in the root directory and add:  
```plaintext
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### **4️⃣ Start the server**  
```sh
npm start  

## **📌 API Endpoints**  
| Method | Endpoint       | Description          |
|--------|--------------|----------------------|
| POST   | /api/auth/register | Register a new user |
| POST   | /api/auth/login    | User login with JWT |
| GET    | /api/data          | Fetch data |

## **📞 Contact**  
For queries, feel free to reach out at **mrupali1394@gmail.com** or raise an issue in the repo.  
