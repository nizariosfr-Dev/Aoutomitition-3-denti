Site statique minimal pour le Cabinet Dentaire du Dr. Anouar Sekkak

Fichiers créés :
- index.html : page d'accueil
- about.html : présentation du cabinet
- services.html : liste des services
- rdv.html : prise de rendez-vous / informations pratiques
- contact.html : formulaire de contact & urgences
- assets/css/styles.css : styles minimaux

Comment utiliser
1. Ouvrez le dossier dans votre navigateur (double‑clic sur `index.html`) ou servez-le via un petit serveur local.

Exemple pour lancer un serveur local (PowerShell) :

```powershell
# depuis le dossier du site
python -m http.server 8000
# puis ouvrez http://localhost:8000
```

Remarques & prochaines étapes
- Remplacez les images placeholders dans `assets/img/` (créées comme références) par des photos professionnelles.
- Renseignez l'URL de la plateforme de prise de RDV et l'email du cabinet dans les pages concernées.
- Pour la mise en production, ajouter SSL, optimiser images et configurer la fiche Google Business.

Si vous voulez, je peux :
- Ajouter les images et optimiser les formats (webp),
- Générer des pages détaillées pour chaque service,
- Préparer un petit script de déploiement vers un hébergement (Netlify, Vercel, ou hébergeur local).