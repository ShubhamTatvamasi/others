# Bring venv to an existing non-venv project in PyCharm
1. Open project in PyCharm
1. Go to settings / preferences
1. Project: <proj-name> -> Project Interpreter -> Top right click the "settings" button -> Select "Show All"
1. From the bottom of "Project Interpreters" window, click the '+' icon 
1. Select "New Environment", ensure location is <your-proj-directory/venv>
1. Select the right base interpreter
1. Click "OK"
1. Open "Terminal" within PyCharm
1. source venv/bin/activate
1. pip install -r requirements.txt
