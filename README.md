# Deploying a Django app to Google App Engine

Check out the [article](https://testdriven.io/blog/django-gae/) to learn how to deploy it.

## Want to use this project?

1. Fork/Clone

2. Create and activate a virtual environment:

    ```sh
    $ python3 -m venv venv && source venv/bin/activate
    ```

3. Install the requirements:

    ```sh
    (venv)$ pip install -r requirements.txt
    ```

4. Apply the migrations:

    ```sh
    (venv)$ python manage.py migrate
    ```

5. Run the server:

    ```sh
    (venv)$ python manage.py runserver
    ```
    
 6. Navigate to [http://localhost:8000/](http://localhost:8000/) in your favorite web browser.
