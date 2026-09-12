# lab1-webbplats
Detta projekt är skapat som en del av min utbildning för att öva på grundläggande webbutveckling. Innehållet i webbplatsen är baserat på ett av mina favoritresmål.

## Tekniker
Dessa tekniker har använts i projektet:
- HTML5
- CSS

## Publicerade versioner

Github Pages: https://miahog.github.io/lab1-webbplats/
Netlify: https://dapper-mooncake-cd3bb6.netlify.app/

## Svar på frågor om git:

### Vad är skillnaden mellan git add och git commit?
- Genom git add så sparas ändringar enbart i staging området medans git commit sparar ändringar till en ny version i projektet. 

### Varför använder man branches istället för att jobba direkt i main?
- Man vill sällan riskera att förstöra main (huvudversionen). Därför kan man testa och göra ändringar i branches och se så att de fungerar innan man ändrar i main.

### Vad händer rent praktiskt när man gör en merge?
Man kopplar ihop ändringar från en branch till en annan branch. Det kan dock uppstå konflikter som behöver lösas manuellt, detta kan bero på ändringar av t.ex. samma kodrad. 

### Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
När man publicerar en webbplats direkt på Netlify så blir den synlig för besökare på internet. När man pushar till Github så laddar man upp kod och historik till sitt Github repo.

### Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
Då kan man göra så att man skapar en .gitignore-fil och då kommer git att ignorera just den mappen/filen. 