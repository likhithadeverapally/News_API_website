# News_API_website
Here’s a sample `README.md` file that provides comprehensive information for the project using the `index.html`, `style.css`, `script.js`, and `api-key.js` files.

---

# News App

This is a simple News App built using HTML, CSS, and JavaScript. The app fetches and displays the latest news articles from various categories using the NewsAPI. Users can select different categories to filter the news displayed.

## Features

- Fetches news articles from the [NewsAPI](https://newsapi.org/).
- Categories include General, Entertainment, Health, Science, Sports, and Technology.
- Responsive design, ensuring compatibility with various screen sizes.
- Articles include images, titles, descriptions, and a link to the full article.

## Project Structure

```
NewsApp/
│
├── index.html        # Main HTML file
├── style.css         # Stylesheet for the project
├── script.js         # JavaScript file handling the news fetching and UI updates
├── api-key.js        # JavaScript file containing the API key (kept separate for security)
└── newspaper.jpg     # (Optional) Fallback image used if the news article has no image
```

### `index.html`

This file contains the structure of the webpage, including the headings, containers for the news categories, and the section where news articles are displayed.

### `style.css`

This file handles the styling of the webpage, ensuring a modern and clean design. It includes styles for the layout, fonts, colors, and responsiveness.

### `script.js`

This is the core logic of the application, responsible for:

- Fetching news data from the NewsAPI.
- Dynamically generating the news cards.
- Handling category selection and updating the displayed news.

### `api-key.js`

This file contains your NewsAPI key. It’s separated from the main `script.js` to enhance security by isolating sensitive information.

```javascript
// api-key.js

// Enter your API key here
const apiKey = "YOUR_API_KEY";
```

> **Important:** Make sure to replace `"YOUR_API_KEY"` with your actual API key from NewsAPI.

## Setup

### Prerequisites

- A valid API key from [NewsAPI](https://newsapi.org/).
- Basic knowledge of HTML, CSS, and JavaScript.
- A code editor like Visual Studio Code.

### Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/NewsApp.git
   cd NewsApp
   ```

2. **Add your API key**:
   - Open the `api-key.js` file.
   - Replace the placeholder text with your API key:
     ```javascript
     const apiKey = "YOUR_API_KEY";
     ```

3. **Run the app**:
   - Open the `index.html` file in your browser.
   - Alternatively, you can serve the project using a local server (like `Live Server` in VSCode).

### API Key Limitations

The free version of NewsAPI allows up to 100 requests per day. If you exceed this limit, you will encounter an error, and the app will not display any news. Consider upgrading to a paid plan if you require more requests.

### Optional: Fallback Image

If a news article does not provide an image, the app will use a fallback image named `newspaper.jpg`. Ensure this file is present in the project directory. You can replace it with any image of your choice.

## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is open-source and available under the [MIT License](LICENSE).

---
