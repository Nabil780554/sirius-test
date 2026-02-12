# Cloner ton repo GitHub
git clone https://github.com/Nabil780554/sirius-test.git
cd sirius-test

# Construire l'image Docker
docker build -t sirius-test .

# Lancer le conteneur
docker run -d -p 8501:8501 sirius-test

# Après quelques secondes, un bouton "8501" apparaît en haut
# Clique dessus pour voir ton appli !


