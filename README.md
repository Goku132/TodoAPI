# Todo List
Rest API  for todo list application.
Allowing user to create a todo list using python and flask.
Test run file with python setup.py.
Get web address on terminal.
Open new ternimal shell use curl to test.
Press ctrl c to finish.

Simple Get list:
curl http://localhost:5000/todos

Get single task: 
curl http://localhost:5000/todos/todo3

Delete task:
curl http://localhost:5000/todos/todo2 -X DELETE -v

Add new task:
curl http://localhost:5000/todos -d "task=something new" -X POST -v

Update task:
curl http://localhost:5000/todos/todo3 -d "task=something different" -X PUT -v


