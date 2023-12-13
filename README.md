# Opdrachtenboek C# SDG

*So you want to be a programmer* 

![https://github.com/Tormie/CSOpdrachtenBoek/blob/main/Code.png](https://github.com/Tormie/CSOpdrachtenBoek/blob/main/Code.png)

# Inhoudsopgave

# Vooraf
* Maak een C# Console Applicatie in Visual Studio 2022(2019). 
* Maak een github repository en deel deze met je docent.
* Voeg alle gemaakte opdrachten toe aan hetzelfde project.
* Geef doormiddel van commentaar aan bij welke opdracht het stukje code hoort.
* Commit aan het eind van je lesdag/uur al je changes zodat ik ze kan nakijken en eventueel feedback geven.
* Zorg ervoor dat je de gehele projectmap gezipt inlevert.
* Opdrachten met een * of ** zijn extra uitdagend.

# Cheat Sheet

![https://github.com/Tormie/CSOpdrachtenBoek/blob/main/csCheatSheet.png](https://github.com/Tormie/CSOpdrachtenBoek/blob/main/csCheatSheet.png)

# Opdrachten

Zorg ervoor dat het volgende stuk code tenminste in je applicatie staat:
(wat achter namespace staat moet overeen komen met je projectnaam.

![https://github.com/Tormie/CSOpdrachtenBoek/blob/main/Code2.png](https://github.com/Tormie/CSOpdrachtenBoek/blob/main/Code2.png)

## Console Schrijven

1. Gebruik drie keer Console.WriteLine om “Hello World!” naar het scherm te schrijven.
2. Gebruik drie keer achter elkaar Console.Write om “Hello World!” naar het scherm te schrijven.
3. Wat is het verschil? Zet je antwoord in een regel commentaar.
4. Gebruik Console.BackgroundColor om de achtergrondkleur van je console te veranderen. Gebruik hierna een Console.WriteLine om dit te laten zien.
5. Gebruik Console.ForegroundColor om de tekstkleur van je console te veranderen. Gebruik hierna een Console.WriteLine om dit te laten zien.
6. Schrijf een stukje code dat “Hello World” naar het scherm schrijft met voor beide woorden een andere BackgroundColor en ForegroundColor. De tekst moet op één regel staan.
7. ** Schrijf een functie met als parameters twee kleuren en een string. Deze functie schrijft de string tekst weg naar de console met de opgegeven kleuren en reset daarna de kleuren.

## Console Lezen

8.	Doormiddel van Console.ReadLine kun je gebruikersinvoer lezen. Maak een string variabele ‘userName’ aan. 
9.	Schrijf een stukje code dat de gebruiker om zijn naam vraagt. 
10.	Sla de invoer van de gebruiker op in de variabele ‘userName’.
11.	Geef ter controle de inhoud van de variabele ‘userName’ weer in de console.
12.	Doormiddel van Int32.Parse() kun je ‘proberen’ bepaalde inhoud om te zetten in een int. Maak een int variabele userAge aan.
13.	Schrijf een stukje code dat de gebruiker om zijn leeftijd vraagt.
14.	Sla de invoer van de gebruiker op in de variabele ‘userAge’ (let op het type)
15.	** Schrijf een functie die de gebruiker om een getal vraagt. Vergelijk dit getal met een opgeslagen getal. Als het hier gelijk aan is, geef dan de gebruiker terug dat hij het goed heeft geraden.

## Basis Variabelen

16.	Declareer 5 variabelen, 1 int, 1 string, 1 char, 1 float en 1 bool.
17.	Initialiseer deze 5 variabelen met een waarde.
18.	Geef 2 van deze 5 variabelen een nieuwe waarde.
19.	Declareer een nieuwe int variabele.
20.	Schrijf deze variabele naar de console.
21.	Wat gebeurt er? Waarom gebeurt dit? Zet je antwoord in een regel commentaar. 

## Bewerkingen met Variabelen

22.	Declareer twee char variabelen en initialiseer deze met een cijfer als waarde.
23.	Declareer een int variabele.
24.	Tel de twee char variabelen bij elkaar op en sla het resultaat op in de int variabele.
25.	Schrijf dit resultaat weg naar de console.
26.	Wat is het resultaat? Is dit wat je verwachtte? Waarom wel/niet? Zet je antwoord in een regel commentaar.
27.	Declareer twee string variabelen en geef deze een tekst waarde.
28.	Declareer een derde string variabele.
29.	Tel de twee string variabelen bij elkaar op en sla het resultaat op in de derde.
30.	Schrijf dit resultaat weg naar de console.
31.	Declareer drie int variabelen en initialiseer er twee.
32.	Sla de deling van de twee waarden op in de derde.
33.	Schrijf het resultaat weg naar de console.
34.	Is dit wat je verwacht? Waarom wel/niet? Zet je antwoord in een regel commentaar.
35.	Declareer twee string variabelen en een int.
36.	Initialiseer een string en de int met een waarde.
37.	Tel de int bij de string op en sla het resultaat op in de niet geinitialiseerde string.
38.	Schrijf het resultaat weg naar de console.
39.	Is dit wat je verwacht? Waarom wel/niet? Zet je antwoord in een regel commentaar.

## Casting en Conversie

40.	Declareer een int, een char en een string en initialiseer deze met een standaard waarde.
41.	Gebruik de juiste vorm (casting, conversie of parsing) om deze waarden om te zetten op de volgende manier:
  - Maar een char variabele en zet de waarde van de int hierin.
  - Maak een int variabele en zet de waarde van de char hierin.
  - Maak een int variabele en zet de waarde van de string hierin.
42.	Declareer een char variabele en geef deze een nummer als waarde.
43.	Gebruik conversie om deze waarde in een int en double te zetten. Schrijf deze waarden naar de console.
44.	Declareer een string variabele en geef deze een decimaal getal als waarde.
45.	Gebruik parsing om deze waarde in een int en double te zetten. Schrijf deze waarden naar de console. Wat valt je op?
46.	Declareer een string variabele en geef deze een woord als waarde.
47.	Gebruik TryParse om deze waarde in een int om te zetten. Wat gebeurt er?
48.	\* Binaire getallen bestaan alleen uit 0 en 1. Je kunt deze waarde opslaan in een string. Ga uit van een byte (8 bits) dit is dus bijvoorbeeld de string “01101010”.
Schrijf een functie die van een gegeven string met 8 nullen en enen de decimale waarde berekent en naar de console schrijft. (De meest rechter bit heeft de waarde 1, die daar links van 2, daar links van 4, ect).
49.	** Laat de gebruiker een stuk tekst invoeren, sla dit op in een string variabele. Gebruik TryParse om dit om te zetten in een int. Als dit lukt dan moet je programma aan de gebruiker teruggeven dat hij het goed gedaan heeft, anders moet je programma aan de gebruiker teruggeven dat hij het niet goed gedaan heeft.

## Beslissingen

50.	Declareer een int variabele en geef deze een waarde.
51.	Schrijf een if-statement dat controleert of deze int een bepaalde waarde heeft. Als dit waar is, schrijf dan “Waar” naar de console. Als het niet waar is, schrijf dan “Niet waar” naar de console.
52.	Declareer een string variabele en een char variabele. Geef deze beide hetzelfde teken als waarde.
53.	Schrijf een if-statement waarin je de string variabele met de char variabele vergelijkt. Als dit zo is, dan moet je programma “Ze zijn gelijk” naar de console schrijven. Is dit niet zo, dan moet je programma “Ze zijn niet gelijk” naar de console schrijven.
54.	Lukt dit? Zo niet, wat moet je doen om dit wel te laten werken? Schrijf je if-statement zo dat dit goed werkt.
55.	Vraag de gebruiker om een getal (van 1 t/m 12) in te voeren en sla deze op in een integer variabele (gebruik Console.ReadLine en parsing).¬¬¬¬¬¬ Schrijf een switch-statement dat de gebruikersinvoer vergelijkt met alle opties van 1 t/m 12 en geef de gebruiker in de console terug welke maandnaam hierbij hoort.
56.	\* Schrijf een stukje code dat de gebruiker om invoer vraagt. Schrijf een if-statement die controleert of dit stukje tekst overeenkomt met een string variabele die je zelf hebt ingesteld. Zorg ervoor dat je code de gebruiker een antwoord geeft afhankelijk van de invoer.
57.	** Declareer een enum Moves die minstens drie verschillende moves van het karakter van de gebruiker bevat. (bv: heal, attack, flee). Schrijf de keuzes voor de gebruiker naar de console en vraag de gebruiker om een van de opties. Controleer eerst of de invoer overeenkomt met een van de opties, geef anders aan dat dit geen correcte invoer is. Als het correct is, gebruik dan een switch statement om een stukje ‘flavor-tekst’ naar de console te schrijven die bij die move past.

## Arrays

58.	Maak een array van 5 integers aan en vul deze met willekeurige waarden. Print vervolgens de waarden van de array naar de console.
59.	Maak een array van 10 strings aan en vraag de gebruiker om de waarden in te voeren. Print vervolgens de waarden van de array naar de console.
60.	Maak een array van 8 decimalen aan en vul deze met willekeurige waarden. Bereken vervolgens het gemiddelde van de waarden in de array en print deze waarde naar de console.
61.	Maak een array van 7 doubles aan en vraag de gebruiker om de waarden in te voeren. Bereken vervolgens de som van de waarden in de array en print deze waarde naar de console.
62.	Maak een array van 6 strings aan en vraag de gebruiker om de waarden in te voeren. Gebruik vervolgens de Array.Sort() methode om de array te sorteren en print de gesorteerde array naar de console.
63.	Maak een array van 9 integers aan en vul deze met willekeurige waarden. Gebruik vervolgens de Array.Reverse() methode om de array om te keren en print de omgekeerde array naar de console.
64.	Maak een array van 10 doubles aan en vraag de gebruiker om de waarden in te voeren. Gebruik vervolgens de Array.IndexOf() methode om te zoeken naar een specifieke waarde in de array en print de index van de waarde naar de console.
65.	Maak een array van 5 characters aan en vul deze met willekeurige waarden. Gebruik vervolgens de Array.Clear() methode om de array leeg te maken en print de lege array naar de console.
66.	Maak een array van 8 booleans aan en vul deze met willekeurige waarden. Gebruik vervolgens de Array.Find() methode om te zoeken naar een specifieke waarde in de array en print de gevonden waarde naar de console.
67.	\* Maak een 2D array van 3 rijen en 4 kolommen aan en vul deze met willekeurige waarden. Print vervolgens de waarden van de array naar de console.
68.	** Maak een 2D array van 5 rijen en 5 kolommen aan en vul deze met willekeurige waarden. Schrijf vervolgens een functie die de som van de waarden in de bovenste rij van de array berekent en de som van de waarden in de onderste rij van de array berekent. Print vervolgens de som van de waarden in de bovenste rij en de som van de waarden in de onderste rij naar de console. Daarnaast moet de functie ook de grootste waarde in de bovenste rij en de grootste waarde in de onderste rij retourneren, print deze waarden ook naar de console.

## Clean Code

69.	Schrijf een functie die de lengte van een string controleert. Gebruik een zinvolle naam voor de functie, en maak gebruik van de ingebouwde string methode om de lengte te bepalen.
70.	Schrijf een functie die de eerste letter van een string uppercase maakt. Gebruik zinvolle namen voor de functie en voor de parameter die de string ontvangt.
71.	Schrijf een functie die twee getallen bij elkaar optelt. Gebruik zinvolle namen voor de functie en voor de parameters die de getallen ontvangen. Voeg ook een duidelijk commentaar toe dat de functie beschrijft.
72.	Schrijf een functie die bepaalt of een getal even of oneven is. Gebruik zinvolle namen voor de functie en voor de parameter die het getal ontvangt. Voeg ook een duidelijk commentaar toe dat de functie beschrijft.
73.	Schrijf een functie die de grootste waarde van drie getallen bepaalt. Gebruik zinvolle namen voor de functie en voor de parameters die de getallen ontvangen.
74.	Schrijf een functie die een array sorteert van klein naar groot. Gebruik zinvolle namen voor de functie en voor de parameter die de array ontvangt. Maak gebruik van de ingebouwde sorteermethode van de array.
75.	Schrijf een functie die bepaalt of een string een palindroom is. Gebruik zinvolle namen voor de functie en voor de parameter die de string ontvangt. Voeg ook een duidelijk commentaar toe dat de functie beschrijft.
76.	Schrijf een functie die de som van alle even getallen in een array bepaalt. Gebruik zinvolle namen voor de functie en voor de parameter die de array ontvangt.

## While Loops

77.	Gebruik een while-loop om alle even getallen tussen 0 en 20 te printen.
78.	Laat de gebruiker een getal invoeren en gebruik een while-loop om alle getallen af van dat getal tot 0 te printen.
79.	Gebruik een while-loop om de tafel van 5 te printen, beginnend bij 5 en eindigend bij 50.
80.	Laat de gebruiker een woord invoeren en print elk karakter in het woord af, in omgekeerde volgorde, doormiddel van een while-loop.
81.	Laat de gebruiker een getal invoeren en bereken de som van alle getallen van 1 tot dat getal, doormiddel van een while-loop.
82.	Laat de gebruiker een woord invoeren en controleer doormiddel van een while-loop of het een palindroom is.
83.	Laat de gebruiker een getal invoeren en bepaal doormiddel van een while-loop of het een priemgetal is.
84.	Laat de gebruiker een reeks getallen invoeren doormiddel van een while-loop, totdat hij/zij "-1" invoert. Print vervolgens het grootste en kleinste getal af.
85.	Laat de gebruiker een reeks getallen invoeren doormiddel van een while-loop, totdat hij/zij "-1" invoert. Bepaal vervolgens het gemiddelde van alle ingevoerde getallen.
86.	Laat de gebruiker een getal invoeren en print alle Fibonacci-getallen tot dat getal af doormiddel van een while-loop. 

## For Loops

87.	Schrijf een for-loop die van 1 tot en met 10 telt en ieder getal afdrukt.
88.	Schrijf een for-loop die van 10 tot en met 1 telt en ieder getal afdrukt.
89.	Schrijf een for-loop die alle even getallen van 2 tot en met 20 afdrukt.
90.	Schrijf een for-loop die de tafel van 7 afdrukt tot en met 70.
91.	Schrijf een for-loop die de som van alle getallen van 1 tot en met 100 berekent.
92.	Console.WriteLine(sum);
93.	Schrijf een for-loop die alle letters van het woord "hello" afdrukt.
94.	Schrijf een for-loop die alle getallen tussen twee door de gebruiker ingevoerde getallen afdrukt.
95.	Schrijf een for-loop die de grootste waarde in een array van integers vindt.
96.	Schrijf een for-loop die alle elementen van een array van strings afdrukt.
97.	Schrijf een for-loop die alle oneven getallen tussen twee door de gebruiker ingevoerde getallen afdrukt.

## Do While Loops

98.	Gebruik een do while-loop om de gebruiker om een getal te vragen totdat hij/zij een even getal invoert.
99.	Gebruik een do while-loop om de gebruiker om zijn/haar leeftijd te vragen totdat hij/zij een getal tussen 18 en 99 invoert.
100.	Gebruik een do while-loop om de gebruiker om zijn/haar naam te vragen totdat hij/zij een naam invoert die korter is dan 10 letters.
101.	Gebruik een do while-loop om de gebruiker om een wachtwoord te vragen totdat hij/zij het correcte wachtwoord invoert.
102.	Gebruik een do while-loop om de gebruiker om een getal te vragen totdat hij/zij een getal invoert dat tussen 1 en 100 ligt.
103.	Gebruik een do while-loop om de gebruiker om zijn/haar adres te vragen totdat hij/zij een adres invoert dat langer is dan 20 letters.
104.	Gebruik een do while-loop om de gebruiker om een cijfer te vragen totdat hij/zij een getal invoert dat tussen 1 en 10 ligt.
105.	Gebruik een do while-loop om de gebruiker om zijn/haar telefoonnummer te vragen totdat hij/zij een geldig telefoonnummer invoert.
106.	Gebruik een do while-loop om de gebruiker om zijn/haar e-mailadres te vragen totdat hij/zij een geldig e-mailadres invoert.
107.	Gebruik een do while-loop om de gebruiker om een getal te vragen totdat hij/zij een negatief getal invoert.

## Combinatie Opdrachten

108.	Schrijf een programma dat de gebruiker vraagt om zijn/haar naam in te voeren en vervolgens begroet met "Hallo [naam]!". Als de gebruiker 'stop' invoert, stopt het programma.
109.	Schrijf een programma dat de gebruiker vraagt om een getal in te voeren en controleert of het getal groter is dan 10. Als dit het geval is, moet het programma "Het getal is groter dan 10" afdrukken, anders moet het programma "Het getal is kleiner of gelijk aan 10" afdrukken. Het programma moet blijven vragen om nieuwe getallen totdat de gebruiker 'stop' invoert.
110.	Schrijf een programma dat de gebruiker vraagt om zijn/haar leeftijd in te voeren en controleert of hij/zij oud genoeg is om alcohol te drinken. Als de gebruiker 18 jaar of ouder is, moet het programma "Je bent oud genoeg om alcohol te drinken" afdrukken, anders moet het programma "Je bent te jong om alcohol te drinken" afdrukken. Het programma moet blijven vragen om nieuwe leeftijden totdat de gebruiker 'stop' invoert.
111.	Schrijf een programma dat de gebruiker vraagt om zijn/haar naam in te voeren en controleert of deze overeenkomt met een vooraf gedefinieerde lijst van namen. Als de naam overeenkomt met een naam in de lijst, moet het programma "Welkom [naam]!" afdrukken, anders moet het programma "Je bent niet welkom hier" afdrukken. Het programma moet blijven vragen om nieuwe namen totdat de gebruiker 'stop' invoert.
112.	Schrijf een programma dat de gebruiker vraagt om zijn/haar favoriete kleur in te voeren en vervolgens controleert of deze overeenkomt met een vooraf gedefinieerde lijst van kleuren. Als de kleur overeenkomt met een kleur in de lijst, moet het programma "Mijn favoriete kleur is ook [kleur]" afdrukken, anders moet het programma "Ik hou niet van die kleur" afdrukken. Het programma moet blijven vragen om nieuwe kleuren totdat de gebruiker 'stop' invoert.
113.	Schrijf een programma dat de gebruiker vraagt om 5 getallen in te voeren en deze in een array opslaat. Het programma moet vervolgens de grootste waarde in de array bepalen en afdrukken.
114.	Schrijf een programma dat een array van strings met 5 namen bevat. Het programma moet de gebruiker vragen om een naam in te voeren en controleren of deze in de array voorkomt. Als de naam in de array voorkomt, moet het programma "Ja, die naam zit in de lijst!" afdrukken, anders moet het programma "Nee, die naam zit niet in de lijst" afdrukken.
115.	Schrijf een programma dat een array van integers met 10 getallen bevat. Laat de gebruiker de 10 getallen opgeven. Het programma moet het gemiddelde van de getallen berekenen en afdrukken.
116.	Schrijf een programma dat een array van integers met 10 getallen bevat. Laat de gebruiker de 10 getallen opgeven. Het programma moet alle getallen in de array afdrukken die deelbaar zijn door 3.
117.	Schrijf een programma dat de gebruiker vraagt om een cijfer tussen 1 en 10 in te voeren en vervolgens het cijfer omzet naar een lettercijfer. Bijvoorbeeld, als de gebruiker "8" invoert, moet het programma "B" afdrukken. Gebruik hiervoor een switch statement. Als de gebruiker een getal invoert dat buiten de range 1-10 valt, moet het programma een foutmelding afdrukken.
118.	Schrijf een programma dat de gebruiker vraagt om een getal in te voeren en vervolgens alle even getallen afdrukt tot het ingevoerde getal. Gebruik hiervoor een loop en een if statement.
119.	Schrijf een programma dat de gebruiker vraagt om een wachtwoord in te voeren. Het programma moet blijven vragen om een wachtwoord totdat de gebruiker het juiste wachtwoord invoert. Gebruik hiervoor een loop en een if statement.
120.	Schrijf een programma dat de gebruiker vraagt om 5 getallen in te voeren. Het programma moet vervolgens het grootste en het kleinste getal afdrukken. Gebruik hiervoor een loop, een if statement en variabelen om de grootste en kleinste waarde bij te houden.
121.	Schrijf een programma dat de gebruiker vraagt om een cijfer tussen 1 en 7 in te voeren en vervolgens het corresponderende dag van de week afdrukt. Gebruik hiervoor een switch statement.
122.	Schrijf een programma dat de gebruiker vraagt om een getal tussen 1 en 10 in te voeren en vervolgens de tafel van vermenigvuldiging voor dat getal afdrukt. Gebruik hiervoor een loop en console.writeline om de berekeningen af te drukken.

## Methoden

123.	Schrijf een methode genaamd "HalloWereld" die "Hallo, Wereld!" naar de console print.
124.	Schrijf een methode genaamd "GroetUser" die de gebruiker vraagt om hun naam in te voeren en vervolgens een begroeting met hun naam naar de console print.
125.	Schrijf een methode genaamd "BerekenSom" die twee getallen van de gebruiker vraagt en de som van deze getallen berekent en naar de console print.
126.	Schrijf een methode genaamd "BerekenGemiddelde" die een array van getallen van de gebruiker vraagt en het gemiddelde van deze getallen berekent en naar de console print.
127.	Schrijf een methode genaamd "IsEven" die een getal van de gebruiker vraagt en controleert of het getal even is. De methode moet "true" teruggeven als het getal even is en "false" als het getal oneven is.
128.	Schrijf een methode genaamd "Faculteit" die een getal van de gebruiker vraagt en de faculteit van dat getal berekent en naar de console print.
129.	Schrijf een methode genaamd "OmkeerString" die een woord van de gebruiker vraagt en de omgekeerde versie van dat woord naar de console print.
130.	Schrijf een methode genaamd "IsPalindroom" die een woord van de gebruiker vraagt en controleert of het woord een palindroom is. De methode moet "true" teruggeven als het woord een palindroom is en "false" als dat niet het geval is.
131.	Schrijf een methode genaamd "BerekenMacht" die twee getallen van de gebruiker vraagt, waarbij het eerste getal de basis is en het tweede getal de exponent. De methode moet de waarde van de basis tot de macht exponent berekenen en naar de console print.
132.	Schrijf een methode genaamd "SchrijfTafel" die een getal van de gebruiker vraagt en de vermenigvuldigingstafel van dat getal afdrukt naar de console.

## Basis OOP

133.	Maak een klasse genaamd "Persoon" met eigenschappen zoals "naam", "leeftijd" en "geslacht". Schrijf vervolgens code om een object van deze klasse te maken en de eigenschappen in de console af te drukken.
134.	Breid de "Persoon" klasse uit met een methode genaamd "Groet", die een begroeting afdrukt met de naam van de persoon. Maak een object van deze klasse en roep de "Groet" methode aan.
135.	Maak een klasse genaamd "Rechthoek" met eigenschappen zoals "lengte" en "breedte". Voeg een methode toe genaamd "BerekenOppervlak" die de oppervlakte van het rechthoek berekent en retourneert. Test de methode met verschillende lengtes en breedtes.
136.	Creëer een klasse genaamd "BankRekening" met eigenschappen zoals "rekeningnummer", "naam" en "saldo". Voeg methoden toe voor het storten en opnemen van geld van de rekening. Test de methoden met enkele transacties.
137.	Maak een klasse genaamd "Student" die is afgeleid van de "Persoon" klasse. Voeg een extra eigenschap toe genaamd "studentnummer" en een methode genaamd "ToonInfo" die zowel de eigenschappen van de "Persoon" klasse als het "studentnummer" afdrukt.
138.	Maak een klasse genaamd "Auto" met eigenschappen zoals "merk", "model" en "bouwjaar". Schrijf code om een lijst van auto-objecten te maken en deze in de console af te drukken.
139.	Maak een klasse genaamd "Rekenmachine" met een statische methode genaamd "Optellen" die twee getallen optelt en het resultaat retourneert. Gebruik de methode om de som van twee getallen af te drukken.
140.	Maak een klasse genaamd "Cirkel" met een eigenschap genaamd "straal" en een methode genaamd "BerekenOmtrek" die de omtrek van de cirkel berekent en retourneert. Test de methode met verschillende stralen.
141.	Creëer een klasse genaamd "Product" met eigenschappen zoals "naam", "prijs" en "beschikbaarheid". Voeg een methode toe genaamd "CheckBeschikbaarheid" die controleert of het product op voorraad is. Test de methode met verschillende producten.
142.	Maak een klasse genaamd "Bank" met een lijst van "BankRekening" objecten als eigenschap. Voeg methoden toe voor het toevoegen en verwijderen van bankrekeningen aan de lijst, evenals een methode om alle bankrekeningen af te drukken. Test de methoden met enkele bankrekeningen

## OOP Advanced

143.	Maak een klasse genaamd "Medewerker" met eigenschappen zoals "naam", "salaris" en een methode genaamd "BerekenBonus" die een bonus voor de werknemer berekent op basis van hun salaris. Maak vervolgens subklassen zoals "Manager" en "Developer" die de "BerekenBonus" methode overschrijven om een specifieke bonusberekening te implementeren.
144.	Maak een klasse genaamd "Voertuig" met eigenschappen zoals "merk", "model" en een methode genaamd "StartMotor" die aangeeft dat het voertuig is gestart. Maak vervolgens subklassen zoals "Auto" en "Motor" die de "StartMotor" methode overschrijven om specifieke startgedragingen te implementeren.
145.	Maak een klasse genaamd "Persoon" met eigenschappen zoals "Naam" en "Leeftijd" en een methode genaamd "Introduceer" die de persoon introduceert door hun naam en leeftijd af te drukken. Maak vervolgens subklassen zoals "Student" en "Leraar" die de " Introduceer " methode overschrijven om specifieke introducties voor die rollen te implementeren.
146.	Maak een klasse genaamd "BankRekening" met eigenschappen zoals "RekeningNummer", "Balans" en een methode genaamd "Opnemen" die een bedrag van de balans aftrekt. Maak vervolgens subklassen zoals "SpaarRekening" en "BetaalRekening" die de " Opnemen" methode overschrijven om specifieke validatie of gedragingen toe te voegen.
147.	Maak een klasse genaamd "GameCharacter" met eigenschappen zoals "Name" en "Health" en implementeer een virtuele methode genaamd "Attack" die aangeeft hoe het personage aanvalt. Maak vervolgens subklassen zoals "Warrior" en "Mage" die de "Attack" methode overschrijven met hun eigen aanvalsmechanismen.
148.	Maak een klasse genaamd "Game" met eigenschappen zoals "Title" en "Genre" en implementeer een virtuele methode genaamd "PlayGame" die aangeeft hoe het spel wordt gespeeld. Maak vervolgens subklassen zoals "PuzzleGame" en "ShooterGame" die de "PlayGame" methode overschrijven met hun eigen speelstijl.

## Challenges
### Probleemoplossen

1.	Schrijf een functie Priem_Zoeker(int n) die alle priemgetallen van 1 t/m n teruggeeft. (Een priemgetal is een getal dat enkel deelbaar is door 1 en zichzelf).
2.	Schrijf een functie KeerOm(string s) die de positie van de woorden in de string omkeert. ("Hallo mijn naam is Niels” wordt dan: “Niels is naam mijn Hallo”).
3.	Schrijf een functie UniekeTekens(string s) die aangeeft of een gegeven string enkel unieke tekens bevat(niet één teken mag vaker dan 1x voorkomen). Laat de functie een bool teruggeven die aangeeft of de invoer hieraan voldoet of niet.
4.	Schrijf een functie GemiddeldeVinder(int[] x) die van de invoer het gemiddelde en de modus teruggeeft. (De modus is de waarde die het vaakst voorkomt in de lijst).
5.	Schrijf een functie Fibonacci(int x) die het x’te getal in de Fibonacci-reeks weergeeft. (De Fibonacci-reeks is een reeks getallen waar ieder getal de optelling van zijn twee voorgangers is – de reeks begint met 0 en 1.) Begin van de reeks: 0,1,1,2,3,5,8,etc. Laat je functie de waarde berekenen, geef dus niet een hardcoded reeks op.
6.	Schrijf een functie PascalDriehoek(int x) die een Pascaldriehoek van hoogte x op het scherm schrijft. (Een Pascaldriehoek is een driehoeksweergave van verschillende cijferwaarden. De driehoek begint altijd met een enkele 1 bovenaan. Alle waarden daaronder zijn de optellingen van hun linker en rechter bovenbuur. Zie afbeelding)   
![https://github.com/Tormie/CSOpdrachtenBoek/blob/main/PascalTriangle.png](https://github.com/Tormie/CSOpdrachtenBoek/blob/main/PascalTriangle.png)   
8.	Schrijf een functie Anagram(string s) die in de gegeven string s kijkt of er woorden in staan die een anagram van elkaar zijn. Laat de functie deze woorden teruggeven.(Een anagram is een woord dat uit dezelfde letters bestaat als het woord waarmee vergeleken word). Voorbeeld: “Het bezoeken van deze engte stond hem erg tegen.”
9.	Schrijf een functie RekenWonder() die alle mogelijkheden om + en – (of niets) tussen een rij van de getallen 1 t/m 9 berekent (en weergeeft) waarbij het resultaat 100 is. (Voorbeeld: 1+2+3-4+5+6+78+9=100)
10.	Schrijf een functie StringFramed(string s) die alle woorden van een string op een losse regel en het totaal omkaderd weergeeft. (Voorbeeld: “Hallo wereld in een lijst”)   
![https://github.com/Tormie/CSOpdrachtenBoek/blob/main/HW%20framed.png](https://github.com/Tormie/CSOpdrachtenBoek/blob/main/HW%20framed.png) 
11.	Schrijf een functie SchrikkelJaar(int x) die de x eerstvolgende schrikkeljaren weergeeft.
12.	Schrijf een functie LosseCijfers(int x) die alle cijfers waaruit het getal x bestaat als losse waarden in een int-array teruggeeft. (Voorbeeld LosseCijfers(2345) = [2,3,4,5]
13.	Schrijf een functie IntNaarBinair(int x) die van een integer waarde een string maakt die zijn binaire waarde weergeeft. (Voorbeeld: IntNaarBinair(5) = “101”)
14.	Schrijf een functie BinairNaarInt(string b) die van een string-weergave van een binair getal de integer waarde uitrekent en weergeeft.

### Games

Voor alle hier te maken games geldt dat deze games in een loop moeten draaien. De game moet de speler om zijn naam vragen en deze gedurende de hele game onthouden. De game moet na ieder potje de speler vragen of hij nog een keer wil spelen. Als dit zo is dan mag de game niet afgesloten worden, maar moet deze een interne oplossing hebben om het proces te herstarten. De spellen moeten voldoende communicatief zijn naar de speler, zodat deze op alle mogelijke momenten doorheeft wat er precies gebeurt.

1.	Maak Steen-Papier-Schaar waarin je het tegen de computer opneemt.
2.	Maak Boter, Kaas en Eieren waarin je het tegen de computer of een andere speler opneemt. Zorg voor een visuele weergave van het speelveld.
3.	Maak een dobbelspel waarin je het aantal te gooien dobbelstenen kunt kiezen. Speel het tegen de computer of een andere speler. Degene met het hoogste totaal aantal ogen wint.
4.	Maak Mastermind. Mastermind is een spel voor 1 speler waarin deze een getal van 4 cijfers moet raden. Een speler mag 10 keer raden en krijgt iedere keer teruggekoppeld hoeveel cijfers er juist zijn maar op de verkeerde plek staan en hoeveel cijfers er juist zijn en op de juiste plek staan.
5.	Maak BlackJack(21en). Zoek de regels voor BlackJack op als je deze niet kent en implementeer deze allemaal. De computer is de deler.
6.	Maak Memory voor een of meer spelers, zorg voor een duidelijke grafische weergave en volg de spelregels.
7.	Maak Lingo. Zoek of stel zelf een lijst met mogelijke 5-letter woorden op en laat een speler het woord raden. De eerste beurt krijgt de speler een van de letters van het te raden woord. De speler mag 5x proberen dit woord te raden en krijgt terug of een letter goed is en op de goede plek staan of goed is en op de verkeerde plek staat.
8.	Maak Zeeslag. Let op: dit is een erg complexe game. Zorg ervoor dat een speler dit tegen de computer kan spelen. Zorg voor een goede willekeurige plaatsing van de computerschepen en bedenk een goede oplossing voor de speler om schepen te plaatsen. Laat de computer ‘slim’ maar eerlijk spelen, dus wanneer hij een schip geraakt heeft probeert hij dat schip eerst te vernietigen.

### De Ultieme Uitdaging!

Het uitvoeren van deze opdracht vraagt een goede algemene kennis van het programmeren in C# (of een andere OOP-taal). Zorg ervoor dat je alles goed scheidt en iedere klasse zijn eigen bestand geeft. Het is essentieel dat je met klassen werkt en het gebruik van enums en coroutines kan ook handig zijn.

Benodigde kennis: datatypen, expressies, operatoren, beslissingen, strings, loops, methoden, arrays, lists, classes, file system.

De opdracht:
Maak een game die gebaseerd is op de oorspronkelijke Rogue(1980). In deze game moet er iedere keer dat je speelt een willekeurige level gegenereerd worden. Als speler is je doel alle vijanden in het level te verslaan om vervolgens in een nieuw level geplaatst te worden. Door vijanden te verslaan krijg je xp en eventueel gold en items. Na een x-aantal levels krijg je een store waar je items kunt kopen die je character sterker maken. Zorg dus voor een werkbare character en inventory implementatie. 

![https://github.com/Tormie/CSOpdrachtenBoek/blob/main/Rogue_Screenshot.png](https://github.com/Tormie/CSOpdrachtenBoek/blob/main/Rogue_Screenshot.png)

Mechanics: 
Als speler beweeg je je door de kamer met de pijltjestoetsen. Je beweegt een vakje per keer. Iedere keer als je beweegt bewegen de vijanden (die je gezien hebben) naar je toe of vallen je aan als dat mogelijk is.
Als je naar een vakje beweegt waar zich een vijand bevind, dan val je deze vijand aan met het wapen dat je character op dat moment in zijn hand(en) heeft.

Layout:
De gegenereerde levels moeten 64 bij 32 karakters zijn, daarnaast moet er wat ruimte zijn voor een rudimentaire GUI die de eigenschappen van je character weergeeft. Zorg ervoor dat de buitenrand van de kamer een duidelijke muur is. En dat het GUI-deel goed te onderscheiden is van de rest.
Gebruik alleen ASCII-tekens voor de visuele weergave. Kies duidelijke karakters voor je speler en voor vijanden en pickups. 

Vereisten:
* Menuscherm
* Random (bruikbare) levels van 64x32 characters.
* GUI
* Speler class met xp, health, inventory
  * Optioneel: ras
  * Optioneel: klasse
  * Optioneel: Stats (str, dex, int, etc)
* Enemy class
* XP en leveling systeem
* Inventory en items systeem
* Shop
* Optioneel: ranged/magic systeem
