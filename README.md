# Basic-Stocks Hub

## Overview
Basic-Stocks Hub provides stock listing, sorting, and filtering for NSE and BSE stocks across various sectors.

## Setup & Deployment
1. Clone the repository:
   ```sh
   git clone https://github.com/Basic-Stocks-Hub
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   npm start
   ```

## API Endpoints
### Stock Sorting
- **By Price:** `/stocks/sort/pricing` (Low to High / High to Low)
- **By Growth:** `/stocks/sort/growth` (High to Low / Low to High)

### Stock Filtering
- **By Exchange:** `/stocks/filter/exchange?exchange=NSE`
- **By Industry:** `/stocks/filter/industry?sector=Finance`

### Retrieve All Stocks
- **Endpoint:** `/stocks`
- Returns all available stocks.

## Integration with Advani Exchange UI
1. Deploy the backend API to Vercel.
2. Copy the deployment URL.
3. Open [Basic-Stocks Hub Frontend](https://bd2-stock-listing.vercel.app/).
4. Paste the backend URL in the **Server URL** field and save.

## Features
- Sort stocks by price and growth.
- Filter stocks by exchange and industry.
- Seamless integration with Basic-Stocks Hub’s frontend.

### Notes
- Ensure `cors` is imported before API endpoints:
  ```javascript
  let cors = require('cors');
  app.use(cors());
  ```

## Live Demo & Resources
- **Live Video Demo:** [Click Here](#)
- **StackBlitz URL:** [StackBlitz Project](https://stackblitz.com/edit/stackblitz-starters-grocl4?file=index.js)
- **Deployed URL:** [Advani Stocks API](https://basic-stocks-hub-akshay.vercel.app/)

## Conclusion
This API enables efficient stock listing, sorting, and filtering, enhancing the Stocks Hub trading experience.

