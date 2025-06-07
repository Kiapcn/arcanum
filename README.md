# Arcanum-Lotos

**Le créateur d'univers numériques intelligents**

---

## Présentation
Arcanum-Lotos est un site vitrine moderne pour un créateur indépendant de solutions digitales élégantes, mystérieuses et optimisées. Le storytelling s'articule autour de l'alchimie digitale : transformer les idées en expériences numériques performantes grâce à la synergie du code, du design, du SEO et de l'IA.

---

## Stack technique
- **Astro 5** : Framework principal, ultra-rapide, orienté contenu statique et dynamique.
- **Tailwind CSS** : Pour un design moderne, responsive et facilement personnalisable.
- **@astrojs/mdx** : Pour intégrer du contenu Markdown/MDX dans le site.
- **@astrojs/sitemap** : Génération automatique du sitemap pour le SEO.
- **@astrojs/vercel** : Déploiement optimisé sur Vercel (adapter officiel).
- **GSAP** : Animations fluides et élégantes.
- **Supabase JS** : (optionnel) Pour la gestion de données et d'API si besoin.

---

## Structure du projet

```
/
├── public/                # Images, favicon, ressources statiques
├── src/
│   ├── components/        # Composants réutilisables (Header, Footer, Sidebar)
│   ├── layouts/           # Layout principal du site
│   ├── pages/             # Pages du site (index, blog, services, contact, etc.)
│   └── lib/               # (optionnel) Fonctions utilitaires, ex: supabase.ts
├── astro.config.mjs       # Configuration Astro et intégrations
├── tailwind.config.mjs    # Configuration Tailwind CSS
├── package.json           # Dépendances et scripts
└── README.md              # Ce fichier
```

---

## Pages principales
- **Accueil** : Présentation, storytelling, call-to-action
- **Réalisations** : Portfolio de projets (à compléter)
- **Services** : Détail des offres (SEO, automatisation, IA, etc.)
- **Blog** : "Le Livre d'Arcanum" (SEO, guides, astuces)
- **Contact** : Formulaire ou lien de contact

---

## Commandes utiles

- `npm install` : Installer les dépendances
- `npm run dev` : Lancer le serveur de développement (http://localhost:4321)
- `npm run build` : Générer le site pour la production
- `npm run preview` : Prévisualiser le build localement

---

## Déploiement
Le projet est prêt pour un déploiement sur [Vercel](https://vercel.com) (configuration automatique via l'adapter officiel).

---

## Personnalisation
- **Couleurs** : Palette sombre, or doux, ivoire, lotus (voir `tailwind.config.mjs`)
- **Typographies** : Titres en Playfair Display (serif), textes en Inter (sans-serif)
- **Logo** : Lotus stylisé (à placer dans `/public`)

---

## Auteur
Kiapcn – Créateur indépendant dans le Var

---

## Licence
Projet open-source, libre de réutilisation et d'inspiration.
