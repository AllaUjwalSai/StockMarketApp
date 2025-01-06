# Stock Tracking Application (Kotlin)

## Overview

This Android application, developed in Kotlin using Android Studio, allows users to track and monitor stock prices in real time. The app provides essential tools for users to manage their investments and stay updated with market trends.

## Features

- **Real-Time Stock Data**: Fetch live stock prices and updates.
- **Watchlist**: Add favorite stocks to a personalized watchlist for quick access.
- **Stock Details**: View comprehensive details, including historical performance and key metrics.

## Requirements

### Software Requirements
- **Android Studio**: Arctic Fox or later
- **Kotlin**: 1.5+
- **Minimum Android SDK**: 21 (Lollipop)
- **Target Android SDK**: 33 (Tiramisu)
- **Third-Party Libraries**:
  - Retrofit: For API calls
  - Glide: For image loading
  - Room: For local database

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AllaUjwalSai/StockMarketApp.git
   cd stock-tracking-app
   ```

2. **Open in Android Studio**:
   - Launch Android Studio.
   - Select "Open an Existing Project" and navigate to the cloned repository.

3. **Set Up API Keys**:
   - Obtain an API key from a stock market data provider (e.g., Alpha Vantage, IEX Cloud).
   - Add the API key to `local.properties`:
     ```
     STOCK_API_KEY=your_api_key_here
     ```

4. **Build and Run**:
   - Sync Gradle files.
   - Connect an Android device or start an emulator.
   - Click on "Run" to launch the application.

## Usage

1. **Search Stocks**:
   - Use the search bar to find specific stocks.

2. **Add to Watchlist**:
   - Tap the "Add to Watchlist" button on stock detail pages.

## Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/stocktracking/   # Kotlin source files
│   │   ├── res/                             # UI resources (layouts, drawables, etc.)
│   │   ├── assets/                          # Static assets
│   │   └── AndroidManifest.xml              # App manifest
├── build.gradle                             # Project build file
├── local.properties                         # API key storage (not included in repo)
└── README.md                                # Project documentation
```

## Key Components

- **Retrofit**: Handles API calls to fetch stock data.
- **Room**: Manages local storage for offline data access.
- **Glide**: Ensures smooth image loading and caching.

## Contributing

1. **Fork the Repository**.
2. **Create a Feature Branch**:
   ```bash
   git checkout -b feature-name
   ```
3. **Commit Changes**:
   ```bash
   git commit -m 'Add feature'
   ```
4. **Push to the Branch**:
   ```bash
   git push origin feature-name
   ```
5. **Open a Pull Request**.



## Acknowledgments

- Stock market API providers Alpha Vantage.
- Open-source libraries (Retrofit, Glide, Room) for simplifying development.

## Contact

For questions or support, contact [Your Name] at [your-email@example.com].

