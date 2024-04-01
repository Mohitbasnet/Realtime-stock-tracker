
# Realtime stock tracker

In this project i have build realtime stock tracker app using Django channels, Celery, Redis, ASGI Server


## Installation

1. Clone the repository to your local machine:
     - git clone <repository_url>

2. Create a virtual environment and activate it:

    - pip install virtualenv
    - virtualenv envname
    - envname\scripts\activate # For Windows
    - source envname/bin/activate # For macOS/Linux

3. Navigate to the project directory:

    - cd Realtime-stock-tracker

4. Install project dependencies:

    - pip install -r requirements.txt

5. Apply database migrations:

    - python manage.py migrate

6. Run the development server:

   - python manage.py runserver

## Features

- You can select the stockes and you can see the stockes update like nepse chart


## Tech Stack

- Django Channels
- Websocket
- Redis
- Celery
- ASGI
- Daphne


## Contributing

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.


