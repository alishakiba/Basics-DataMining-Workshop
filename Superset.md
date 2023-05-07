```python 
python3 -m venv venv
. venv/bin/activate
pip install apache-superset
pip install sqlparse=='0.4.3'
export FLASK_APP=superset
openssl rand -base64 42
export SUPERSET_CONFIG_PATH=/home/ali/Projects/Basics-DataMining-Workshop/superset_config.py
superset db upgrade
superset fab create-admin
superset load_examples
superset init
superset run -p 8088 --with-threads --reload --debugger
```
