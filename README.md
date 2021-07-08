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

3. Make some requests by going to `localhost:3000/a` and `localhost:3000/b`. Then go to Azure portal - your Application Insights resource page to review data.
