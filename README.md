# Lamya Gandhi's Web Portfolio

Welcome to my web portfolio! This repository contains the source code for my personal portfolio website, showcasing my skills, projects, and experiences as a Computer Science Engineer.

## Live Link

Check out my portfolio live: [Lamya Gandhi's Portfolio](https://lamya-gandhi.onrender.com/)

## Description

This web portfolio is designed to present my background, skills, and projects in a visually engaging and interactive manner. The site includes multiple sections such as Home, About, Projects, and Contact. The Home page features 3D models and animations to create an immersive experience, while the Projects page showcases my key projects with detailed descriptions and live links.

## Tech Stack

- **Frontend**: React, Tailwind CSS, Three.js (react-three-fiber)
- **Backend**: EmailJS for handling contact form submissions
- **Libraries**: react-vertical-timeline-component, @react-three/drei

## Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

- Node.js (v14 or later)
- npm or yarn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/web-portfolio.git
    cd web-portfolio
    ```

2. Install dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```

3. Create a `.env` file in the root directory and add your EmailJS credentials:
    ```plaintext
    VITE_APP_EMAILJS_SERVICE_ID=your_service_id
    VITE_APP_EMAILJS_TEMPLATE_ID=your_template_id
    VITE_APP_EMAILJS_PUBLIC_KEY=your_public_key
    ```

4. Run the development server:
    ```sh
    npm start
    # or
    yarn start
    ```

5. Open your browser and navigate to `http://localhost:3000`.

### Deployment

To deploy the application, you can use any static site hosting service like Vercel, Netlify, or GitHub Pages. For example, to deploy with Vercel:

1. Install Vercel CLI:
    ```sh
    npm install -g vercel
    ```

2. Deploy the project:
    ```sh
    vercel
    ```

## Most Difficult Aspect

The most challenging part of this project was integrating 3D models and animations using Three.js (react-three-fiber). Ensuring that the models were responsive and interacted smoothly across different devices required significant effort. I overcame this challenge by extensively researching Three.js documentation and experimenting with various configurations to optimize performance and responsiveness.

## Feedback and Contact

I would love to hear your feedback on my portfolio. Feel free to reach out if you have any suggestions or questions. You can contact me through the contact form on my website or connect with me on [LinkedIn](https://www.linkedin.com/in/lamyagandhi10).

---

Thank you for visiting my portfolio!
