Meal Nest 🍽️🌿
A recipe-sharing platform for discovering, saving, and planning meals with community features

Features
🍳 Recipe Sharing: Upload and browse recipes with images, ingredients, and instructions

🔍 Smart Search: Find recipes by name, ingredients, or dietary preferences

🛒 Shopping Lists: Automatically generate grocery lists from saved recipes

💬 Community Interaction: Rate, comment, and save favorite recipes

📱 Responsive Design: Works seamlessly on all devices

Tech Stack
Frontend: React.js, Tailwind CSS, Framer Motion

Backend: Node.js, Express, MongoDB (MERN stack)

Deployment: Vercel/Netlify (frontend), Render (backend)

Project Structure
src/
├── assets/
│   ├── images/ (placeholder images)
│   └── styles/
│       └── global.css
├── components/
│   ├── Auth/
│   │   ├── LoginForm.jsx
│   │   └── RegisterForm.jsx
│   ├── Recipe/
│   │   ├── RecipeCard.jsx
│   │   ├── RecipeForm.jsx
│   │   ├── RecipeDetail.jsx
│   │   ├── CommentSection.jsx
│   │   └── RatingSystem.jsx
│   ├── Search/
│   │   ├── SearchBar.jsx
│   │   └── FilterPanel.jsx
│   ├── ShoppingList/
│   │   └── ShoppingListGenerator.jsx
│   ├── Navigation/
│   │   ├── Navbar.jsx
│   │   └── Footer.jsx
│   └── UI/
│       ├── AnimatedRoute.jsx
│       ├── LoadingSpinner.jsx
│       └── Modal.jsx
├── pages/
│   ├── Home.jsx
│   ├── Login.jsx
│   ├── Register.jsx
│   ├── Recipes.jsx
│   ├── RecipeDetail.jsx
│   ├── AddRecipe.jsx
│   ├── Profile.jsx
│   ├── TopRecipes.jsx
│   └── ShoppingList.jsx
├── App.js
└── index.js
