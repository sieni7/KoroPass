# 🔐 DANGÔRÔ-PASS

<p align="center">
  <strong>"Le vieux père veille sur tes accès."</strong><br>
  Générateur de mots de passe sécurisé — pensé pour un usage réel en Afrique.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Security-CSPRNG-green" />
  <img src="https://img.shields.io/badge/Privacy-Local--Only-blue" />
  <img src="https://img.shields.io/badge/Stack-VanillaJS%20%7C%20Bootstrap-orange" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey" />
</p>

---

## 📸 Aperçu

![DANGÔRÔ-PASS UI](./screenshot.png)

---

## 🌍 Vision

Kôrô-Pass est une application web de génération de mots de passe sécurisés, conçue avec une approche **Tech-Vernaculaire** :

> Adapter la cybersécurité aux usages réels, pas l’inverse.

Contrairement aux générateurs génériques, Kôrô-Pass intègre :
- des **cas d’usage locaux** (Mobile Money, PIN)
- une **lecture intelligente des erreurs humaines**
- une **expérience simple et immédiate**

---

## 🚀 Démo Live

👉 https://koro-pass.netlify.app *(à remplacer)*

---

## ⚙️ Fonctionnalités

### 🔐 Génération avancée
- Mot de passe complexe (configurable)
- Code MoMo (PIN sécurisé 6 chiffres)
- Passphrase Kôrô (mémorisable + robuste)

---

### 🧠 Analyse intelligente
- Calcul d’entropie → `E = L × log₂(R)`
- Détection de patterns faibles (`123`, `abc`, etc.)
- Blacklist locale (ex : `abidjan`, `admin`, `225`)
- Pénalisation automatique du score

---

### 🛡️ Sécurité intégrée
- Génération via `window.crypto.getRandomValues()` (CSPRNG)
- Exécution 100% côté client
- Aucun transfert réseau
- Aucune dépendance backend

---

### 🧾 Expérience utilisateur
- Historique local (5 derniers mots de passe)
- Copie instantanée dans le presse-papiers
- Mode sombre natif
- Feedback sécurité contextualisé (niveau “Kôrô”)

---

## 🌍 Différenciation

Kôrô-Pass introduit une approche **contextuelle africaine** :

- 🔸 Génération de PIN adaptés aux usages Mobile Money  
- 🔸 Détection de références locales dans les mots de passe  
- 🔸 Interface pensée pour un usage rapide, mobile-first  

---

## 🛡️ Modèle de sécurité

### ✔️ Protège contre :
- Mots de passe faibles ou prévisibles
- Mauvaises pratiques (patterns simples, réutilisation)

### ❌ Ne protège pas contre :
- Malware / keyloggers
- Phishing
- Compromission du navigateur

---

## 🧱 Stack Technique

- HTML5 / CSS3
- Vanilla JavaScript
- Bootstrap 5
- Web Crypto API

---

## ⚡ Installation

```bash
git clone https://github.com/your-username/koro-pass.git
cd koro-pass
open index.html
