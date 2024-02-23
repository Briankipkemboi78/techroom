# TechRoom Django App

TechRoom is a Django web application designed to facilitate discussions on technology topics within the realms of software and web development. Users can create rooms, engage in conversations, and post topics to foster a collaborative environment.

## Features

- **Room Creation:** Users can create dedicated rooms for specific technology topics.
- **Topic Posting:** Members can post and discuss various technology-related topics within each room.
- **User Authentication:** Secure user authentication system for personalized experiences.
- **Responsive Design:** User-friendly and responsive interface for seamless interactions.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Briankipkemboi78/techroom.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

4. Run the development server:

    ```bash
    python manage.py runserver
    ```

5. Access the application at `http://localhost:8000` in your web browser.

## Usage

1. Create a superuser account to access the Django admin panel:

    ```bash
    python manage.py createsuperuser
    ```

2. Log in to the admin panel at `http://localhost:8000/admin` to manage rooms, topics, and users.

3. Explore the TechRoom app by navigating to `http://localhost:8000`.

## Contributing

We welcome contributions! If you'd like to contribute to the development of TechRoom, please follow our [contribution guidelines](CONTRIBUTING.md).


