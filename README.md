# Clone le dépôt GitHub (remplacez 'votre-utilisateur' par votre vrai identifiant GitHub)
git clone https://github.com/votre-utilisateur/securitech-site.git

# Entrez dans le dossier du dépôt cloné
cd securitech-site

# Copiez maintenant vos fichiers du site (index.html, style.css, script.js, images/, etc.) dans ce dossier
# Exemple : cp -r /chemin/vers/votre/site/* .

# Ajoute tous les fichiers au système de suivi de Git
git add .

# Crée un commit avec un message descriptif
git commit -m "Initial commit"

# Envoie les fichiers vers GitHub
git push origin main
