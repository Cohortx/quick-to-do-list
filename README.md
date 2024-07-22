# quick-to-do-list

If you prefer to run it directly on your local machine, I suggest using
[venv](https://docs.python.org/3/library/venv.html).

    pip install -r requirements.txt
    FLASK_APP=todolist.py flask run

To add some 'play' data you can run

    pip install -r test-requirements.txt
    flask fill-db

Now you can browse the API:
<http://localhost:5000/api/users>

Pick a user, login as the user. Default password after `fill-db` is
*correcthorsebatterystaple*.
Click around, there is not too much, but I like the overview under:
<http://localhost:5000/todolists>
(You must be logged in to see it.)
