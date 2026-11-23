# Case 03 – Ta bort en fil från staging

## Scenario

Du har gjort en ändring i `index.html`.

Lägg ändringen i staging med:

git add index.html

Du inser sedan att du inte vill ha med ändringen i nästa commit.

## Din uppgift

- Kontrollera vilka filer som finns i staging.
- Ta bort `index.html` från staging.
- Kontrollera att filen inte längre är staged.
- Se till att ändringen fortfarande finns kvar i arbetskatalogen.

> **Tips:** Att ta bort en fil från staging innebär inte att filens ändringar försvinner.
# Case 06 – Jag vill bara committa delar av mina ändringar

## Scenario

Du har gjort flera separata ändringar på olika ställen i samma fil, men du vill inte committa alla ändringar samtidigt.

Endast en del av ändringarna ska ingå i nästa commit.

## Din uppgift

1. Gör minst två separata ändringar på olika ställen i samma fil.
2. Kontrollera vilka ändringar som har gjorts.
3. Lägg endast till de ändringar som ska ingå i nästa commit.
4. Skapa en commit med de valda ändringarna.
5. Kontrollera att övriga ändringar fortfarande finns kvar i arbetskatalogen.

> **Tips:** Git kan låta dig välja vilka delar av en fil som ska ingå i nästa commit, utan att övriga ändringar försvinner.
# Case 01 – Jag committade fel fil

## Scenario

Du arbetade med webbplatsen och råkade committa en fil som inte ska finnas i projektet.

Filen har redan blivit committad, men den ska inte ingå i projektets historik.

## Din uppgift

- Identifiera vilken fil som har committats av misstag.
- Ta bort filen från den senaste commiten.
- Behåll övriga ändringar i projektet.
- När du är klar ska projektet se ut som innan den felaktiga filen lades till.

> **Tips:** Kontrollera först projektets historik och status innan du börjar göra ändringar.
# Case 04 – Jag vill ångra ändringar

## Scenario

Du har gjort ändringar i en eller flera filer, men inser att du inte vill behålla dem.

Ändringarna finns bara lokalt i arbetskatalogen och är ännu inte committade.

## Din uppgift

1. Gör en eller flera ändringar i projektet.
2. Kontrollera vilka filer som har ändrats.
3. Ångra ändringarna med hjälp av Git.
4. Kontrollera att filerna har återställts till den senaste committade versionen.

> **Tips:** Kontrollera status före och efter att du löst uppgiften.
# Case 05 – Jag vill gå tillbaka till en tidigare commit

## Scenario

Du har gjort flera commits i projektet, men inser att du vill återgå till en tidigare version.

## Din uppgift

1. Undersök projektets commit-historik.
2. Hitta den commit du vill återgå till.
3. Återställ projektet till den tidigare commiten.
4. Kontrollera att projektet ser ut som det gjorde vid den valda commiten.

> **Tips:** Börja med att undersöka projektets commit-historik för att hitta den version du vill återgå till.
