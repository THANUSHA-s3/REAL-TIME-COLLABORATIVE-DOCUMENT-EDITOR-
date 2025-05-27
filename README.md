









# 🔧 Step-by-Step Setup

# STEP 1: Create Project Folder Structure

Copy
Edit

mkdir codtech-doc-editor

cd codtech-doc-editor

npx create-react-app client

mkdir server

# ⚙️ STEP 2: Backend Setup (Node.js + Express + Socket.IO + MongoDB)

# 1. Initialize Node.js Project

Copy
Edit

cd server

npm init -y

npm install express socket.io mongoose cors dotenv

# 2. Create server/index.js

The index.js file code has been in folder make sure the file

# 3. Create .env file

# 🖥️ STEP 3: Frontend Setup (React + Quill + Socket.IO)

# 1. Go to client/ folder

Copy
Edit

cd ../client

npm install react-quill socket.io-client

# 2. Replace App.js with:
the given file 

# 🌐 STEP 4: Run Everything

# 1. Start MongoDB:
Copy
Edit
mongod

# 2. Start Backend Server
Copy
Edit

cd server

node index.js

# 3. Start React Frontend
Copy
Edit

cd client

npm start

# Output
![Screenshot (6)](https://github.com/user-attachments/assets/842424f0-eed1-4bac-8da8-219a330d6a30)



