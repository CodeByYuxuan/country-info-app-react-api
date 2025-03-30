# 🌍 Country Info App

A dynamic and responsive React app that helps users search for and explore detailed information about countries around the world, including real-time weather updates for each capital city.

## ✨ Features

- 🔍 **Live Search**: Filter countries by name with real-time feedback.
- 🏳️ **Country Details**: View each country’s flag, capital, population, languages, and more.
- ☀️ **Weather Updates**: Get current weather info for the capital city using OpenWeatherMap API.

## 🛠️ Tech Stack

- **Frontend**: React
- **HTTP Client**: Axios
- **Styling**: CSS
- **APIs**:
  - [REST Countries](https://restcountries.com/) API for country data
  - [OpenWeatherMap](https://openweathermap.org/api) for weather data

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone git@github.com:CodeByYuxuan/country-info-app-react-api.git
cd country-info-app-react-api
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env` file in the root directory with the following:

```env
REACT_APP_WEATHER_API_KEY=your_openweathermap_api_key
```

### 4. Start the Development Server

```bash
npm start
```

Visit `http://localhost:3000` to use the app.

## 📁 Project Structure

```
country-info-app-react-api/
├── public/
├── src/
│   ├── components/       # Reusable UI components
│   ├── services/         # API call utilities
│   ├── App.js            # Root component
│   ├── index.js          # App entry point
│   └── ...
├── .env                 # API keys
├── package.json
└── README.md
```

## 🙌 Contributing

Got ideas or improvements? Contributions are welcome! Feel free to fork this repo and open a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Made with ❤️ using React and public APIs.
