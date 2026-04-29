---
marp: true
theme: default
_class: lead
_paginate: false
paginate: true
backgroundColor: #ffffff
style: |
  section {
    font-family: 'Ubuntu', sans-serif;
    font-size: 22px;
    color: #333333;
    line-height: 1.6;
    padding: 60px 80px;
  }

  /* Forcer la couleur Orange sur le titre et le sous-titre */
  h1 { 
    color: #E95420 !important; 
    font-size: 2.8em; 
    margin-top: 100px; 
    text-align: left; 
    font-weight: 700;
  }

  section.lead h1 {
    color: #E95420 !important;
  }

  h3 { 
    color: #E95420 !important; 
    text-align: left; 
    margin-top: 0; 
    font-weight: 600;
  }

  section.lead h3 {
    color: #E95420 !important;
  }

  section.lead {
    color: #E95420 !important;
  }

  h2 { 
    color: #77216F !important; 
    font-size: 2.2em; 
    border-bottom: 4px solid #E95420; 
    margin-bottom: 40px;
    font-weight: 700;
  }

  footer { 
    width: 100%; 
    text-align: right; 
    font-size: 14px; 
    color: #E95420; 
  }

  .logo-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    top: 35px;   
    left: 60px;
    right: 60px;
  }

  .logo-header img { 
    height: 80px; 
    object-fit: contain;
  }

  .ubuntu-logo {
    height: 90px !important;
  }

  .sommaire-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-top: 20px;
  }

  .sommaire-item {
    display: flex;
    align-items: center;
    background: #fdf2ee;
    border-radius: 12px;
    padding: 15px 20px;
    border-left: 6px solid #77216F;
    color: #77216F;
    font-weight: 600;
  }

  .sommaire-num {
    background: #E95420; 
    color: white; 
    width: 35px; 
    height: 35px;
    display: flex; 
    justify-content: center; 
    align-items: center;
    border-radius: 50%; 
    font-weight: bold; 
    margin-right: 15px; 
    flex-shrink: 0;
  }

  .dt-card {
    background: #ffffff;
    padding: 30px;
    border-radius: 12px;
    border-top: 6px solid #77216F;
    text-align: left;
    margin-top: 20px;
    width: 100%;
    box-shadow: 0 10px 20px rgba(0,0,0,0.05);
  }

  li {
    margin-bottom: 10px;
    list-style: none;
    position: relative;
    padding-left: 20px;
  }

  li::before {
    content: "•";
    color: #E95420;
    font-weight: bold;
    position: absolute;
    left: 0;
  }

  .highlight { color: #E95420 !important; font-weight: bold; }
  .purple { color: #77216F !important; font-weight: bold; }
---

<div class="logo-header">
  <img src="photos/ofppt-logo.png" alt="OFPPT">
  <img src="photos/logo-solicode.png" alt="Solicode">
</div>

# <span style="color: #E95420 !important;">**Projet : Lab Ubuntu**</span>
### <span style="color: #E95420 !important;">**Exploration et Configuration du Système d'Exploitation Open Source**</span>

**Réalisée par :** <span class="highlight">Haddad Yasmine</span>  
**Encadré par :** <span class="highlight">M. ESSARRAJ Fouad</span>  
**Filière :** <span class="purple">Développement Web et Mobile</span>

---

## Sommaire

<div class="sommaire-grid">
  <div class="sommaire-item"><div class="sommaire-num">1</div>Introduction & Contexte</div>
  <div class="sommaire-item"><div class="sommaire-num">2</div>Expérience Utilisateur</div>
  <div class="sommaire-item"><div class="sommaire-num">3</div>Gestion Logicielle</div>
  <div class="sommaire-item"><div class="sommaire-num">4</div>Analyse Critique</div>
  <div class="sommaire-item"><div class="sommaire-num">5</div>État d'avancement</div>
  <div class="sommaire-item"><div class="sommaire-num">6</div>Conclusion</div>
</div>

---

## 1. 🌟 Introduction & Contexte
### Qu'est-ce qu'Ubuntu ?
- **Origine** : Basé sur Debian, développé par **Canonical**.
- **LTS** : Support long terme (5 à 10 ans).
- **Philosophie** : Éthique Open Source et partage.

---

## 2. 📱 Expérience Utilisateur
### Interface GNOME
- **Modernité** : Une interface épurée.
- **Activités** : Gestion intelligente des fenêtres.

---

## 3. 📥 Gestion des Applications
### Écosystème Logiciel
- **App Center** : Boutique moderne.
- **Snap** : Format universel toujours à jour.

---

## 4. ⚖️ Analyse Critique

<div class="sommaire-grid">
  <div class="dt-card" style="border-top-color: #27ae60;">
    <h4 style="color: #27ae60;">✅ Atouts</h4>
    <ul>
      <li>Gratuité et Éthique</li>
      <li>Environnement Développeur</li>
    </ul>
  </div>
  <div class="dt-card" style="border-top-color: #e74c3c;">
    <h4 style="color: #e74c3c;">❌ Limites</h4>
    <ul>
      <li>Logiciels spécialisés (Adobe)</li>
      <li>Support Gaming en transition</li>
      <li>Courbe d'apprentissage CLI</li>
    </ul>
  </div>
</div>

---

## 5. 📊 État d'avancement du Projet

<div class="dt-card" style="border-top-color: #f39c12;">
  <h4 style="color: #77216F;">Rapport de session</h4>
  <ul>  
    <li><strong>✅ Terminées :</strong> Documentation, structure Marp, design thématique Ubuntu.</li>
    <li><strong>🚧 En cours :</strong> Version HTML interactive.</li>
    <li><strong>🚀 Suivant :</strong> Démonstrations terminal.</li>
  </ul>
</div>

---

## 6. 🏁 Conclusion
- Ubuntu est le standard de la **Liberté** et de la **Performance**.
- Un outil indispensable pour tout développeur moderne.

> "L'Open Source est une communauté mondiale."

---

<!-- _class: lead -->

# **Merci pour votre attention !**
