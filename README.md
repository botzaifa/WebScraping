# WebScraping Repository

Welcome to the WebScraping repository! Here, you'll find code related to web scraping using Flask, BeautifulSoup, and other tools. This project involves scraping data from Flipkart and storing it in MongoDB. The primary file for the project is `app.py`.

## Table of Contents

1. [About](#about)
2. [Setup](#setup)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

---

## About

This project demonstrates web scraping using Flask and BeautifulSoup to extract product reviews from Flipkart and store them in a MongoDB database. The project structure includes:

- `static/`: Static files like CSS and images.
- `templates/`: HTML templates used in the Flask app.
- `app.py`: The main Flask application script.
- `Procfile`: A file used for deploying the app on platforms like Heroku.
- `requirements.txt`: List of Python packages required for the project.

---

## Setup

To set up and run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/botzaifa/WebScraping.git
   cd WebScraping
   ```

2. Create a virtual environment (recommended):
   ```
   python3 -m venv venv
   source venv/bin/activate   # On Windows, use: venv\Scripts\activate
   ```

3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

4. Set up MongoDB:
   - Replace `<password>` in `app.py` with your MongoDB Atlas password.
   - Ensure you have a MongoDB Atlas cluster set up.

---

## Usage

1. Run the Flask application:
   ```
   python app.py
   ```

2. Open your web browser and go to `http://127.0.0.1:5000/` to use the web scraping tool.
   - Enter the product name in the search bar and submit.
   - The application will scrape reviews from Flipkart and store them in your MongoDB Atlas cluster.

---

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

---

## License

This project is open-source and licensed under the [GNU General Public License v3.0](LICENSE). You are welcome to use, modify, and distribute the code under the terms and conditions of this license. Please review the full license text [here](LICENSE) for more details.

Happy Scraping and Coding!

[Huzaifa Khan]
