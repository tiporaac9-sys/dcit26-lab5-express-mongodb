# DCIT 26 - Lab 5 Express & MongoDB

Open VSCode Terminal And Type:

```bash
mkdir lab5-student-api
cd lab5-student-api
npm init -y
npm install express mongoose dotenv
npm install --save-dev nodemon
npm pkg set scripts.dev="nodemon backend/server.js"
npm pkg set scripts.start="node backend/server.js"
```

Download and Install MongoDB Compass

Your .env file must contain:

```env
PORT=5001
MONGODB_URI=mongodb://127.0.0.1:27017/lab5_students
```

Start MongoDB

Go to your vscode terminal and type:

```bash
npm run dev
```

On your VSCode, install an extension called thunder client.

Your project structure must look like this:

```text
lab5-student-api/
├── backend/
│   ├── models/
│   │   └── Student.js
│   └── server.js
├── .env.example
├── .gitignore
├── package.json
└── README.md
```