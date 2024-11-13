**🦁 Wildlife Conservation Hub (WCH) 🌍**

Empowering Conservation Through Collaboration, Education, and Innovation

Table of Contents

Description

GitHub Repository

Features

Environment Setup and Installation

Designs

Deployment Plan

Technologies Used

Contributing

License



**Description**

Wildlife Conservation Hub (WCH) is a digital platform dedicated to fostering collaboration among conservationists, researchers, and the general public. The platform facilitates wildlife conservation efforts through education, real-time data sharing, and collaboration on conservation initiatives. The WCH platform aims to harness the power of technology to make conservation efforts more effective and transparent while engaging a broader audience.

**GitHub Repository**

You can find the complete source code and version history for the Wildlife Conservation Hub on GitHub:

https://github.com/emelyne1234/Wildlife_Conservation_Hub


**Features**

🌍 User Registration and Profile Creation: For conservationists, researchers, and the public.

📊 Real-Time Data and Analytics: Tools for tracking biodiversity and conservation metrics.

📚 Educational Resources: Tutorials, articles, and multimedia content for educating the public.

🤝 Collaboration Tools: Enables global cooperation on conservation initiatives.

📂 Biodiversity Database: Provides access to detailed species and habitat information.


**Environment Setup and Installation**

Follow these steps to set up the environment and run the project locally:

Clone the Repository:


git clone https://github.com/emelyne1234/Wildlife_Conservation_Hub

Navigate to the Project Directory:


cd wildlife-conservation-hub

Install the Dependencies: Ensure you have npm installed, then run:

npm install

Set Up Environment Variables:

Create a .env file in the root directory and include the necessary environment variables:


DATABASE_URL=

API_KEY=

JWT_SECRET=

Run the Application:


npm start

Your application will run on http://localhost:3000.

Testing: To run tests:

npm test

**Design**

Designed in Figma. Link to the Figma design:

https://www.figma.com/design/4lQCaXgk3ghbUVIrnbnS3K/wildlife-conservation-hub-design?node-id=0-1&t=NdfvUM38IrisNfeD-1


**Deployment Plan**

The Wildlife Conservation Hub is deployed using modern DevOps practices. Here's the detailed deployment strategy:

Deployment Platform

Vercel

Link to the deployment : https://wch-prep.vercel.app/


CI/CD Pipeline

GitHub Actions: CI/CD pipeline handles automated tests and deployment whenever changes are pushed to the main branch.

Steps to Deploy

Prepare Environment Variables: In the Render dashboard, set the following environment variables:

DATABASE_URL

API_KEY

JWT_SECRET

Push to GitHub: Once changes are pushed to the main branch, GitHub Actions will automatically trigger the CI/CD pipeline.

Auto-Deployment: Render will detect any changes pushed to GitHub and automatically deploy the updated version of the platform.

Production URL: The live site will be accessible.

**Technologies Used**

Frontend: React.js

Backend: Node.js with Express.js

Database: MongoDB

Data Visualization: D3.js and Chart.js

Authentication: JWT (JSON Web Token)

Deployment: Render, GitHub Actions (CI/CD)

**Contributing**

We welcome contributions from the community! Here’s how you can get started:

Fork the Repository.

Create a New Branch:

git checkout -b feature-branch

Make Your Changes and Commit:

git commit -m "Add new feature"

Push to Your Branch:

git push origin feature-branch

Create a Pull Request: Once your changes are ready, open a pull request on GitHub.

**License**

This project is licensed under the MIT License.
