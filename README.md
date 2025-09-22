# BitBaby

A beautiful crypto tracker web application that displays real-time cryptocurrency prices and trading signals.

## Features

- 📊 Real-time cryptocurrency price tracking
- 🎨 Beautiful teal and gold themed UI
- 📈 7-day percentage change analysis
- 🚦 BUY/WAIT trading signals
- 🔄 Auto-refresh functionality
- 📱 Responsive design

## Supported Cryptocurrencies

- Bitcoin (BTC)
- Ethereum (ETH)
- Solana (SOL)
- Ripple (XRP)
- Hedera (HBAR)
- Cardano (ADA)
- Dogecoin (DOGE)

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/EmersonSpiff/bitbaby.git
   cd bitbaby
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and visit `http://localhost:3000`

## Railway Deployment

This application is configured for easy deployment on Railway.com:

1. **Connect Repository**: Link your GitHub repository to Railway
2. **Auto-Deploy**: Railway will automatically detect the Node.js application
3. **Environment**: The app will run on Railway's cloud infrastructure
4. **Custom Domain**: Optionally configure a custom domain

### Railway Configuration

- **Build Command**: `npm install`
- **Start Command**: `npm start`
- **Port**: Automatically configured by Railway
- **Health Check**: Available at `/health` endpoint

## Repository Information

- **GitHub URL**: https://github.com/EmersonSpiff/bitbaby.git
- **Local Path**: /Users/jeannettebezinque/Documents/CursorProjects/BitBaby

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Node.js, Express.js
- **Data Source**: CoinGecko API
- **Deployment**: Railway.com

## License

MIT License - feel free to use this project for your own crypto tracking needs!
