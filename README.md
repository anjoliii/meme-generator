# Meme Generator

A fun and interactive React application that allows you to create custom memes by adding text to popular meme templates. The app fetches meme images from the Imgflip API and lets you personalize them with your own top and bottom text.

## Features

- 🎨 **Random Meme Selection**: Get a random meme template with the click of a button
- ✏️ **Custom Text**: Add your own top and bottom text to any meme
- 🔄 **Real-time Updates**: See your text changes instantly on the meme preview
- 📱 **Responsive Design**: Works on desktop and mobile devices
- 🚀 **Fast & Modern**: Built with React and Vite for optimal performance

## Technologies Used

- **React** - UI library for building the interface
- **Vite** - Fast build tool and development server
- **Imgflip API** - External API for fetching meme templates

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd MemeGenerator
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
# or
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal)

## Usage

1. **Enter Text**: Type your desired text in the "Top Text" and "Bottom Text" input fields
2. **Get New Meme**: Click the "Get a new meme image 🖼" button to load a random meme template
3. **Customize**: Edit the text fields to see your changes reflected in real-time on the meme preview

## Available Scripts

- `npm start` or `npm run dev` - Start the development server
- `npm run build` - Build the app for production
- `npm run preview` - Preview the production build locally

## Project Structure

```
MemeGenerator/
├── components/
│   ├── Header.jsx      # Header component with logo and title
│   └── Main.jsx        # Main component with meme generation logic
├── images/
│   └── troll-face.png  # Header logo image
├── App.jsx             # Root component
├── index.jsx           # Application entry point
├── index.html          # HTML template
├── index.css           # Global styles
├── vite.config.js      # Vite configuration
└── package.json        # Project dependencies and scripts
```

## API Information

This project uses the [Imgflip API](https://imgflip.com/api) to fetch meme templates. The API is called on component mount to retrieve a list of available memes, and a random meme is selected when the user clicks the "Get a new meme image" button.

## License

This project is open source and available for personal and educational use.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

---

Happy Coding! 🎉
