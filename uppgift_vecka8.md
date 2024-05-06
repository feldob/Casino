# **Fördjupningsuppgift i Java: Avancerade koncept och teststrategier**

## **Del 1: Enhets- och användningsfallstestning (2 timmar)**

### **1.1 Förstå skillnaden mellan enhetstestning och användningsfallstestning**
- **Uppgift:** Läs om skillnaderna mellan enhetstestning och användningsfallstestning på [Effective Software Testing](https://www.effective-software-testing.com/use-case-vs-unit-testing).
- **Syfte:** Förstå syftet och tillämpningen av olika testmetoder för att effektivt validera både enskilda komponenter och användarscenarier.

### **1.2 Implementera båda testmetoderna i ditt projekt**
- **Uppgift:** 
  1. Välj en klass i ditt projekt och skriv enhetstester för dess metoder.
  2. Identifiera ett viktigt användningsfall i ditt system och utforma ett testfall som täcker detta scenario.
- **Exempel på användningsfallstest:** "Testa att användare kan registrera sig med alla obligatoriska uppgifter ifyllda."
- **Syfte:** Praktiskt tillämpa lämplig testning för att förbättra kvaliteten och pålitligheten i projektet.

## **Del 2: Tillämpning av Enums (1 timme)**

### **2.1 Identifiera möjligheter för Enums**
- **Uppgift:** Granska din kod och identifiera delar där användning av `Enums` skulle vara lämpligt för att ersätta uppsättningar av konstanter eller för att hantera definierade tillstånd.
- **Exempel:** Betrakta områden som hanterar användarroller, tillstånd i en process, eller resultat av operationer där `Enums` kan öka kodens läsbarhet och underhållbarhet.
- **Syfte:** Förbättra kodens klarhet och felhanteringskapacitet genom strategisk användning av enums.

## **Del 3: Tillämpning och granskning av arv (1.5 timmar)**

### **3.1 Implementera arv i ditt projekt**
- **Uppgift:** Läs om (fel-)användning av Arv [här](https://betterprogramming.pub/when-to-and-when-not-to-use-enums-in-java-8d6fb17ba978). Identifiera en lämplig situation i ditt projekt där arv från klasser eller användning av abstrakta klasser skulle kunna tillföra strukturellt värde och förenkla koden.
- **Exempel:** Implementera en bas-klass `Fordon` som kan ärvas av specifika fordonsklasser som `Bil`, `Cykel`, etc.

### **3.2 Granska och begränsa användningen av arv**
- **Uppgift:** För djupare insikt, läs [denna artikel](https://www.thoughtworks.com/insights/blog/composition-vs-inheritance-how-choose) som behandlar val mellan komposition och arv. Reflektera över de implementerade eller tilltänkta arvsstrukturerna i ditt projekt och identifiera potentiella problem med överanvändning av arv.
- **Diskussionspunkt:** Diskutera möjliga komplexitets- och underhållsproblem som kan uppstå genom överanvändning av arv, samt utforska moderna rekommendationer om komposition över arv.
- **Syfte:** Utveckla en förståelse för när och hur arv bör användas eller undvikas för att bibehålla kodens modularitet och flexibilitet.

## **Generell information**
- **Fokus för veckan:** Denna vecka är inriktad på att fördjupa förståelsen av avancerade programmeringsprinciper och effektiva teststrategier för att stärka projektets struktur och kvalitet.
- **Samtal om Enums/Arv:** Under veckans gruppmöte i projektet skapa utrymme för att prata om användning av enums och arv.
