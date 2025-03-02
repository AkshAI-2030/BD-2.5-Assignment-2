# Basic-Stocks Hub

## Overview
Basic-Stocks Hub provides stock listing, sorting, and filtering for NSE and BSE stocks across various sectors.

## Live Demo & Resources
<div>
    <a href="https://www.loom.com/share/77e78dbb5f2541bda0aeff1073948090">
      <p>Basic-Stocks-Hub-LiveDemo - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/77e78dbb5f2541bda0aeff1073948090">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/77e78dbb5f2541bda0aeff1073948090-f5ef58a7edf5f1c1-full-play.gif">
    </a>
  </div>
  
- **StackBlitz URL:** [StackBlitz Project](https://stackblitz.com/edit/stackblitz-starters-movkpq?file=index.js)
- **Deployed URL:** [Stocks-Hub API](https://basic-stocks-hub-akshay.vercel.app/)


## Setup & Deployment
1. Clone the repository:
   ```sh
   git clone https://github.com/AkshAI-2030/Basic-Stocks-Hub.git
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   node index.js
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
  
## Conclusion
This API enables efficient stock listing, sorting, and filtering, enhancing the Stocks Hub trading experience.

