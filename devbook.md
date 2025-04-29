Je veux créer un site vitrine moderne pour présenter le projet Orus, une solution d’observation hyperspectrale issue du secteur spatial. Le site doit s’inspirer du design et de la structure du site suivant : https://virtual-reality.weblium.site/

🧪 Orus est un projet scientifique/technique ambitieux mêlant spatial, IA, capteurs optiques, traitement d’image et usages appliqués à l’environnement, l’agriculture ou la défense.

🛠️ Technologies imposées :

    Astro (structure du site)

    Tailwind CSS (design)

    AOS ou IntersectionObserver (animations au scroll)

    HTML statique optimisé (le site est vitrine, pas d'app dynamique)

🎯 Structure des sections attendue (toutes en composants Astro réutilisables) :

    Hero Section : grand titre "Orus – L’œil hyperspectral du futur", fond spatial ou satellite en orbite, bouton "Découvrir la technologie"

    À propos : bref résumé du projet, de son origine, et de l’équipe porteuse (CNES, industriels, labos)

    Technologie : 3 cartes ou blocs décrivant les composants (capteur hyperspectral, plateforme satellite, traitement IA embarqué)

    Applications : section alternée texte/image listant des cas concrets (surveillance forestière, analyse de sols, détection de polluants, etc.)

    Partenaires : logos de partenaires (publics/privés)

    Actualités (optionnel) : section avec 2-3 blocs type "blog"

    Contact : formulaire simple + coordonnées

    Footer : mentions, logo, réseaux sociaux, etc.

🎨 Style visuel :

    Thème spatial/scientifique : fond sombre ou dégradés "deep space", éléments violets/bleus/argentés

    Police moderne et technique (type Inter, IBM Plex Sans, Space Mono…)

    Icônes techniques (satellites, lentilles, spectres, IA)

    Design responsive

📁 Structure de fichiers souhaitée (dans src/) :

components/
  Header.astro
  HeroSection.astro
  AboutSection.astro
  TechSection.astro
  ApplicationsSection.astro
  PartnersSection.astro
  ContactSection.astro
  Footer.astro
layouts/
  MainLayout.astro
pages/
  index.astro
data/
  applications.json
  partners.json
styles/
  global.css

🚀 Lancement du projet :

    Initialiser un projet Astro avec npm create astro@latest

    Ajouter Tailwind CSS manuellement

    Intégrer AOS pour les animations au scroll

✅ Le code doit être propre, commenté, modulaire et prêt à être stylisé finement. Tu peux utiliser des données factices dans les fichiers JSON (applications.json, partners.json) pour alimenter dynamiquement les sections.