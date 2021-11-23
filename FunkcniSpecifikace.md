# NasaAplikace
Filip Forejt
* Úvod
  * Účel
    * Úkolem bude vytvořit jednoduchou a přehlednou aplikaci v prostředí Xamarin, který bude vypisovat objektů v okolí země podle informací od NASA. Uživatel to nebude muset složitě vyhledávat v prohlížeči a bude to mít přehledně v aplikaci, ve které nebude mít problém číst informace
  * Konvence dokumentu
    * Důležité části budou zvýrazněné
  * Pro koho je dokument určený
    * Pro uživatele, kteří chtějí mít podrobnou zprávu o programu, buď aby tomu rozuměli, nebo pokud by chtěli program nějak vylepšit do budoucna, pokud zde vidí chyby, které by mohli být vyřešeny jinak.
  * Odkazy na ostatní dokumenty
    * https://github.com/forejtos/NasaAplikace/blob/main/SRS.md

* Scénáře
  * Všechny reálné zpúsoby použití
    * Program bude použitelný pro zkoumání a sledování objektů, které jsou v blízkosti Země. Využít ho mohout ať už studenti a učitelé, lidi se zájmem sledovat tyto věci nebo i vědci.
  * Detaily, motivace, "živé" příklady
    * Program bude čerpat data přímo od NASA, které jsou na stránkách NASA API poskytnuta v JSON a bude je převádět do programu. Data budou aktualizováná vždy, když bude mít uživatel přístup k internetu a pokud ne, budou použita data od poslední aktualizace a bude tam zároveň čas poslední aktualizace.
  * Vymezení rozsahu
    * Program bude obsahovat informace pouze od NASA ze serveru NASA API a to konkrétně objekty v okolí Země.
  * Na co se nebude klást důraz
    * Důraz se nebude klást hlavně na **složitost**, jelikož chceme mít **přehledný a jednoduchý** program, tudíž složitost programu není potřeba.
* Celková hrubá architektura
  * Pracovní tok
    * Aplikace bude pro uživatele přehlednější a jednodušší na používání, protože informace přímo od JSON jsou vcelku nepřehledné a nekaždý v tom umí číst
  * Detaily
    * text
  * Všechny možné toky programu a jejich projevy
    * text
* Otevřené otázky
  * Části na které se zatím nedosáhlo shody
    * text
