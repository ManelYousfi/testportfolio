# ------------------------------
# Configuration de base
# ------------------------------
title: "Manel Yousfi - Data Scientist"
email: "manelyousfipro@gmail.com"
description: "Data scientist passionnée par le développement et l'industrialisation de solutions IA end-to-end : NLP, computer vision, deep learning et MLOps."
baseurl: "" # laisse vide si le repo est sur https://username.github.io
url: "https://manelyousfi.github.io"

# ------------------------------
# Thème
# ------------------------------
theme: jekyll-theme-cayman

# ------------------------------
# Réseaux sociaux
# ------------------------------
social:
  github: "https://github.com/ManelYousfi"
  linkedin: "https://www.linkedin.com/in/manel-yousfi-/"


# ------------------------------
# Navigation
# ------------------------------
navbar:
  - title: "Accueil"
    url: "/"
  - title: "Projets"
    url: "/projects"
  - title: "CV"
    url: "/cv"
  - title: "Contact"
    url: "/contact"

# ------------------------------
# Paramètres des posts
# ------------------------------
paginate: 5
paginate_path: "/page:num/"

# ------------------------------
# Markdown & plugins
# ------------------------------
markdown: kramdown
kramdown:
  input: GFM
plugins:
  - jekyll-feed
  - jekyll-seo-tag

# ------------------------------
# Options supplémentaires
# ------------------------------
exclude:
  - Gemfile
  - Gemfile.lock
  - node_modules
  - vendor
