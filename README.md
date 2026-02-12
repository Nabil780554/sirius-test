# Construire l'image
docker build -t sirius-test .

# Lancer le conteneur
docker run -p 8501:8501 sirius-test
