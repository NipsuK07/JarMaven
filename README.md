# HandLeVR 
## Ohje Maven-projektin luomiseen ja JAR-tiedoston tekemiseen

### 1. Lataa Java JDK 13+ versio.

Asennus pitää tehdä Oraclessa, koska projekti on tehty vanhemmalla Java versiolla jonka päivitys on loppunut Maaliskuussa 2020. Uudempaan versioon päivittäminen saattaisi aiheuttaa ongelmia.
https://www.oracle.com/java/technologies/javase/jdk13-archive-downloads.html

Kun olet asentanut Javan tarkista versio kirjoittamalla Komentokehotteeseen: `java -version`.
Versionumeron tulisi näkyä `("13.X.XX")`.

### 2. Asenna Apache Maven

Lataa Maven sovellus `https://maven.apache.org/download.cgi`. Kun olet ladannut sovelluksen, pura ladattu paketti.
#### Lisää Maven ympäristömuuttujiin (Windows).
1. Avaa Järjestelmäasetukset ja valitse Ympäristömuuttujat.
2. Lisää uusi muuttuja:
   Nimi: `MAVEN_HOME`
   Laita arvoksi sijainti johon purit ladatun maven paketin.
3. Lisää `;%MAVEN_HOME%\bin` polkuun `Path`.

### 3. Visual Studio Code -valmistelut  
Asenna VS Code: `https://code.visualstudio.com/`.

Kun VS Code on asennettu lisää seuraavat lisäosat:
1. Extension Pack for Java
2. Maven for Java
3. Debugger for Java

Kun Maven on asennettu oikein, sen pitäisi näkyä automaattisesti vasemman laidan valikossa VS Codessa (“Maven Projects”).

### 4. Luo Maven projekti klikkaamalla `+` näppäintä. Tämän jälkeen Maven luo .jar tiedoston kansioosi.

### 5. Kopioi .jar tiedosto muistitikulle ja siirrä se RasberryPi:lle.

Käynnistä .jar tiedosto Terminalissa ja kirjoita komento `java -jar MyProgram.jar`. (Myprogram kohtaan tiedoston nimi.)
