# sqlstuff
 
### tabelle drunkie
*persid surname forename country state*
- 1 Bond James UK EN
- 2 Bierig Josef DE BY

### tabelle drink
*name alcohol(gehalt)*
- 'vodka martini' -1
- 'aventinus' 8.2

### tabelle drinking
persid name
- 1 'vodka martini'
- 2 'aventinus'

## studienleistung
### tabelle game genre marketshare
*genreid genre* 
- 1 shooter
- 2 RPG

`result = stmt.executeUpdate("DROP TABLE IF EXISTS Game CASCADE");
            result = stmt.executeUpdate("CREATE TABLE Game(Game text UNIQUE NOT NULL PRIMARY KEY, ReleaseDate date NOT NULL, PeakViewership integer NOT NULL)");`

### tabelle games
 *genreid game*
- 1 CoD MW2
- 2 BaldursGate

### tabelle gamereleaseyear
- COD MW2 2002
- BaldursGate 2019
