
# Order Tracker App

This is a React-based app for tracking online store orders with Gmail integration.

## 🌐 Deploy to Vercel

1. Upload this project to GitHub.
2. Go to https://vercel.com and connect your GitHub repo.
3. Set the following environment variables:

- `GOOGLE_CLIENT_ID` = your OAuth client ID
- `GOOGLE_CLIENT_SECRET` = your OAuth client secret
- `NEXTAUTH_URL` = https://your-vercel-project.vercel.app
- `NEXTAUTH_SECRET` = a random string (e.g. use openssl rand -base64 32)

4. Deploy!

## ✅ Features

- Google Sign-In (OAuth)
- Automatic order email parsing
- View orders with store, date, order number
- Click to reveal items and tracking numbers
- Delivery status with color indicators
