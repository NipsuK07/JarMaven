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
Extension Pack for Java
Maven for Java
Debugger for Java

Seuraavaksi Luo Maven projekti.
Kun projekti on luotu klikkaa mvn ja sitten package. Tämän Maven luo JAR tiedosto sinun servermaster kansioon.
