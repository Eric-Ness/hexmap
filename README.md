# Hexmap - Google Map Hexmap

This is a variation of joshcarr's Google Maps + D3 + hexbin project. 

https://gist.github.com/joshcarr/c0a405243d3051a9c986

![Hexmap](hexmap.png)

## Updates

There are a number of major/minor differences to Josh's excellent version. 

1. Hex grid extends out a bit
2. Zoom In/Zoom Out
3. stations.json simplification
4. Mouse over example
5. Secure API key handling

## Setup Instructions

### Google Maps API Setup

1. Create a Google Cloud project and enable the Maps JavaScript API
2. Create an API key with appropriate restrictions:
   - HTTP referrer restrictions (limit to your domains)
   - API restrictions (limit to Maps JavaScript API)

### Project Configuration

1. Copy `config.json.example` to `config.json`
2. Add your Google Maps API key to `config.json`
3. Make sure `config.json` is in your `.gitignore` to prevent exposing your API key

```json
{
  "googleMapsApiKey": "YOUR_API_KEY_HERE"
}
```

### Running the Project

Open `index.html` in your browser or serve it using a local web server.