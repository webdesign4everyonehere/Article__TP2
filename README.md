# Article__TP2
TP2 – Rédaction Scientifique pour Ingénieur : Article réalisé par Sara AIT TALEB et Kaoutar ATOUF

📦 Package LaTeX mystyle — README

Ce dépôt contient deux versions du package mystyle, utilisé pour styliser des articles scientifiques en LaTeX.

🎨 Version 1 — Version simple

La première version propose un style fixe : titres colorés, en-têtes personnalisés et abstract décoré.
Elle fonctionne avec des options très limitées, essentiellement le choix d’une couleur.
C’est une version efficace mais peu flexible.

🔧 Version 2 — Version améliorée (key=value)

La seconde version introduit un système moderne d’options key=value (titlecolor=…, showline=…, widthabstract=…).
Elle permet de personnaliser l’apparence sans modifier le fichier .sty : couleur des titres, présence ou non de la ligne décorative, largeur de l’abstract, etc.
Le code est mieux structuré, plus propre et beaucoup plus modulable.

🧪 Exemple d’utilisation
\usepackage[titlecolor=green,showline=false,widthabstract=0.7]{mystyle}

🌟 Résumé

La version 1 offre un style élégant mais fixe.
La version 2 apporte une flexibilité professionnelle, une configuration précise et une utilisation plus moderne du package.
