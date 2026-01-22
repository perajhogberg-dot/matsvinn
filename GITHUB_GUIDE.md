# Guide: Publicera Matsvinn-appen på GitHub

Följ dessa steg för att publicera din app på GitHub och göra den tillgänglig för andra att testa och ge feedback.

## 📋 Förkunskaper

- Ett GitHub-konto (skapa gratis på [github.com](https://github.com))
- Git installerat på din dator ([ladda ner här](https://git-scm.com/downloads))

## 🚀 Steg 1: Skapa ett nytt repository på GitHub

1. Gå till [github.com](https://github.com) och logga in
2. Klicka på **"+"** uppe till höger och välj **"New repository"**
3. Fyll i:
   - **Repository name:** `matsvinn-mullsjo` (eller valfritt namn)
   - **Description:** "Webbapp för att minska matsvinn i Mullsjö - kopplar samman butiker och restauranger"
   - **Public** (så andra kan se och testa appen)
   - **BOCKA INTE I** "Add a README file" (vi har redan en)
4. Klicka på **"Create repository"**

## 💻 Steg 2: Ladda upp filerna från din dator

### Om du har filerna lokalt:

Öppna terminalen/kommandotolken i mappen där du har filerna och kör:

```bash
# Initiera git i din mapp
git init

# Lägg till alla filer
git add .

# Skapa din första commit
git commit -m "Första versionen av Matsvinn Mullsjö"

# Koppla till ditt GitHub repository (byt ut DITT-ANVÄNDARNAMN)
git remote add origin https://github.com/DITT-ANVÄNDARNAMN/matsvinn-mullsjo.git

# Pusha till GitHub
git branch -M main
git push -u origin main
```

### Om du bara har HTML-filen:

1. På GitHub repository-sidan, klicka på **"uploading an existing file"**
2. Dra och släpp dessa filer:
   - `index.html`
   - `README.md`
   - `.gitignore`
3. Scrolla ner och klicka **"Commit changes"**

## 🌐 Steg 3: Aktivera GitHub Pages

1. I ditt repository på GitHub, gå till **Settings** (överst till höger)
2. Klicka på **Pages** i menyn till vänster
3. Under **"Source"**, välj:
   - Branch: `main`
   - Folder: `/ (root)`
4. Klicka på **Save**
5. Vänta 1-2 minuter

Din app är nu live på: `https://DITT-ANVÄNDARNAMN.github.io/matsvinn-mullsjo/`

## 📢 Steg 4: Dela och få feedback

### Uppdatera README med rätt länk:

1. I ditt repository, klicka på `README.md`
2. Klicka på pennikonen (Edit)
3. Uppdatera länken under "Alternativ 1" till din faktiska GitHub Pages URL
4. Klicka **"Commit changes"**

### Dela projektet:

- Dela GitHub Pages-länken med:
  - Mullsjö kommun
  - Lokala butiker och restauranger
  - På sociala medier
  - I relevanta communities

- Be om feedback genom att:
  - Be folk skapa **Issues** på GitHub med förslag
  - Dela länken i lokala Facebook-grupper
  - Kontakta näringslivskontoret i Mullsjö

## 🔄 Steg 5: Uppdatera appen

När du vill göra ändringar:

```bash
# Gör dina ändringar i filerna lokalt
# Lägg till ändringarna
git add .

# Commit med ett beskrivande meddelande
git commit -m "Fixade timer-buggen och förbättrade designen"

# Pusha till GitHub
git push
```

GitHub Pages uppdateras automatiskt efter några minuter!

## 💡 Tips för att få bra feedback

1. **Tydlig dokumentation:** Din README är redan bra - se till att den är uppdaterad
2. **Issues-mallar:** Skapa mallar för buggrapporter och feature requests
3. **Demo-video:** Spela in en kort video som visar hur appen fungerar
4. **Kontaktinfo:** Lägg till hur folk kan nå dig i README
5. **Milstones:** Skapa en roadmap för framtida funktioner

## 🎯 Nästa steg efter feedback

- Analysera feedback och prioritera förbättringar
- Skapa Issues för varje förbättring/bugg
- Utveckla i separata branches för större features
- Testa noggrant innan du pushar till main
- Överväg att skapa "releases" för stora uppdateringar

## ❓ Felsökning

**Appen visas inte på GitHub Pages:**
- Vänta 5-10 minuter efter att du aktiverat Pages
- Kontrollera att filen heter exakt `index.html`
- Kolla att branch är satt till `main` i Pages-inställningarna

**Ändringar syns inte:**
- Töm din webbläsares cache (Ctrl+Shift+R / Cmd+Shift+R)
- Vänta några minuter för GitHub Pages att uppdatera

**Git-kommandon fungerar inte:**
- Kontrollera att du är i rätt mapp
- Se till att Git är installerat: `git --version`
- Dubbelkolla att du använt rätt repository-URL

---

**Lycka till med projektet! 🚀**
