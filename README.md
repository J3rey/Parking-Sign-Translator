# Parking Sign Translator

A web application that uses AI to translate and interpret parking signs, helping users understand parking restrictions and rules.

## Features

- Upload parking sign images for analysis
- Get text interpretation of parking rules and restrictions
- View parking locations on an interactive map
- Visualize parking data and statistics
- Mobile-friendly responsive design

## Tech Stack

### Frontend

- HTML/CSS/JavaScript
- Leaflet.js for interactive maps
- Chart.js for data visualization

### Backend

- Python/Flask web server
- Google Generative AI (Gemini) for image analysis
- MongoDB for data storage
- OpenCV and Pillow for image processing

## Installation

1. Clone the repository:

```bash
git clone https://github.com/J3rey/Parking-Sign-Translator.git
cd Parking-Sign-Translator
```

2. Install required Python packages:

```bash
pip install -r requirements.txt
```

3. Set up environment variables:
   - Create a `.env` file in the project root
   - Add your API keys and configuration:

```
GOOGLE_API_KEY=your_api_key
MONGODB_URI=your_mongodb_uri
```

4. Run the application:

```bash
python server.py
```

5. Open `http://localhost:5000` in your web browser

## Usage

1. Upload a parking sign image through the web interface
2. Wait for the AI analysis to complete
3. View the interpreted parking rules and restrictions
4. Use the interactive map to explore parking locations
5. Check statistics and visualizations in the dashboard

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
