# MK Quincaillerie — site statique

Site catalogue professionnel sans base de données.

## Lancer
Ouvrir `index.html` ou utiliser un serveur local :

```bash
python -m http.server 5500
```

Puis ouvrir http://localhost:5500

## À configurer avant publication
Dans `app.js` :

- `CONFIG.whatsappNumber` : numéro WhatsApp au format international sans + ni espaces.
- Ajouter l'adresse et les horaires officiels dans les sections concernées.
- Remplacer les avis placeholders par de vrais avis.
- Remplacer les images produits par les vraies photos si disponibles.

## Pages
- index.html
- products.html
- product.html?id=meuleuse-115
- categories.html
- services.html
- about.html
- contact.html
