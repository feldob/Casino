# **Veckouppgift: Förståelse och Analys av Abstrakta Datatyper och Annotationer**

## **Del 1: Abstrakta Datatyper (ADT) (3 timmar)**

### **1.1 Förståelse för olika ADT**
- **Uppgift:** Titta på den [denna video](https://www.youtube.com/watch?v=XkoeF-xXo2o) om abstrakta datatyper. Fokusera särskilt på skillnaderna och användningsområden för `Set`, `Map`, och `List`.
- **Syfte:** Förstå vikten av olika ADT och deras användning för att effektivt hantera data. Utforska hur `ArrayList`, `HashSet`, och `HashMap` implementerar dessa gränssnitt och de prestandamässiga konsekvenserna av varje val.

### **1.2 Vikten av `hashCode` och `equals`**
- **Uppgift:** 
  1. Lär dig hur `hashCode` och `equals` metoder påverkar beteendet hos datatyper som `HashSet` och `HashMap`.
  2. Be ChatGPT om kodexempel där korrekt implementering av dessa metoder är avgörande för ADT:ernas funktion.
- **Syfte:** Förstå hur Java använder `hashCode` och `equals` för att hantera kollisioner och identifiera unika objekt inom samlingar, och hur du kan implementera dessa metoder för att säkerställa korrekt beteende av dina datastrukturer.

### **1.2 Tillämpa ADT i ditt projekt**
- **Uppgift:**
  1. Identifiera delar av ditt projekt där olika ADT kan förbättra datahanteringen. Reflektera över vilka ADT som skulle vara mest lämpliga för olika delar av ditt system. Implementera minst två olika ADT (som `HashSet` eller `LinkedList`).
  2. Jämför när `PriorityQueue` skulle vara mer lämplig jämfört med `ArrayList` baserat på deras prestanda och beteende.
- **Diskussionspunkt:** Diskutera varför olika projektsegment kan gynnas av antingen `Stack` eller `PriorityQueue`. Vidare, vilka gemensamma gränssnitt (interfaces) delar dessa strukturer och varför är dessa gränssnitt viktiga för polymorfism inom Java.
- **Syfte:** Utveckla en djupare förståelse för när och hur olika ADT bör användas för att möta specifika krav i ditt projekt.

## **Del 2: Lambda, Strömmar och Annotationer (2 timmar)**

### **2.1 Introduktion till Lambda-uttryck och Strömmar**
- **Uppgift:** 
  1. Titta på [denna video](https://www.youtube.com/watch?v=Q93JsQ8vcwY) om lambda-uttryck och metodreferenser samt introduktion till Java Streams.
  2. (Valfritt) Försök implementera en enkel funktion med lambda i ditt projekt för att se fördelarna med deklarativ kod jämfört med imperativ kod.
- **Syfte:** Förstå grundläggande koncept av funktionell programmering och dess potentiella fördelar för programutveckling.

### **2.2 Förståelse och analys av Annotationer**
- **Uppgift:** 
  1. Läs om hur annotationer används i Java, speciellt inom testramverk som JUnit. Exempel på annotationer i JUnit inkluderar `@Test`, `@BeforeEach`, och `@AfterEach`.
  2. Utforska och identifiera ytterligare 2-3 användningsfall för annotationer i Java. Reflektera över hur dessa kan vara användbara i olika projekt, även om du inte kommer att implementera dem just nu.
- **Syfte:** Förstå hur annotationer kan användas för att ge metadata om kodens beteende och hur de kan förenkla vissa programmeringsuppgifter.

## **Generell information**
- **Fokus för veckan:** Den här veckan fokuserar vi på att förstå och analysera abstrakta datatyper och funktionell programmering, samt att utforska konceptet av annotationer.
- **Diskussion och gruppfeedback:** Sätt upp tid för genomgång där ni diskuterar hur olika ADT och programmeringsstilar kan påverka design och prestanda i era projekt.

Denna uppgift är utformad för att djupdyka i abstrakta datatyper och annotationer, vilket ger er teoretiska färdigheter som är direkt tillämpbara på era projekt och framtida yrkesliv.
