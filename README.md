# News Panda

News Panda is a responsive news web application built with React, HTML, Bootstrap, and CSS, that fetches real-time news using the News API. Users can browse through various categories of news including business, entertainment, health, science, sports, and technology, with the option to load more articles through infinite scrolling.

## Features

- **Real-time News**: Fetches top headlines from the [News API](https://newsapi.org/).
- **Category-based Browsing**: Filter news by categories such as General, Business, Entertainment, Health, Science, Sports, and Technology.
- **Infinite Scroll**: Loads more articles as the user scrolls down the page.
- **Responsive Design**: Built with Bootstrap and fully responsive across different devices.
- **Progress Bar**: Displays loading progress while fetching news.
- **Article Details**: Displays news article information such as title, description, author, source, and publication date.

## Built With

- **React**: Frontend JavaScript library used to build the user interface.
- **Bootstrap**: Used for responsive layouts and design elements.
- **CSS**: Custom styles for enhancing the user interface.
- **News API**: External API for fetching news articles.
- **React Infinite Scroll Component**: For implementing infinite scrolling in the app.
- **React Router**: For routing between different categories of news.
- **react-top-loading-bar**: For displaying a top progress bar while news is loading.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jai-singh5/News-Panda.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd news-panda
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```   

4. Get an API Key from [News API](https://newsapi.org/).  

5. **Create a .env file in the root directory and add your News API key**:
   ```bash
   REACT_APP_NEWS_API=<your_news_api_key>
   ``` 

6. **Run the app**:
    ```bash
   npm start
   ``` 

7. The app will run at http://localhost:3000/.


## Dependencies
The project uses the following dependencies:

- **react**: ^17.0.2
- **react-dom**: ^17.0.2
- **react-router-dom**: ^6.0.0
- **react-infinite-scroll-component**: ^6.1.0
- **react-top-loading-bar**: ^2.0.0
- **bootstrap**: ^5.1.3
- **prop-types**: ^15.7.2

## Contributing

- If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License

- This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [News API](https://newsapi.org/) for providing free access to news articles.
- [Bootstrap](https://getbootstrap.com/) for providing a responsive front-end framework.
- [React](https://react.dev/) for building a fast and interactive UI.