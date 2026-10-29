# Portfolio – Julien Garcia

Développeur front-end **Vue.js / Nuxt** basé à Aix-en-Provence, en recherche d'un CDI.

**Site en ligne : https://julien-garcia1.github.io/**

## Le site

Un portfolio d'une page qui présente mes réalisations, avec des captures d'écran et une courte explication pour chacune :

- **Little Cigogne** : le front-end Vue 3 / Pinia / Nuxt d'un site e-commerce en six langues, et l'application mobile en Flutter.
- **Deux agents IA** : l'un traduit les textes du français vers l'allemand, le néerlandais, l'espagnol, l'italien et le portugais, puis les importe en base une fois validés par l'équipe ; l'autre traite les petits tickets du back-office jusqu'à la pull request, relue par un humain.
- **Avant Match en Folie** : mon application mobile full-stack (Flutter, Node.js / Express, MongoDB, back-office React), en phase de tests fermée.
- **PWA Alltricks / Décathlon** : scan produit et appel vendeur en magasin.

## Choix techniques

- **HTML et CSS, sans framework ni build** : une seule page statique, rapide à charger.
- **Responsive**, avec un thème clair et un thème sombre qui suivent les réglages du système.
- **Accessibilité** : navigation au clavier, lien d'évitement, textes alternatifs sur toutes les captures, agrandissement des images dans un élément `<dialog>` natif.
- **SEO** : balises meta, Open Graph et données structurées schema.org (`Person`).
- **Performance** : captures compressées (moins de 100 Ko chacune) et chargées à la demande (`loading="lazy"`).

## Structure

```
index.html   la page
assets/      photo, captures d'écran, CV en PDF, favicon
```

## Lancer en local

```bash
python3 -m http.server
```

Puis ouvrir http://localhost:8000

## Contact

- LinkedIn : [linkedin.com/in/julien-garcia1](https://www.linkedin.com/in/julien-garcia1/)
- Email : juliengarcia788@gmail.com