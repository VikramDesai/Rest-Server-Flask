# Rest-Server-Flask

Our tasks resource will use HTTP methods as follows:

# HTTP Method	URI	Action

GET	http://[hostname]/todo/api/v1.0/tasks	Retrieve list of tasks

GET	http://[hostname]/todo/api/v1.0/tasks/[task_id]	Retrieve a task

POST	http://[hostname]/todo/api/v1.0/tasks	Create a new task

PUT	http://[hostname]/todo/api/v1.0/tasks/[task_id]	Update an existing task

DELETE	http://[hostname]/todo/api/v1.0/tasks/[task_id]	Delete a task

Disclaimer:
This project was designed in reference to the tutorial provided by https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask
