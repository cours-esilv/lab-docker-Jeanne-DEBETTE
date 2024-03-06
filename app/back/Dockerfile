# Utiliser l'image de base Python
FROM python:3.8

# Définir le répertoire de travail dans le conteneur
WORKDIR /app

# Copier le contenu du répertoire actuel dans le répertoire de travail du conteneur
COPY . /app

# Installer les dépendances
RUN pip install --no-cache-dir -r requirements.txt

# Commande par défaut à exécuter lorsque le conteneur démarre
CMD ["python", "app.py"]
