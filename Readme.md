# Todo App using flask
## Perform Operation like
1. Add Task
2. Delete Task
3. Update Task

# To run app
# Windows Preconditions
- install python from https://www.python.org/downloads/windows/
- Create virtual Environment
```
python -m venv myenv
```
```
source myenv/bin/activate  # For Linux/macOS
```
- or
```
myenv\Scripts\activate  # For Windows
```
- Install requirements
```
pip install -r requirements.txt
```
- Initialize the Database
```
python
```
```
from app import db, app

with app.app_context():
    db.create_all()
```

```
exit()
```

- run app
```
python app.py
```
