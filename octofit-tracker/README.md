# OctoFit Tracker - Modern Multi-Tier Application

A full-stack fitness tracking application built with React 19, Node.js/Express, TypeScript, and MongoDB.

## 📁 Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite application
│   ├── src/
│   ├── index.html
│   ├── package.json
│   ├── tsconfig.json
│   └── vite.config.ts
└── backend/           # Node.js + Express + TypeScript
    ├── src/
    ├── package.json
    ├── tsconfig.json
    └── .env.example
```

## 🚀 Technology Stack

### Frontend
- **React 19** - Latest React with modern features
- **Vite** - Next generation frontend tooling
- **TypeScript** - Type-safe JavaScript
- **Port**: 5173

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **TypeScript** - Type-safe backend
- **Mongoose** - MongoDB ODM
- **Port**: 8000

### Database
- **MongoDB** - NoSQL database
- **Port**: 27017

## 📦 Getting Started

### Prerequisites
- Node.js 18+
- MongoDB 5.0+
- npm or yarn

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

Frontend will be available at: `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

Backend will be available at: `http://localhost:8000`

### MongoDB Setup

Ensure MongoDB is running on `localhost:27017`:

```bash
mongod --dbpath /path/to/db
```

## 🔗 API Endpoints

- `GET /api/health` - Health check endpoint
- `GET /api/workouts` - Get all workouts (Coming soon)

## 📝 Development

### Frontend
```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run lint     # Run ESLint
npm run preview  # Preview production build
```

### Backend
```bash
npm run dev      # Start with ts-node
npm run build    # Compile TypeScript
npm start        # Run compiled JavaScript
npm run lint     # Run ESLint
```

## 🔧 Configuration

### Environment Variables (Backend)

Create `.env` file in backend directory:
```
PORT=8000
MONGODB_URI=mongodb://localhost:27017/octofit-tracker
NODE_ENV=development
```

## 📚 Next Steps

1. Define data models (User, Workout, Exercise)
2. Create API routes and controllers
3. Build frontend components
4. Implement authentication
5. Add data validation
6. Set up testing

---

**OctoFit Tracker** - Built with ❤️ using Copilot Agent Mode
