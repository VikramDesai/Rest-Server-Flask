# Rest-Server-Flask

Our tasks resource will use HTTP methods as follows:

HTTP Method	URI	Action

GET	http://[hostname]/todo/api/v1.0/tasks	Retrieve list of tasks

GET	http://[hostname]/todo/api/v1.0/tasks/[task_id]	Retrieve a task

POST	http://[hostname]/todo/api/v1.0/tasks	Create a new task

PUT	http://[hostname]/todo/api/v1.0/tasks/[task_id]	Update an existing task

DELETE	http://[hostname]/todo/api/v1.0/tasks/[task_id]	Delete a task

We can define a task as having the following fields:

id: unique identifier for tasks. Numeric type.
title: short task description. String type.
description: long task description. Text type.
done: task completion state. Boolean type.
And with this we are basically done with the design part of our web service. All that is left is to implement it!
