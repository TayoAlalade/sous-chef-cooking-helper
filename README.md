# Sous Chef Cooking Helper

**Sous Chef Cooking Helper** is an AI-powered cooking assistant app designed to help users make the most of their available ingredients by recommending recipes and providing step-by-step instructions. Whether you're a beginner or an advanced cook, Sous Chef assists you in the kitchen by offering recipes, ingredient tracking, and cooking tips. The app also functions as a virtual cookbook, allowing users to explore a wide range of recipes and save their favorites.

---

## Features

- **Ingredient-Based Recipe Suggestions**: Input your available ingredients, including the food you have in your fridge, and Sous Chef will recommend recipes that can be made using them.
- **Step-by-Step Instructions**: Each recipe includes detailed, easy-to-follow instructions for both novice and experienced cooks.
- **Recipe Search and Filter**: Search for recipes by ingredients, cuisine type, or dietary preferences.
- **Virtual Cookbook**: Save your favorite recipes and explore hundreds of curated recipes.
- **User Accounts**: Users can create accounts to save recipes and track their cooking history.
- **Responsive Design**: Works across desktop and mobile devices for ease of use in the kitchen.

---

## Tech Stack

- **Backend**:  
  - Ruby on Rails: For creating the API and managing server-side logic.
  - PostgreSQL: Database for managing user data, recipes, and ingredients.
  - GraphQL: Used for efficient querying of the API.

- **Frontend**:  
  - React: For building an interactive and dynamic user interface.
  - Apollo Client: For managing GraphQL queries and state on the frontend.

- **Cloud & Hosting**:  
  - AWS EC2: For hosting the Rails backend.
  - AWS S3: For storing and serving user-uploaded recipe images and files.
  - Heroku: Used to host the React frontend.

---

## Installation

### Prerequisites
- Ruby (3.0 or higher)
- Rails (6.0 or higher)
- Node.js (14.x or higher)
- PostgreSQL
- Yarn or npm

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sous-chef-backend.git
   cd sous-chef-backend
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Set up the database:
   ```bash
   rails db:create db:migrate
   ```

4. Start the Rails server:
   ```bash
   rails server
   ```

### Frontend Setup
1. Clone the frontend repository:
   ```bash
   git clone https://github.com/yourusername/sous-chef-frontend.git
   cd sous-chef-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the React app:
   ```bash
   npm start
   ```

---

## Usage

1. Open the backend server (`localhost:3000`) and frontend server (`localhost:3001`).
2. Create an account or log in to start adding ingredients, including what you have in your fridge, and receive recipe suggestions.
3. Search for recipes by ingredients, dietary preferences, or cuisine.
4. Follow the step-by-step instructions to cook your chosen recipe.

---

## Deployment

This app is deployed using **Heroku** for the frontend and **AWS EC2** for the backend. Images and files are stored securely in **AWS S3**.

---

## License

This project is licensed under the MIT License.

---

## Contact

For any questions or feedback, please reach out at **tjalalade@gmail.com**.

---
