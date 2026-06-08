# TimeTravel Agency — Webapp Interactive

> Webapp immersive pour une agence de voyage temporel fictive, créée avec IA générative.  
> Projet pédagogique M1/M2 — IA Créatives

---

## 🛠 Stack Technique

| Technologie | Usage |
|---|---|
| HTML5 / CSS3 / JS Vanilla | Structure, style, interactions |
| Google Fonts (Cinzel + Crimson Text + Inter) | Typographie premium |
| Claude API (Anthropic) | Chatbot IA + recommandations quiz |
| Images base64 embarquées | Visuels des destinations (zéro CDN) |
| Netlify / GitHub Pages | Déploiement gratuit |

**Aucun framework, aucune dépendance NPM, aucun build tool — 1 seul fichier `index.html`.**

---

## ✨ Features Implémentées

### Page d'accueil
- Hero animé avec portail temporel rotatif et ciel étoilé génératif
- Background image Belle Époque (Paris 1889) en overlay
- Navigation fixe responsive avec scroll fluide

### Galerie des destinations
- 3 cards interactives : Paris 1889 · Crétacé −65M · Florence 1504
- Visuels générés par IA (Session 1) intégrés en base64
- Modal détaillé avec description complète, points forts, tarifs
- Bouton de réservation direct depuis le modal

### Agent conversationnel — Chronos
- Chatbot flottant (bas droite) alimenté par Claude API
- Personnalité définie : professionnel, passionné d'histoire, chaleureux
- Historique de conversation conservé (8 derniers messages)
- Suggestions rapides prédéfinies

### Quiz IA personnalisé
- 4 questions avec scoring algorithmique multi-critères
- Appel à Claude API pour générer une recommandation poétique personnalisée
- Affichage de l'image de la destination recommandée

### Formulaire de réservation
- Sélection destination + date + nombre de voyageurs
- Validation des champs avec confirmation animée

---

## 🤖 IA Utilisées

| Usage | Outil |
|---|---|
| Génération du code webapp | Claude Sonnet (Anthropic) via Claude.ai |
| Chatbot conversationnel | Claude Sonnet API (`claude-sonnet-4-20250514`) |
| Recommandation quiz | Claude Sonnet API (`claude-sonnet-4-20250514`) |
| Visuels destinations | IA générative (Session 1) |

---

## 📝 Prompts Documentés

**Prompt principal (génération initiale) :**
> "Crée une webapp single-page pour TimeTravel Agency, agence de voyage temporel de luxe. Dark mode, accents dorés, typographie Cinzel. Sections : hero animé, about, 3 destinations (Paris 1889 / Crétacé −65M / Florence 1504), quiz IA, réservation, footer. Chatbot flottant connecté à Claude API. Quiz avec recommandation IA personnalisée."

**Prompt chatbot (system prompt) :**
> "Tu es Chronos, assistant virtuel de TimeTravel Agency. Professionnel, chaleureux, passionné d'histoire. Tu connais Paris 1889 (4890€), Crétacé −65M (8500€), Florence 1504 (5990€). Réponds en français, max 3-4 phrases."

**Prompt quiz IA :**
> "Génère une explication 2-3 phrases (style poétique) pourquoi cette destination correspond à ce voyageur selon son profil."

---

## 📄 Licence

Projet pédagogique — M1/M2 Digital & IA  
Visuels générés par IA à des fins éducatives uniquement.  
API Claude utilisée via Claude.ai (Anthropic).
