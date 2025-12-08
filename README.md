# Smart Recipe Finder — Interactive Feedback Loop

**Name:** Xinyu Tang  
**Andrew ID:** xinyutan

## Project Overview

This project is an intelligent recipe recommendation system that helps users find recipes based on available ingredients with interactive feedback mechanisms. The inspiration came from cooking videos on TikTok, where creators often share creative recipes based on limited ingredients.

## Open-Source Code Usage

**No open-source code was imported or used as a base.** This application was built entirely from scratch.

## APIs Used

This application uses the **Google Gemini API** (Generative AI) to:
- Generate recipe recommendations based on user-provided ingredients
- Apply dietary preferences and cuisine styles
- Process user feedback (banned ingredients, ingredient replacements)
- Refine recommendations based on user interactions

> **Security Note:** For security reasons, the API key is not included in the GitHub repository. See the "How to Run" section below for instructions on adding your own API key.

## Key Features Implemented

### Core Functionality
- **Ingredient-based recipe search**: Users can add multiple ingredients and receive AI-generated recipe recommendations
- **Advanced filters**: Cuisine style, prep time, and dietary preferences
- **Recipe details**: Complete ingredient lists and step-by-step instructions

### Interactive Feedback Loop
- **Ban ingredients**: Mark ingredients to avoid in future recommendations
- **Replace ingredients**: Specify ingredient substitutions globally
- **Refine recommendations**: Apply feedback to regenerate better-suited recipes
- **Feedback log**: Track all user preferences and modifications

### User Experience Features
- **Save recipes**: Bookmark favorite recipes for later reference
- **Persistent storage**: All preferences and saved recipes are stored locally
- **Responsive design**: Mobile-friendly interface using Tailwind CSS
- **Animated interactions**: Smooth transitions and hover effects

## Technical Implementation

- **Frontend**: Pure HTML, CSS (Tailwind CSS), and vanilla JavaScript
- **AI Integration**: Google Gemini API for natural language processing and recipe generation
- **Data Persistence**: Browser's localStorage for saving user preferences and recipes
- **Design**: Modern, responsive UI with gradient backgrounds and card-based layout

## How to Run

**Note:** This application requires a Google Gemini API key to function. For security reasons, the API key is not included in the repository.

### Option 1: Online Deployment
Live demo: **https://tangxinyuuu.github.io/cmu_05318_Project/**

To use the online version:
1. Open the browser's developer console (F12 or right-click → Inspect)
2. Go to the Console tab
3. Manually set your API key by running: `GEMINI_API_KEY = 'your-api-key-here'`

### Option 2: Local Setup (Recommended)
1. Clone or download this repository
2. Obtain a Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
3. Open `index.html` in a text editor
4. Find line 199 and replace `YOUR_API_KEY_HERE` with your actual API key
5. Save and open `index.html` in your web browser
6. Start exploring recipes!

## Project Structure

```
├── index.html              # Main application file (includes HTML, CSS, and JavaScript)
├── README.md              # This file
├── Gemini_api_key.txt     # Placeholder for API key (not uploaded to the github for security)
```
