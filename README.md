 # Project Fitness Backend API

Backend API for Project Fitness mobile/web app.

## API Endpoints

### Auth
- POST `/api/auth/register` - Register new user
- POST `/api/auth/login` - Login user
- GET `/api/auth/me` - Get current user

### Users
- PUT `/api/users/profile` - Update profile
- GET `/api/users/stats` - Get user stats

### Workouts
- POST `/api/workouts` - Create workout
- GET `/api/workouts` - Get all workouts
- GET `/api/workouts/today` - Get today's workout
- PUT `/api/workouts/:id` - Update workout

### Nutrition
- POST `/api/nutrition` - Create meal plan
- GET `/api/nutrition/today` - Get today's meals
- GET `/api/nutrition/week` - Get weekly meals

### Progress
- GET `/api/progress/week` - Get weekly progress

### AI
- POST `/api/ai/recommendations` - Get AI advice
- POST `/api/ai/generate-workout` - Generate workout
- POST `/api/ai/generate-meal-plan` - Generate meal plan

## Deployment

1. Set environment variables
2. Run `npm install`
3. Run `npm start`
