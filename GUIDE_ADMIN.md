# 📚 Guide Administrateur MalihaGroup

Ce guide complet vous explique comment gérer votre plateforme MalihaGroup.

---

## 🔐 Connexion à l'administration

L'interface d'administration est accessible à: **`votre-site.netlify.app/admin`**

1. Rendez-vous sur `/admin`
2. Connectez-vous avec vos identifiants Netlify Identity
3. Vous accédez au tableau de bord Décap CMS

---

## 📖 Modules Disponibles

### 📝 Blog
- Créer des articles avec titre, date, image, description
- Organiser avec catégories et tags
- Rédiger en Markdown

**Pour publier:**
1. Cliquez **Blog** > **New Blog**
2. Remplissez les champs
3. Cliquez **Publish**

### ⚽ Sport News
- Ajouter des scores, news, transferts
- Catégorisez: Scores, News, Transferts, Vidéos, Tendances

### 🎵 Musique
- Titre, Artiste, Fichier MP3
- Pochette (JPG/PNG 1400x1400px)
- Genre, Playlist, Durée

### 🖼️ Galerie
- Photos (JPG/PNG max 10MB)
- Vidéos (MP4/MOV max 100MB ou YouTube/Vimeo)

### 🎤 Événements
- Titre, Date, Lieu, Type
- Description détaillée
- Lien inscription & Capacité
- Organisateurs

### 💬 Témoignages
- Nom, Titre, Pays
- Photo profil
- Témoignage Markdown
- Rating (5 étoiles)

### ⚙️ Paramètres
- **Homepage:** Titre Hero, Sous-titre, CTA
- **SEO:** Meta Title, Description, Keywords, OG Image
- **Social:** Facebook, Twitter, Instagram, YouTube, TikTok, LinkedIn, Discord
- **Contact:** Email, Téléphone, Adresse

---

## 🔄 Workflow de Publication

```
1. Vous publiez depuis l'admin
   ↓
2. Décap CMS crée un commit GitHub
   ↓
3. GitHub Actions teste et valide
   ↓
4. Netlify rebuild automatiquement
   ↓
5. Site mis à jour en 30 secondes ✅
```

---

## 📞 Contact & Support

- 📧 Email: outboxprodfilm@gmail.com
- 📱 WhatsApp: +4915754169524
- 🌐 Facebook: facebook.com/malihaprod
- 🎥 YouTube: youtube.com/@malihaprod
- 📱 TikTok: tiktok.com/@malihaprod
- 📸 Instagram: instagram.com/@malihaprod

---

## 🚀 Commencer Maintenant

1. **Configurer Identity**
   - Netlify Dashboard > Settings > Identity > Enable

2. **Ajouter Secrets GitHub**
   - GitHub > Settings > Secrets
   - NETLIFY_AUTH_TOKEN
   - NETLIFY_SITE_ID

3. **Tester Localement**
   ```bash
   npm install
   npm run dev
   ```

4. **Publier du Contenu!**
   - Ouvrir `/admin`
   - Commencer à créer

---

**Réussir ensemble, d'Afrique en Europe** 🌍✨