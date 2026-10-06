# class-room-booking-system

## Vercel deployment

The app is Flask and can be deployed to Vercel with zero configuration. Set `CLASSROOM_SECRET_KEY` in Vercel Environment Variables. SQLite uses `/tmp` on Vercel; it is suitable for demos only because serverless storage is not persistent. Use a managed database for production data.
