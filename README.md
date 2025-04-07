# nodejs-demo-app
Node.js Demo App with CI/CD Pipeline
This is a simple Node.js application deployed using Docker and automated with a CI/CD pipeline using GitHub Actions.

 Features
Express.js app that returns "Hello from Node.js App!"

Dockerized for containerized deployment

CI/CD pipeline with:

Node.js setup

Install & test steps

Docker image build & push to DockerHub

Project Structure
css
Copy
Edit
nodejs-demo-app/
├── app.js
├── package.json
├── Dockerfile
└── .github/
    └── workflows/
        └── main.yml
CI/CD Workflow
Triggered on push to the main branch

Builds and tests the app

Builds and pushes Docker image to DockerHub

 Run Locally
bash
Copy
Edit
npm install
node app.js
