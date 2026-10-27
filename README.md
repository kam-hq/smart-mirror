# Smart Mirror

A Python-based smart mirror display application that shows weather conditions, news headlines, and internet connectivity status.

## Features

- **Weather Display** — Real-time weather with condition icons (sun, rain, clouds, snow, etc.)
- **News Feed** — Latest news headlines from configurable sources
- **Connectivity Monitor** — Visual internet connection status indicator
- **Custom Icons** — Weather condition icons for day and night variants

## Screenshots

| Weather Icons (Day) | Weather Icons (Night) |
|---|---|
| ☀️ Clear | 🌙 Clear Night |
| ⛅ Partly Cloudy | 🌥️ Cloudy Night |
| 🌧️ Rain | 🌧️ Rain Night |
| ❄️ Snow | ❄️ Snow Night |

## Tech Stack

- **Language:** Python
- **Libraries:** tkinter (GUI), requests (API calls), feedparser (RSS)
- **APIs:** OpenWeatherMap API

## Files

```
├── SMKAM.py          # Main application
├── os.py             # System utilities
├── 01d.png - 50n.png # Weather condition icons (day/night)
├── internet.png      # Connectivity indicator
└── Newspaper.png     # News section icon
```

## Getting Started

### Prerequisites

- Python 3.7+
- OpenWeatherMap API key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kam-hq/smart-mirror.git
   cd smart-mirror
   ```

2. Install dependencies:
   ```bash
   pip install requests feedparser
   ```

3. Add your API key in `SMKAM.py`

4. Run the application:
   ```bash
   python SMKAM.py
   ```

## Usage

Run the script and the mirror display will show:
- Current weather with appropriate condition icon
- Latest news headlines
- Internet connectivity status

Designed to run on a Raspberry Pi connected to a monitor behind a two-way mirror.

## License

MIT
