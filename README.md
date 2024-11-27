# 🛒 MERN Grocery Shop Project

## Installation

1. Change into the project directory:

   ```bash
   cd MERN-NM-MAIN
   ```

3. Install backend dependencies:

   ```bash
   npm install
   ```

4. Install frontend dependencies:

   ```bash
   cd frontend
   npm install
   ```

## Configuration

1. Create a `.env` file in the `root` directory with the following environment variables:

   ```env
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET_KEY = jwt_secret_key
   JWT_RESET_PASSWORD_SECRET_KEY = jwt_reset_password_secret_key
   COOKIE_EXPIRE = 5
   SMPT_MAIL = smpt_mail
   SMPT_PASSWORD = smpt_password
   CLOUD_NAME = your_cloudinary_cloud_name
   CLOUD_API_KEY =  your_cloudinary_api_key
   CLOUD_API_SECRET_KEY =  your_cloudinary_api_secret
   ```

## Usage

1. Start the backend:

   ```bash
   npm run dev
   ```

2. Start the frontend:

   ```bash
   cd frontend
   npm start
   ```

3. Access the application in your web browser at `http://localhost:3000`.

