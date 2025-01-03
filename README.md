## This is a dJango RESRTful API>

The API is rather basic.</br>
It uses the direct approach.</br>
1. Install dependencies.
```bash
pip install -r requirements.txt
```
2. Create a virtual environment for the project that you can call anything.
```bash
python3 -m venv env #linux
```
3. Activate the environment.
```bash
source env/bin/activate
```
4. Make migrations.
```bash
python3 manage.py makemigrations
```
```bash
python3 manage.py migrate
```
5. Run the server.
```bash
python3 migrate.py runserver
```
### That's all, you should have your API up and running.