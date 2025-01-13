# IMDb Scraper

This Python project is a web scraper for IMDb that extracts detailed information about movies, such as titles, ratings, and cast/crew details. It leverages the `requests` library for HTTP requests and `BeautifulSoup` for parsing HTML. The scraper can search for movies, retrieve information using IMDb IDs, and extract additional features like full credits.
---

## Features

This project provides the following functionalities:

1. **Search Movies by Title**:
   - Input a movie name to fetch its IMDb details.

2. **Retrieve Movie Details by IMDb ID**:
   - Fetch detailed information about a movie using its unique IMDb identifier (e.g., `tt1375666`).

3. **Extract Features**:
   - Retrieve metadata such as:
     - Title
     - IMDb Rating
     - Genre
     - Release Date
     - Director
     - Writer(s)
     - Cast

4. **Fetch Full Credits**:
   - Extract and list the cast and crew for a specific movie.

---

## Prerequisites

Before running the script, ensure the following libraries are installed:

- **requests**: For sending HTTP requests.
- **beautifulsoup4**: For parsing HTML content.
- **html5lib**: For better HTML parsing.

## Code Structure

- **`scrapping.py`**:
  - Main script containing the `IMDB` class and methods for scraping.

---

## How It Works

1. **Search for a Movie**:
   - The script constructs a search URL using IMDb’s base URL and the movie name.
   - Sends a request to IMDb, fetches the HTML, and parses it for relevant links and data.

2. **Retrieve Movie Details**:
   - Fetches movie-specific pages using IMDb IDs.
   - Extracts information like title, rating, genre, and more.

3. **Parse HTML**:
   - Uses `BeautifulSoup` to locate specific tags and classes that hold movie metadata.

---

## Disclaimer

This project is intended for **educational purposes only**. IMDb’s data is copyrighted, and scraping it without permission might violate their terms of service. Please use this tool responsibly.

---

## Contributions

Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request.

### How to Contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit changes: `git commit -m 'Add feature name'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per your requirements.

---
