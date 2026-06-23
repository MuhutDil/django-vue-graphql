#     DjangoVueGraph
An application where users can write posts. Posts can have many tags. The back end is implemented on Django. The front end is implemented on a Vue front end, using GraphQL to communicate between them.

This is a learning project based on an article [RealPython](https://realpython.com/python-django-blog/).

#### Build and starting backend
    cd back_end/
    python -m pip install -r requirements.txt
    python manage.py migrate
    python manage.py runserver
#### Build and starting frontend
    cd front_end
    npm install
    npm run build
    npm run dev
