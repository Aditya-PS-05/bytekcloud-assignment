# Authentication Module with NextJS and FastAPI

## Prerequisites
- Python 3.8+
- Node.js 14+
- MySQL Database

## Backend Setup
1. Create a virtual environment
2. Install dependencies:
```bash
pip install fastapi sqlalchemy pymysql python-jose[cryptography] passlib[bcrypt] python-multipart
```

## Frontend Setup
1. Install dependencies:
```bash
npm install next react react-dom @types/react antd next-auth axios
```

## Environment Variables
Create `.env` files for both backend and frontend with:
- `DATABASE_URL`
- `SECRET_KEY`

## Running the Application
- Backend: `uvicorn main:app --reload`
- Frontend: `npm run dev`