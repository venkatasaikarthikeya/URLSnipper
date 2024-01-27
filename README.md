# URL-SNIPPER

URL-SNIPPER is a URL shortener project built with Python, Django, and MySQL.

## Features

- Shorten long URLs to a shorter, more manageable format.
- Redirect users to the original URL when they visit the shortened URL.
- Track the number of clicks and other analytics for each shortened URL.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/url-snipper.git
    ```

2. Create a virtual environment:

    ```bash
    python3 -m venv env
    ```

3. Activate the virtual environment:

    - For Windows:

      ```bash
      .\env\Scripts\activate
      ```

    - For macOS/Linux:

      ```bash
      source env/bin/activate
      ```

4. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

5. Set up the database:

    - Create a MySQL database and update the database settings in `url_snipper/settings.py`.

6. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

7. Start the development server:

    ```bash
    python manage.py runserver
    ```

8. Open your browser and visit `http://localhost:8000` to access the URL-SNIPPER application.

## Usage

- To shorten a URL, enter the long URL in the input field on the homepage and click the "Shorten" button.
- The shortened URL will be displayed on the page. Users can copy and share this URL.
- When a user visits the shortened URL, they will be redirected to the original URL.

##
