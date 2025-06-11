# TikTok Script Generator

A responsive web application for generating TikTok video scripts using the Google Gemini API. The app is built with HTML, Tailwind CSS, and vanilla JavaScript.

## Features
- **Google Gemini API Integration**: Generate scripts using your own API key and model.
- **Model Selection**: Choose from pre-defined models or input and save a custom model.
- **Video Idea Input**: Enter your TikTok video idea for script generation.
- **Duration Selection**: Specify the desired video duration (in seconds) for the script.
- **Brand Storytelling**: The AI is prompted to generate scripts with a storytelling approach, not hard sell.
- **Markdown Table Output**: Scripts are displayed in a table with columns: Timestamp, Scene, Voiceover, and On-Screen Text.
- **Copy & Export**: Copy the output or export it to XLS format.
- **Clear Output**: Easily clear the generated script.
- **Responsive Design**: Works well on all screen sizes.
- **Accessibility**: Improved for keyboard and screen reader users.

## Setup
1. Clone or download this repository.
2. Open `index.html` in your web browser.
3. No build step or server is required; everything runs in the browser.

## Usage
1. **Enter your Google Gemini API key.**
2. **Select a model** (or enter a custom model and save it).
3. **Type your TikTok video idea.**
4. **Set the desired video duration (in seconds).**
5. Click **Generate Script**.
6. The output table will show: Timestamp, Scene, Voiceover, and On-Screen Text.
7. Use the **Copy**, **Export to XLS**, or **Clear Output** buttons as needed.

## Customization
- You can adjust the prompt in the JavaScript to change the style or language of the generated scripts.
- Tailwind CSS is loaded via CDN; you can further style the app as desired.

## Security Notice
- Your API key and custom model are stored in your browser's session storage and are never sent to any server except Google's Gemini API.

## License
MIT 