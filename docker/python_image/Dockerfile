FROM python:3.10

# Met à jour pip
RUN pip install --upgrade pip

# Installe les dépendances nécessaires
RUN pip install dash dash-bootstrap-components plotly mysql-connector-python pandas

# Lancement de ton application Python (par exemple un fichier dashboard.py)
CMD ["python", "dashboard.py"]
