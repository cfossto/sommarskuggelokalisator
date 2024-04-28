# Sommarskuggelokalisator 3000
Det här repot är till för att göra en manick som spårar Sommarskuggan. Under sommaren befinner den ju sig i Beijers Park.. Men övriga året? Vår manick vet nog..

# Vad är det som händer här?
Detta är den öppna källkoden till ett privat hårdvaruprojekt i syfte att göra en Sommarskuggelokalisator 3000, en manick som försöker lokalisera Sommarskuggan.
Under SVTs sommarlov så befinner ju sig Sommarskuggan runt Beijers Park i Malmö, så min manick kommer att peka mot Malmö under den tiden och ge en "kompass" åt det hållet.
Om man dessutom kommer närmare och närmare Beijers Park, så lyser dioder från Rött till Gult och Grönt beroende på hur nära man är.
Övriga tider på året så är det ju lite oklart vart Sommarskuggan befinner sig, men det får man ju reda på via manicken om den är nära eller inte..

## Teknisk översikt
### Hårdvara
Hårdvara kommer initalt bestå av en 3D-printad makapär som har en liten LED-skärm för kompassen och 8 st LED-lampor som lyser beroende på
hur nära Sommarskuggan man befinner sig. Makapären drivs initalt av 9V batteri, men ska försöka dras ner till cirka 5V. Bild kommer vid tillfälle.

### Mjukvara
Program skrivet i C++ som främst interagerar mot hårdvaran. Sköter kontroll av datum (för villkoret om position under sommaren) och
funktionerna kring positionering (magisk triangulering ...) av Sommarskuggan. Introducerar dagligen ny sommarskugge-position utifrån en slumpgenerator.

## Disclaimer
Jag äger inte varumärket till Sommarskuggan men gör detta som ett kul - privat - projekt till mina döttrar. Jag tänker inte använda källkoden kommersiellt för egen vinning. Koden kommer enbart att användas för privat experiment med tema taget från Sommarskuggan. Sommarskuggan ägs (enligt min kännedom) av SVT och Tina Mackic.

Använd inte denna källkoden för kommersiellt bruk, men bygg gärna på som ett open source-projekt. Skulle SVT eller Tina Mackic vilja samarbeta med en "closed source"-version av detta projekt, hör gärna av er till "info (at) fossto.com". Vill ni att jag tar ner koden, hör gärna av er så löser jag det. Inte på något sätt vill jag för egen vinnings skull göra ekonomisk nytta på projektet. Jag vill bara göra min döttrar glada och sporra deras leklust och fantasi. Inga andra motiv finns.

## Hälsning
Mackic, du är bäst.
