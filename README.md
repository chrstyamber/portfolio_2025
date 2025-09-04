# Portfolio Website

This is a personal portfolio website built using Vite+React, Tailwind CSS, and Framer Motion to showcase my skills, projects, and experience.

## Features
- **Responsive Design** – Works on all screen sizes.
- **Smooth Animations** – Powered by Framer Motion for interactive user experience.
- **Dark Mode Support** – Stylish UI with light and dark theme toggling.
- **Optimized Performance** – Efficient rendering and smooth navigation.
- **SEO Friendly** – Optimized for better search engine visibility.

## Tech Stack
- **Frontend:** React.js
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion

## Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/sathishk-dev/illustration-portfolio.git
   ```
2. Navigate to the project directory:
   ```sh
   cd illustration-portfolio
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```
   The app will be available at `http://localhost:3000/`.

## Demo
Check out the live demo of the portfolio website: [Live Demo](https://sk-illustration-portfolio.netlify.app/)

## Deployment
To deploy the portfolio website, you can use platforms like:
- **Vercel**
- **Netlify**
- **GitHub Pages** (with additional configurations)

## Install Node.js using Docker
To install node.jd, please use this instructions:
# Docker has specific installation instructions for each operating system.
# Please refer to the official documentation at https://docker.com/get-started/

# Pull the Node.js Docker image:
docker pull node:22-alpine

# Create a Node.js container and start a Shell session:
docker run -it --rm --entrypoint sh node:22-alpine

# Verify the Node.js version:
node -v # Should print "v22.19.0".

# Verify npm version:
npm -v # Should print "10.9.3".

# Run locally
docker run -it --rm -v ${PWD}:/app -w /app -p 5173:5173 node:22-alpine sh -c "npm install && npm run dev -- --host"
