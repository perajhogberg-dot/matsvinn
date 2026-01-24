# 🔄 Workflow: Hur vi jobbar med uppdateringar framöver

Detta dokument beskriver det enkla arbetssättet för när du vill göra ändringar i Matsvinn-appen.

---

## 📋 Grundprincipen

**Du beskriver → Jag fixar → Du uppdaterar GitHub**

Det är så enkelt! 🎯

---

## 🎨 Steg-för-steg: När du vill ha en ändring

### 1️⃣ **Du beskriver vad du vill ändra**

Skriv till mig i Claude och berätta vad du vill:

**Exempel:**
- "Jag vill ändra timern från 2 timmar till 3 timmar"
- "Kan vi lägga till en funktion för att ladda upp bilder på produkter?"
- "Designen på knappar - kan vi göra dem rundare?"
- "Jag vill ha en chattfunktion mellan butik och restaurang"
- "Kan restauranger se en karta över var butikerna ligger?"

Ju mer detaljer desto bättre, men jag hjälper till att förtydliga om något är oklart!

---

### 2️⃣ **Jag fixar ändringen**

Jag gör följande:

✅ Uppdaterar koden
✅ Testar att det fungerar
✅ Skapar en ny `index.html`
✅ Ger dig filen att ladda ner
✅ Skriver en kort beskrivning av vad jag ändrat

**Du får:**
- Den nya `index.html` filen
- En commit-meddelande att använda
- Instruktioner om något särskilt behöver testas

---

### 3️⃣ **Du uppdaterar på GitHub**

**Enklaste sättet (via webb):**

```
1. Gå till https://github.com/perajhogberg-dot/matsvinn
2. Klicka på index.html
3. Klicka på pennan (✏️)
4. Ta bort allt (Ctrl+A → Delete)
5. Klistra in den nya koden (Ctrl+V)
6. Commit changes med mitt meddelande
7. Vänta 2-3 min
8. Testa på https://perajhogberg-dot.github.io/matsvinn/
```

**Via terminalen (om du föredrar):**

```bash
# Ersätt index.html i din projektmapp
# Sen kör:
git add index.html
git commit -m "Commit-meddelande från Claude"
git push
```

---

### 4️⃣ **Du testar och ger feedback**

- Testa den nya funktionen
- Om det fungerar: perfekt! ✨
- Om något är konstigt: berätta för mig så fixar jag det

---

## 🚀 Olika typer av ändringar

### **Snabba ändringar** (5-10 minuter)
- Ändra färger
- Justera text
- Ändra timer-längd
- Fixa små buggar
- Justera layout

### **Medelstora ändringar** (20-30 minuter)
- Lägga till nya fält i formulär
- Ändra hur data visas
- Nya filter eller sortering
- Förbättra notifieringar
- Mobilanpassning

### **Stora ändringar** (1-2 timmar)
- Helt nya funktioner (t.ex. chat, bilder)
- Integration med API:er
- Avancerad statistik
- Nya användartyper
- E-postnotifieringar

---

## 💡 Tips för bra ändringsförfrågningar

### ✅ BRA exempel:

> "Kan timern vara 3 timmar istället för 2? Våra restauranger behöver mer tid att svara."

> "Jag vill att butiker ska kunna se vilken restaurang som accepterat erbjudandet direkt i listan, inte bara i 'Accepterade'-fliken."

> "Kan vi lägga till ett fält där butiker kan skriva 'Bäst före'-datum?"

### ⚠️ Mindre bra exempel:

> "Gör det bättre"
→ Vad specifikt vill du förbättra?

> "Kan du fixa designen?"
→ Vilken del av designen? Vad gillar du inte?

---

## 🗂️ Versionering (för större uppdateringar)

När vi gör stora ändringar kan vi skapa "versioner":

- **v1.0** - Nuvarande (grundfunktioner)
- **v1.1** - Små förbättringar
- **v2.0** - Stora nya funktioner

Du kan tagga dessa i GitHub med:
```bash
git tag v1.1
git push --tags
```

---

## 📝 Dokumentera ändringar

Jag kan hjälpa dig uppdatera README.md eller skapa en CHANGELOG.md som listar alla ändringar:

```markdown
# Ändringslogg

## Version 1.1 (2025-01-25)
- Ändrade timer från 2 till 3 timmar
- Fixade acceptera-knapp för restauranger
- Förbättrade mobilvisning

## Version 1.0 (2025-01-23)
- Första versionen
- Grundläggande funktioner
```

---

## 🎯 Prioritering av ändringar

Om du har många idéer kan vi prioritera:

1. **Kritiska buggar** - Fixas direkt
2. **Användarupplevelse** - Saker som gör appen lättare att använda
3. **Nya funktioner** - Coola tillägg som inte är nödvändiga
4. **Nice-to-have** - Saker som kan vänta

---

## 🤝 Exempel på komplett ändringscykel

**Du skriver:**
> "Hej! Jag vill att restauranger ska kunna se hur många kg mat de har räddat totalt. Typ en räknare på deras dashboard."

**Jag svarar:**
> "Bra idé! Jag lägger till en statistik-sektion på restaurangernas dashboard som visar:
> - Totalt antal accepterade erbjudanden
> - Total mängd (kg) mat räddad
> - Senaste accepterade erbjudandet
> 
> Ger mig 20 minuter!"

**Jag levererar:**
- Ny `index.html`
- Commit-meddelande: "Lägg till statistik för restauranger - total mängd mat räddad"
- Testinstruktioner: "Logga in som restaurang1 och acceptera några erbjudanden, sen se statistiken längst upp"

**Du uppdaterar:**
- Ersätter filen på GitHub
- Committar
- Testar

**Feedback:**
> "Perfekt! Kan vi lägga till samma för butiker också?"

**Nästa iteration startar!** 🔄

---

## 📞 Kontakt och frågor

När du vill ha ändringar:
1. Öppna en ny konversation med Claude (mig)
2. Beskriv ändringen
3. Jag fixar och levererar
4. Du uppdaterar
5. Klart! ✨

**Frågor om något är oklart?** Fråga bara - jag förklarar gärna mer detaljerat!

---

**Redo att börja göra appen ännu bättre?** 🚀

Säg bara vad du vill ändra så kör vi!
