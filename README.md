# WeatherChecker ⛅

A sleek weather application built with Next.js 13, featuring real-time weather updates, forecasts, and beautiful weather animations.

## ✨ Features

- 🌡️ **Real-time Weather Data**
- 📅 **5-Day Weather Forecast**
- 🔍 **Smart City Search with Autocomplete**
- 🌓 **Dark/Light Theme**
- 📱 **Fully Responsive Design**
- 💫 **Dynamic Weather Animations**
- 🕒 **Recent Search History**

## 🛠️ Tech Stack

- **Frontend:** Next.js 13+
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion
- **State Management:** React Hooks
- **API:** OpenWeatherMap
- **Icons:** Lucide React
- **Components:** Radix UI

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm/pnpm/yarn
- OpenWeatherMap API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/weather-checker.git
   cd weather-checker
   ```
2. **Install dependencies**

    ```bash
    npm install
    # or
    pnpm install
    # or
    yarn install
    ```
3. **Set up environment variables**

    Create a .env file in the root directory:

    ENV

    ```console
    OPENWEATHER_API_KEY=your_api_key_here
    ```

4. **Start the development server**
    ```bash
    npm run dev
    # or
    pnpm dev
    # or
    yarn dev
    ```
5. **Open http://localhost:3000**

# 📱 Usage
- Enter a city name in the search bar
- Select from autocomplete suggestions
- View current weather and 5-day forecast
- Toggle theme using the theme switcher
- Access recent searches below the search bar
# 🌟 Key Features
Current Weather Display
Temperature
Weather condition with icon
Humidity percentage
Wind speed
Feels like temperature
Sunrise/Sunset times
5-Day Forecast
Daily temperature overview
Weather conditions
High/Low temperatures
Weather icons
UI Features
Dynamic weather backgrounds
Animated weather particles
Responsive design
Loading states
Error handling
Theme switching
🔧 API Integration
The app uses the OpenWeatherMap API for:

Current weather data
5-day weather forecast
City search suggestions
🎨 Styling
Tailwind CSS for responsive design
Custom animations with Framer Motion
Dynamic weather-based backgrounds
Dark/Light theme support
📝 Environment Variables
Required environment variables:

ENV

OPENWEATHER_API_KEY=your_api_key_here
🤝 Contributing
Fork the repository
Create your feature branch
BASH

git checkout -b feature/AmazingFeature
Commit your changes
BASH

git commit -m 'Add some AmazingFeature'
Push to the branch
BASH

git push origin feature/AmazingFeature
Open a Pull Request