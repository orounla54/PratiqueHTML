# TRAFRULE-website

## 🚀 Guide de déploiement sécurisé

### Prérequis
- Serveur web (Apache/Nginx)
- Certificat SSL (recommandé)
- Domaine configuré

### Étapes de déploiement

1. **Upload des fichiers**
   - Transférer tous les fichiers vers le serveur
   - S'assurer que les permissions sont correctes (644 pour les fichiers, 755 pour les dossiers)

2. **Configuration du serveur**
   - Activer HTTPS (SSL/TLS)
   - Configurer les redirections HTTP vers HTTPS
   - Vérifier que le fichier `.htaccess` est bien pris en compte

3. **Vérifications post-déploiement**
   - Tester toutes les pages
   - Vérifier que les ressources locales se chargent
   - Contrôler les performances avec PageSpeed Insights

### Structure des fichiers
```
/
├── accueil/          # Page d'accueil
├── Histoire/         # Section histoire
├── Marques/          # Sections marques
├── Engagement/       # Section engagements
├── Potager/          # Section potager
├── images/           # Images du site
├── bootstrap/        # Framework Bootstrap (local)
├── js/              # jQuery (local)
├── swiper/          # Swiper (local)
├── @flaticon/       # Icônes
├── .htaccess        # Configuration Apache
├── robots.txt       # Instructions pour les robots
└── README.md        # Ce fichier
```

### Sécurité
- ✅ Ressources externes hébergées localement
- ✅ Headers de sécurité configurés
- ✅ Compression GZIP activée
- ✅ Cache optimisé
- ✅ Fichiers sensibles protégés

### Support
Pour toute question concernant le déploiement, contactez l'équipe technique.