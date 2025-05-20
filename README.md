# Reverse Timezone Lookup

![GitHub license](https://img.shields.io/github/license/stayradiated/reverse-timezone-lookup)

A simple, browser-based tool that finds timezones matching a specific target time. Instead of converting a time to different timezones, this app does the reverse: it shows you which timezones currently match your desired time.

## 🌐 [Live Demo](https://stayradiated.github.io/reverse-timezone-lookup)

![Screenshot of Timezone Finder app](https://raw.githubusercontent.com/stayradiated/reverse-timezone-lookup/main/screenshot.png)

## Features

- Find all timezones where the current time matches your target time
- Specify a threshold (in minutes) for flexibility
- Results are sorted by population to highlight the most relevant timezones
- View current time differences in minutes for each result
- Approximate population data for context
- Pure client-side application with no server dependencies
- Uses the browser's built-in Intl API for accurate timezone calculations

## Use Cases

- Finding suitable meeting times across international teams
- Identifying regions for real-time collaboration
- Planning global campaigns or events
- Optimizing customer support hours
- Finding optimal times for livestreams or broadcasts

## How to Use

1. Enter your target time in 24-hour format (e.g., `08:42`)
2. Set a threshold in minutes (e.g., `15` to find timezones within ±15 minutes of your target time)
3. Click "Find Timezones" to see matching results
4. Results are sorted by population size, showing the most populous matching timezones first

## Technical Details

- Fully client-side JavaScript with no dependencies
- Uses the Intl API's DateTimeFormat for accurate timezone calculations
- Compatible with all modern browsers
- Handles all IANA timezone identifiers
- Includes population estimates for context (as of 2025)

## Local Development

```bash
# Clone the repository
git clone https://github.com/stayradiated/reverse-timezone-lookup.git

# Navigate to the project directory
cd reverse-timezone-lookup

# Open the index.html file in your browser
open index.html
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built with vanilla JavaScript, HTML, and CSS
- Uses the browser's native Intl API for timezone handling
- Styled with a clean, responsive interface

---

Made with ❤️ by [stayradiated](https://github.com/stayradiated)
