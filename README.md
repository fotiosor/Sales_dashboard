🛠️ Sales Dashboard avec Streamlit
Ce projet est une application interactive de tableau de bord développée avec Streamlit, Pandas, et Plotly, destinée à visualiser et analyser les données de ventes. L'objectif principal est de fournir une interface conviviale permettant aux utilisateurs de filtrer, explorer, et interpréter les performances des ventes selon différents critères tels que les produits, les villes, et les objectifs de revenus.

🌟 Fonctionnalités principales
Tableau de bord interactif :

Affichage des indicateurs clés de performance (KPIs) : chiffre d'affaires, coût de production, et marge brute.
Visualisation graphique des quantités vendues, des revenus bruts par produit, et des objectifs atteints.
Comparaison des chiffres d'affaires produits et des objectifs.
Filtrage dynamique :

Filtre par ville et produit pour ajuster l'affichage des données.
Cartographie des ventes :

Carte interactive affichant le chiffre d'affaires par ville grâce à Folium.
Intégration responsive :

Application adaptée aux grands et petits écrans via l'interface utilisateur de Streamlit.
🛠️ Technologies utilisées
Python : Langage principal pour le développement.
Pandas : Gestion et manipulation des données Excel.
Plotly Express : Création de graphiques interactifs.
Streamlit : Développement de l'interface utilisateur.
Folium : Création de cartes interactives.
Streamlit-Folium : Intégration de cartes Folium dans Streamlit.
🚀 Comment utiliser
Clonez ce dépôt sur votre machine locale.

bash
Copier le code
git clone https://github.com/votre-utilisateur/sales-dashboard.git
Installez les dépendances nécessaires.

bash
Copier le code
pip install -r requirements.txt
Placez votre fichier de données DATA.xlsx dans le répertoire principal. Le fichier doit contenir deux feuilles :

Base_avec_formules : Contient les données de ventes détaillées.
Objectifs : Contient les objectifs de ventes par produit.
Lancez l'application Streamlit.

bash
Copier le code
streamlit run streamlit_app.py
Accédez au tableau de bord via votre navigateur à l'adresse fournie (par défaut : http://localhost:8501).

📊 Aperçu des données
Exemple de colonnes attendues dans Base_avec_formules :
Produits : Nom des produits.
Villes : Villes où les ventes ont eu lieu.
Quantité_vendue : Quantité totale vendue.
Chiffre_d'affaires : Chiffre d'affaires généré.
Cout_total : Coût total de production.
Latitude_Ville, Longitude_Ville : Coordonnées des villes pour la cartographie.
Exemple de colonnes attendues dans Objectifs :
Produits : Nom des produits.
CA objectifs : Chiffre d'affaires cible.
🎨 Résultat final
Un tableau de bord interactif qui facilite la prise de décision basée sur les données en visualisant les performances des ventes, en comparant les résultats aux objectifs, et en explorant les tendances géographiques.

👨‍💻 Auteur
Fotiosor
🔗 LinkedIn : https://www.linkedin.com/in/fabrice-fotio-bb43925a/
📧 Contact : fotiosor@gmail.com
