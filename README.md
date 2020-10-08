# Svar på frågor

1. Syftet med automatiserings-processens är att det ska gå snabbt och enkelt att sammanslå och komprimera filer,
istället för att det måste göras manuellt så sköts det automatiskt.

2. jag har använt gulp-clean-css, gulp-imagemin och browser-sync, Jag valde dem för att de var uppdaterade ganska nyligen och för att det
var lätt att hitta information om hur jag kunde använda dem.


3. Funktionerna startar genom att man skriver "gulp" i terminalen. 
Tasks:

**copyHTML:** Kopierar HTML till pub-katalogen.

**jsTask:** slår ihop och minifierar JavaScript-filer och lägger resultatet i main.js i pub-katalogen.

**imgTask:** minifierar bilder och kopierar resultatet till pub/images.

**'styles':** slår samman alla css-filer, minifierar och lägger resultatet i filen styles.css i pub/css. visar ändringar i browsern när
styles.css uppdateras/ändras om browsersync körs.

**watchTask:** startar browsersync som visar filerna från pub-katalogen i browsern, kollar efter ändringar i html, css, js och bildfiler, om filerna ändras
visar browsersync de ändringarna i browsern direkt när de sparas.

4. Jag har inte lagt till mer än det som var nödvändigt.
