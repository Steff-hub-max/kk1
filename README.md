# KK1 – Dataanalys av bankkunder

## Om projektet

Det här projektet är min första kunskapskontroll i kursen AI-programmering med Python.

Syftet med projektet är att utforska och analysera ett dataset med information om bankkunder. Jag använder Pandas för att läsa och analysera datan och Matplotlib för att skapa visualiseringar.

## Dataset

Datasetet innehåller information om bankkunder och bland annat följande kolumner:

- `CustomerId` – kundens ID
- `Surname` – kundens efternamn
- `CreditScore` – kreditpoäng
- `Geography` – kundens land
- `Gender` – kön
- `Age` – ålder
- `Tenure` – hur länge kunden varit kund
- `Balance` – kontosaldo
- `NumOfProducts` – antal bankprodukter
- `HasCrCard` – om kunden har kreditkort
- `IsActiveMember` – om kunden är aktiv medlem
- `EstimatedSalary` – uppskattad lön
- `Exited` – om kunden har lämnat banken

## Analys

I notebooken undersöker jag datasetets struktur och använder olika visualiseringar för att försöka hitta samband och skillnader mellan kunder som har lämnat banken och kunder som är kvar.

Exempel på sådant som analyseras är:

- Ålder
- Kreditpoäng
- Kontosaldo
- Antal bankprodukter
- Aktivt medlemskap
- Skillnader mellan kunder som lämnat banken och kunder som är kvar

Diagrammens titlar används för att tydliggöra vilken fråga eller slutsats som varje visualisering försöker visa.

## Teknik

Projektet är gjort med:

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Köra projektet

Installera projektets beroenden och starta sedan Jupyter Notebook.

Öppna notebooken och kör cellerna uppifrån och ned.

## Filer

- `KK1.ipynb` – notebooken med analysen och visualiseringarna
- `Bank_Churn(1).csv` – datasetet
- `Bank_Churn_Data_Dictionary.csv` – beskrivning av datasetets kolumner

## Slutsats

Analysen visar att det finns skillnader mellan kunder som lämnar banken och kunder som stannar kvar. Framför allt går det att se skillnader kopplade till exempelvis ålder, aktivitet och antal bankprodukter.

Syftet med projektet är framför allt att visa hur Python och Pandas kan användas för att undersöka ett dataset och presentera resultatet med hjälp av visualiseringar.