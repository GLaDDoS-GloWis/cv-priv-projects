# Anlage zu Lebenslauf | Künftige private Projekte
Auflistung von Ideen die zukünftig privat umgesetzt werden.  


## WebApp Nutzerverwaltung für Gaming Community Administration
Umsetzung des BEs: In Java mit Spring eine REST  
Umsetzung des FEs: Mit VueJS  
- Bungie.net API
- Discord API (discord.py)
- Steam API
- DB: MongoDB(?) oder Postgres(?) 

## Raidkalender für Destiny 2
Umsetzung des BEs: In Java mit Spring eine REST  
Umsetzung des FEs: Mit VueJS  
- WebCal 
- Bungie.net API
- Discord API (discord.py)
- Discord Benachrichtigung
- Logs

## Discord Bot Development
Implementierung mit Python und discord.py  
Features werden in Microservices unterteilt und Docker bereit gemacht  
Wesentliche Features:  

### Guardian (fertig implementiert & als Docker image deployed)
- Bei- und Austritt monitoring 

### Cleanser
- Löschung von X Nachrichten in Channel Y bzw. bulk deletion
- Crontab Funktionalität zu Channel hinzufügen bzw. "säubere den gesamten Kanal um 23:59Uhr"

### Rollenkiosk 
- Vergabe von Rollen via emote-reactions
- Dabei gibt "+" und "-" nimmt die Rolle
- Logging der entsprechenden Aktion

### Voice Chat(VC) Diner
*Ein Tisch für 2 bitte!*
- Dynamische VC Erstellung durch beitreten eines Template-VCs 
- Moven des entsprechenden Users
- Löschung des dyn VCs bei leerem VC

### WarnA
*Warn Administration*
- Bot zur Benachrichtigung der entsprechenden Administration
- Hat Anbindungen zu Logs etc. von den obigen Modulen

### PlottR
*You're a statistic Harry*
- Bot zur Analyse der Daten von Guardian und weiteren Informationen
- I/O; VC usage; TC(Text Channel) usage; User activity; common visitor time; VC duration etc.

