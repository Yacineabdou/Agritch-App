# 📘 Agritech App — README

Ce dépôt contient trois pages principales de l’application **Agritech App**, développées en **HTML + TailwindCSS**, sans JavaScript.  
Le design est entièrement responsive pour **mobile**, **tablette** et **desktop**.

---

## 📂 Pages incluses

### 1️⃣ Home (`home.html`)
- Section de bienvenue  
- Image principale (carrousel statique)  
- Quelques articles récents mis en avant  
- Bouton "Commencer"  
- Footer avec liens sociaux  

---

### 2️⃣ Formation (`formation.html`)
- Header responsive  
- Présentation des contenus éducatifs  
- Section de description  
- Aperçu d’une formation  
- Bouton pour accéder aux cours ou documentations  

---

## 🎨 Technologies utilisées

- **HTML5**
- **TailwindCSS via CDN**
- **Font Awesome** (icônes)
- **Bootstrap Icons**

Aucun JavaScript n’est utilisé : tout est géré via HTML + Tailwind.

---

## 📱 Responsive Design (Tailwind)

Le projet utilise les breakpoints officiels Tailwind :

| Taille | Préfixe | À partir de |
|--------|---------|--------------|
| Mobile | *(none)* | — |
| Tablette | `sm:` | 640px |
| Moyen écran | `md:` | 768px |
| Laptop | `lg:` | 1024px |

Le design s’adapte automatiquement :

- Sidebar mobile avec `peer`  
- Layouts en grille (`grid`, `md:grid-cols-2`, etc.)  
- Images en `object-cover` pour garder les proportions  

---

## 📁 Structure du projet


---

## 🧩 Fonctionnement du menu mobile

Le sidebar mobile utilise le système Tailwind :

```html
<input type="checkbox" id="menu-toggle" class="peer hidden">
<nav class="peer-checked:translate-x-0 ...">
