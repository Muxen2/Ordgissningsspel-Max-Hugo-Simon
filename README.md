Ordgissningsspel – Python-spel

Detta är ett enkelt textbaserat ordgissningsspel där spelaren ska gissa ett slumpmässigt valt ord genom att mata in bokstäver. Spelet fortsätter tills spelaren gissat hela ordet eller förlorat alla sina försök.

Funktioner

Slumpar ett ord från en stor ordlista.

Visar ordet som en rad av \* som avslöjas allt eftersom spelaren gissar rätt.

Hanterar ogiltig input (t.ex. fler tecken än 1).

Kontrollerar om en bokstav gissats tidigare.

Räknar antal återstående försök.

Ger vinst- och förlustmeddelanden.

Hur spelet fungerar

Programmet väljer ett slumpmässigt ord.

Spelaren gissar en bokstav per omgång.

Om bokstaven finns avslöjas den i ordet.

Felaktiga gissningar minskar antalet försök.

Spelet avslutas när:

Ordet är helt gissat (vinst), eller

Försöken tar slut (förlust)

Potienella buggar

Vi hade bara 1 bugg och det var att spelet printade att man vann när man förlorade och tvärtom, men det fixade vi.

Lägga till i framtiden

Svårhetsgrader för orden.
