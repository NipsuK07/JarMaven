# JarMaven
## Ohje Maven-projektin luomiseen ja JAR-tiedoston tekemiseen

Lataa Java JDK 13+ versio. Asennus pitää tehdä Oraclessa, koska projekti on tehty vanhemmalla Java versiolla jonka päivitys on loppunut Maaliskuussa 2020. Uudempaan versioon päivittäminen saattaisi aiheuttaa ongelmia.
https://www.oracle.com/java/technologies/javase/jdk13-archive-downloads.html

Kun olet asentanut Javan tarkista versio kirjoittamalla Komentokehotteeseen: `java -version`.
Versionumeron tulisi näkyä `("13.X.XX")`.
Lataa Maven sovellus ja latauksen jälkeen sen pitäisi näkyä Visual Studio Codessa automaattisesti.
Seuraavaksi Luo Maven projekti.
Kun projekti on luotu klikkaa mvn ja sitten package. Tämän Maven luo JAR tiedosto sinun servermaster kansioon.
