🐄 USDA Reports API
An Express.js wrapper for fetching real-time USDA Market Reports from the MARS API. This API securely accesses agricultural market data, such as milk powders, whey, and buttermilk, for global regions including Europe, Oceania, South America, and the U.S.

📌 Who Is This For?
Researchers and journalists tracking global agricultural trends

Data analysts building dashboards with up-to-date USDA data

Developers integrating agricultural reports into market tools

Students and educators needing real-world government API data

💡 Why Use This?
✅ Easily pull the latest USDA market reports
✅ Ready-to-deploy Node.js backend
✅ CORS enabled — ready for frontend integration
✅ Secure .env support for credentials
✅ Helpful logging and structure analysis for developers

📦 Example Response (Summarized)

{
  "success": true,
  "data": [
    {
      "id": 1034,
      "title": "Dry Whey - Europe",
      "date": "04/21/2025",
      "published": "04/24/2025 08:25:02",
      "status": "Final",
      "markets": "N/A",
      "office": "Madison"
    },
    {
      "id": 1044,
      "title": "Dry Buttermilk - East and Central U.S.",
      "date": "04/21/2025",
      "published": "04/24/2025 09:25:02",
      "status": "Final",
      "markets": "N/A",
      "office": "Madison"
    }
  ]
}
⚙️ Setup Instructions
1. Clone this repo

git clone https://github.com/yourusername/usda-reports-api.git
cd usda-reports-api
2. Install dependencies

npm install
3. Configure your .env
Create a .env file in the root:


API_KEY=your_usda_api_key
API_URL=https://marsapi.ams.usda.gov/services/v1.2/reports
PORT=5000
4. Start the server

npm start
The API will be available at:
http://localhost:5000/api/reports

📡 Endpoint
GET /api/reports
Fetches USDA market reports using your API key and returns structured JSON data.

🧱 Tech Stack
Express.js

CORS

dotenv

node-fetch

USDA MARS API

🛠 Development Tips
Console logging is added to show request flow and JSON structure

Stack traces are visible in development mode

Easy to extend with filters for product type or region

📜 License
MIT — Free to use, share, and build upon.# USDA_Reports
