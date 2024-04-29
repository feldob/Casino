# **Uppgift i Java: Använda inkapsling, polymorfism och arv**

## **Del 1: Repetition och Tillämpning (2 timmar)**

### **1.1 Läs om inkapsling, polymorfism och arv**
- **Uppgift:** Läs om sektionerna om inkapsling, polymorfism och arv på sidorna 11 och 12 i kursboken.
- **Syfte:** Förstå grundläggande objektorienterade principer i Java och hur de kan tillämpas i ditt projekt.

### **1.2 Tillämpa koncepten i ditt projekt**
- **Uppgift:** Identifiera och kommentera delar i din kod där inkapsling, polymorfism och arv används eller skulle kunna användas. Exempel på en kommentar kan vara:
  - `// Här används inkapsling genom att instansvariabeln 'x' görs privat och endast åtkomlig via getter- och setter-metoder.`
- **Syfte:** Praktisk tillämpning av teoretiska koncept för att förbättra kodens struktur och underhållbarhet.

## **Del 2: Hantering av undantag (Exception Handling) (2 timmar)**

### **2.1 Identifiera behovet av undantagshantering**
- **Uppgift:** Gå igenom din kod och identifiera en koddel där undantagshantering skulle vara till nytta (t.ex. vid filinläsning eller när data omvandlas).
  
### **2.2 Implementera undantagshantering**
- **Uppgift:** Skriv kod för att hantera möjliga fel som kan uppstå i den identifierade kodregionen med `try`, `catch` och `finally`.
  
### **2.3 Testa din felhantering**
- **Uppgift:** Testa din kod genom att medvetet orsaka fel och verifiera att ditt undantagshanteringssystem fungerar som det ska.
  - **Exempel:** I JUnit kan du skapa ett testfall som försöker öppna en fil som inte finns och sedan fånga det förväntade undantaget. Exempelkod:
    ```java
    @Test(expected = FileNotFoundException.class)
    public void testFileNotFound() throws FileNotFoundException {
        // Försök öppna en icke-existerande fil för att testa undantagshantering
        FileInputStream file = new FileInputStream("icke_existerande_fil.txt");
    }
    ```

- **Syfte:** Öka programmets robusthet och felhantering genom att introducera och testa undantagshantering.

## **Generell information**
- **Fokus för veckan:** Denna vecka är inriktad på att göra framsteg i projektet, med särskild uppmärksamhet på undantagshantering som vi nyligen introducerade och som är en viktig del av språket Java.
- **Onsdagens Q&A:** Onsdagens frågestund kommer främst att handla om undantagshantering. Förbered frågor och funderingar kring detta område.

Denna strukturerade uppgift syftar till att integrera och tillämpa centrala Java-koncept i ett praktiskt projekt, med målet att förbättra både förståelsen och kvaliteten på den kod som skrivs.
