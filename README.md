# Matsvinn Mullsjö 🥬

En lokal webbapp för att minska matsvinn genom att koppla samman livsmedelsbutiker med restaurangkök i Mullsjö.

## 🎯 Beskrivning

Matsvinn Mullsjö hjälper livsmedelsbutiker att erbjuda överskottsmat till lokala restauranger innan maten måste kasseras. Restauranger får notifieringar om nya erbjudanden och kan acceptera dem direkt - först till kvarn gäller!

## ✨ Funktioner

- **För butiker:**
  - Skapa erbjudanden med produkt, mängd, pris och beskrivning
  - Automatisk 2-timmars timer per erbjudande
  - Översikt över aktiva, accepterade och utgångna erbjudanden
  - Se kontaktuppgifter till restauranger som accepterat

- **För restauranger:**
  - Se alla tillgängliga erbjudanden i realtid
  - Acceptera erbjudanden med ett klick (först till kvarn)
  - Få kontaktuppgifter till butiken för upphämtning
  - Översikt över egna accepterade erbjudanden

- **Gemensamt:**
  - Enkel inloggning utan komplex säkerhet
  - Profilhantering med kontaktuppgifter
  - Persistent datalagring
  - Responsiv design för mobil och desktop
  - Visuella notifieringar

## 🚀 Kom igång

### Alternativ 1: Använd direkt via GitHub Pages

Besök: **[https://DITT-ANVÄNDARNAMN.github.io/matsvinn-mullsjo]()**

*(Uppdatera denna länk efter att du publicerat projektet)*

### Alternativ 2: Kör lokalt

1. Ladda ner projektet:
```bash
git clone https://github.com/DITT-ANVÄNDARNAMN/matsvinn-mullsjo.git
cd matsvinn-mullsjo
```

2. Öppna `index.html` i en webbläsare

Det är allt! Appen kräver ingen installation eller server.

## 👥 Demo-konton

### Butiker
- **ICA Mullsjö:** användarnamn: `ica`, lösenord: `ica123`
- **Coop Mullsjö:** användarnamn: `coop`, lösenord: `coop123`
- **Willys Mullsjö:** användarnamn: `willys`, lösenord: `willys123`

### Restauranger
- **Restaurang Sjöviken:** användarnamn: `restaurang1`, lösenord: `rest123`
- **Pizzeria Napoli:** användarnamn: `restaurang2`, lösenord: `rest123`
- **Kinarestaurangen:** användarnamn: `restaurang3`, lösenord: `rest123`
- **Café Bageriet:** användarnamn: `restaurang4`, lösenord: `rest123`
- **Mullsjö Hotell & Restaurang:** användarnamn: `restaurang5`, lösenord: `rest123`
- **Grillbaren:** användarnamn: `restaurang6`, lösenord: `rest123`
- **Thai Kitchen:** användarnamn: `restaurang7`, lösenord: `rest123`
- **Skolan Matsalar:** användarnamn: `restaurang8`, lösenord: `rest123`

## 🧪 Testa appen

1. Öppna två webbläsarfönster/flikar
2. Logga in som en butik (t.ex. `ica`) i det ena fönstret
3. Skapa ett erbjudande
4. Logga in som en restaurang (t.ex. `restaurang1`) i det andra fönstret
5. Se erbjudandet och acceptera det
6. Kontrollera att erbjudandet försvinner från andra restaurangers vy
7. Se kontaktuppgifterna som nu visas

## 🛠️ Teknisk information

- **Frontend:** Vanilla React (via CDN)
- **Styling:** Custom CSS med variabler
- **Lagring:** Browser Storage API (persistent mellan sessioner)
- **Ingen backend krävs** - perfekt för snabb prototyping och testning

## 📝 Användningsfall

**Exempel 1 - Färsk fisk:**
ICA har 2 kg färsk lax som går ut imorgon. De lägger upp ett erbjudande för 150 kr. Restaurang Sjöviken ser erbjudandet, accepterar det inom 10 minuter, och hämtar fisken samma eftermiddag.

**Exempel 2 - Grönsaker:**
Coop har ett överskott av 5 kg tomater. De skapar ett erbjudande för 50 kr. Ingen restaurang svarar inom 2 timmar, så erbjudandet tas automatiskt bort.

## 🔮 Framtida utveckling

- [ ] Push-notifieringar via service workers
- [ ] E-postnotifieringar
- [ ] Bilduppladdning för produkter
- [ ] Chattfunktion mellan butik och restaurang
- [ ] Statistik och rapporter
- [ ] Utökad geografisk täckning
- [ ] Integration med befintliga kassasystem

## 🤝 Bidra

Feedback och förslag är välkomna! Skapa gärna ett issue eller pull request.

### Hur du bidrar:
1. Forka projektet
2. Skapa en feature branch (`git checkout -b feature/AmazingFeature`)
3. Commita dina ändringar (`git commit -m 'Add some AmazingFeature'`)
4. Pusha till branchen (`git push origin feature/AmazingFeature`)
5. Öppna en Pull Request

## 📄 Licens

Detta projekt är öppen källkod och fritt att använda för icke-kommersiella ändamål.

## 📧 Kontakt

Har du frågor eller vill diskutera projektet? Skapa ett issue här på GitHub!

---

**Utvecklat för Mullsjö kommun - Tillsammans minskar vi matsvinnet! 🌱**
