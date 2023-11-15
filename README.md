# XGBoost
I denna ska kunder analyseras och prediktioner på vilka som lämnar (churnar) ska göras. XGBoost skall användas för att göra prediktionerna.
Företaget telco vill ha hjälp med att analysera kunder och hitta vilka som kommer lämna
företaget för att kunna jobba för att behålla de kunderna. En churnmodell ska tränas för att
hjälpa med detta problem.
Modellen ska tränas på churn_train.csv och den ska testas på churn_test.csv
Följande punkter och frågor behandlas.
● Analysera datan
○ Hur ser fördelningen av target datan ut? Är den jämnt fördelad? Om inte, kan
det ställa till med problem?
● Förbered datan för att kunna användas av modellen
○ Finns det data som ej borde användas? Varför i så fall?
○ Det finns en hel del textdata som måste behandlas på något vis (finns flera
olika alternativ).
● Träna en XGBoost modell
● Utvärdera modellen
○ Beräkna accuracy
○ Analysera vilka attribut som har störst påverkan
○ Rita ut en confusion matrix och analysera hur modellen gör prediktioner och
vilka typer av fel den gör.
● En accurecy score över 78.5% är målet.
