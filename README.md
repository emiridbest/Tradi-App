# Tradi App

Tradi is an advanced confidential trading analysis dApp that leverages Secret Network's AI SDK to deliver secure, private market insights, technical analysis, and price predictions. The system features interactive charts, conversational AI, and predictive models to help traders make data-driven decisions through an intuitive Next.js frontend and powerful Flask backend with scikit-learn and TensorFlow integration.

## Project Structure

```
tradi/
├── frontend/                 # Next.js application
│   ├── app/                  # Pages and routes (home, analyze, predictions)
│   ├── components/           # UI components (charts, forms, prediction displays)
│   └── public/               # Static assets and images
├── backend/                  # Flask API server
│   ├── app/                  # Core application
│   │   ├── models/           # ML prediction models (sklearn, tensorflow. arima)
│   │   └── routes/           # API endpoints for data and predictions
│   └── utils/                # Trading strategies and data processing
└── README.md                 # Project documentation     
```

## Installation

1. Clone this repository and navigate into it:

```bash
git clone https://github.com/emiridbest/tradi-app
cd tradi-app
```
# Backend Setup
2. Install the required packages:

```bash
pip install -r requirements.txt  
```

3. Setup environment variables

```bash

# Create .env file and add these variables
SECRET_AI_API_KEY="your_secret_api_key_here"
```

4. Running the agent

```bash
python main.py 
```


# Frontend setup
5. Open new terminal in the root directory of the project and install dependencies

```bash
cd frontend
npm install
```

6. Setup environment variables
-  Create .env file
- Add NEXT_PUBLIC_BACKEND_URL=http://127.0.0.1:5000/ to .env file

7. Run react app

```bash
npm run dev

```

Visit `http://localhost:3000` in your web browser to access the application.

## Confidential Computing with Secret AI
Tradi-app leverages Secret Network's confidential computing capabilities through the Secret AI SDK. This integration ensures that:

- Trading analyses remain confidential and are not exposed to third parties
- User queries about trading strategies stay private
- AI model interactions happen within Secret Network's secure enclaves
- Trading decisions and patterns cannot be extracted or front-run by others
- By building on Secret AI, Tradi creates a truly private experience for traders, allowing them to leverage AI capabilities without compromising on security or exposing valuable trading insights.

## Next Steps:
- Enhance privacy-preserving features for portfolio analysis
- Implement confidential automated trading strategies
- Add cross-chain support for trading on multiple blockchains while maintaining privacy


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
# Screenshots


![chat_analysis](https://github.com/emiridbest/tradi/blob/main/assets/chat_analysis.png) 

![dashboard](https://github.com/emiridbest/tradi/blob/main/assets/dashboard.png)

![loading](https://github.com/emiridbest/tradi/blob/main/assets/loading.png)

![price_prediction](https://github.com/emiridbest/tradi/blob/main/assets/price_prediction.png) 

![real_time](https://github.com/emiridbest/tradi/blob/main/assets/real_time.png)
