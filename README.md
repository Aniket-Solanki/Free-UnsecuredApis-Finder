# Free Unsecured APIs Finder

A curated list of free, unsecured (no API key required) public APIs for development and testing.

## Features

- 🔓 **No Authentication Required** — All APIs work without API keys
- 📚 **Categorized** — Organized by category (Weather, News, Finance, etc.)
- 🔍 **Searchable** — Filter by category, method, or keyword
- 📝 **Documentation Links** — Direct links to official docs
- 🌐 **CORS Status** — Indicates if API supports browser requests

## Categories

- **Weather** — OpenWeatherMap, WeatherAPI, etc.
- **News** — NewsAPI, GNews, etc.
- **Finance** — Alpha Vantage, Finnhub, etc.
- **Entertainment** — TMDB, OMDB, etc.
- **Development** — GitHub, GitLab, etc.
- **Utilities** — IP lookup, QR codes, etc.

## Usage

```bash
# Clone the repository
git clone https://github.com/Aniket-Solanki/Free-UnsecuredApis-Finder.git
cd Free-UnsecuredApis-Finder

# Install dependencies
npm install

# Start development server
npm run dev
```

## API Data Format

Each API entry includes:

```json
{
  "name": "API Name",
  "description": "Brief description",
  "category": "Category",
  "baseUrl": "https://api.example.com",
  "endpoints": [
    {
      "path": "/endpoint",
      "method": "GET",
      "description": "What this endpoint does",
      "parameters": []
    }
  ],
  "cors": true,
  "auth": "none",
  "documentation": "https://docs.example.com"
}
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding new APIs.

## License

MIT License — see [LICENSE](LICENSE) for details.

## Author

**Aniket Solanki** — [@Aniket-Solanki](https://github.com/Aniket-Solanki)
