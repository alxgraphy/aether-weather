# AETHER

A minimalist weather application with a brutalist black and white design aesthetic. Built with React and powered by the OpenWeatherMap API.

![AETHER Screenshot](https://via.placeholder.com/800x400/000000/FFFFFF?text=AETHER+Weather+App)

## Features

- **Real-time Weather Data** - Current conditions, hourly forecast (8 hours), and 5-day forecast
- **Auto-location Detection** - Automatically detects your location on first load
- **City Search** - Search for weather in any city worldwide
- **Temperature Units** - Toggle between Celsius and Fahrenheit
- **Light/Dark Mode** - Switch between black and white themes
- **Detailed Views** - Click any weather metric for expanded information
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile

## Tech Stack

- **React** - UI framework
- **Tailwind CSS** - Styling
- **Vite** - Build tool
- **OpenWeatherMap API** - Weather data
- **Lucide React** - Icons

## Installation

1. Clone the repository:
```bash
git clone https://github.com/alxgraphy/alx-weather.git
cd alx-weather
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```bash
VITE_API_KEY=your_openweathermap_api_key
```

4. Get your API key from [OpenWeatherMap](https://openweathermap.org/api)

5. Run the development server:
```bash
npm run dev
```

6. Open [http://localhost:5173](http://localhost:5173)

## Build for Production
```bash
npm run build
```

## Deployment

This project is optimized for deployment on [Vercel](https://vercel.com):

1. Push your code to GitHub
2. Import your repository on Vercel
3. Add `VITE_API_KEY` as an environment variable in Vercel settings
4. Deploy

## Design Philosophy

AETHER embraces a brutalist, minimalist design approach:
- High contrast black and white color scheme
- Clean geometric layouts
- Bold typography with wide letter spacing
- Smooth animations and transitions
- No unnecessary visual elements

## Weather Metrics

**Current Weather:**
- Temperature (with feels like, high, low)
- Weather conditions
- Humidity
- Wind speed and direction
- Atmospheric pressure
- Visibility
- Cloud coverage
- Sunrise/sunset times

**Forecasts:**
- Hourly forecast for the next 24 hours
- 5-day daily forecast
- Detailed view for each forecast day

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera


## Acknowledgments

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Inspired by Nothing Phone's design language
- Icons by [Lucide](https://lucide.dev/)

---

**Alexander Wondwossen** ([@alxgraphy](https://github.com/alxgraphy)) Made with ❤️ in Toronto, Canada 🇨🇦


## License

MIT License - feel free to use this project for personal or commercial purposes.