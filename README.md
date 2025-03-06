## Zepto Website UI Clone ##

# 🚀 Overview

This project is a Zepto Website UI Clone built using Next.js and Tailwind CSS. The entire UI is rendered dynamically using a JSON-based structure to ensure flexibility and maintainability.

# 🛠 Tech Stack

* Next.js – Framework for React applications

* Tailwind CSS – Utility-first CSS framework

* JSON – Used to dynamically drive UI components

* Vercel – Deployment platform

# 🎯 Features

* Dynamic JSON Rendering – The entire UI is built from JSON configuration.

* Fully Responsive Design – Mobile-first approach with smooth adaptability.

* Lazy Loading – Efficient loading of images for better performance.

* Reusable Components – Components for banners, categories, and product listings.

# 🔧 Setup Instructions

# 1️⃣ Clone the Repository

git clone https://github.com/sanjaykumar638/Zepto-Website-UI-clone

`cd zepto-ui-clone`

# 2️⃣ Install Dependencies

`yarn install`  # or `npm install`

# 3️⃣ Run the Development Server

`yarn dev`  # or `npm run dev`

Open http://localhost:3000 in your browser.

# 4️⃣ Build for Production

`yarn build  # or npm run build`

`yarn start  # or npm run start`

# 🚀 Deployment

This project is deployed on Vercel. You can deploy your own version using:

`vercel`

Alternatively, push to GitHub and connect with Vercel/Netlify for automatic deployments.

# 📝 JSON Configuration Example

# [
  {
    "type": "banner",
    "image": "/banner1.jpg",
    "title": "Super Fast Delivery",
    "subtitle": "Get groceries in 10 minutes",
    "cta_text": "Shop Now",
    "cta_link": "/shop"
  },
  {
    "type": "category",
    "categories": [
      { "name": "Vegetables", "image": "/veg.jpg", "link": "/category/vegetables" },
      { "name": "Fruits", "image": "/fruits.jpg", "link": "/category/fruits" }
    ]
  }
] ##


# 📬 Contact

For queries or suggestions, feel free to reach out via GitHub issues.

🔗 Live Demo: [Deployed Link Here]

🔗 GitHub Repository:https://github.com/sanjaykumar638/Zepto-Website-UI-clone