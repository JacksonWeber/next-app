# next-app

1. Update connection string in `server.js`:
   ```js
   appInsights.setup("<YOUR_CONNECTION_STRING>").start();
   ```

2. Run following command: 
   ```dash
   npm install
   npm run dev
   ```

3. Go to localhost:3000 and make some requests by switching route to /a and /b