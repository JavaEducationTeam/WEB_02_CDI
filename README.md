# WEB_02_CDI

## Fontos:
A tároló tartalma önnállóan nem használható! Használd még legalább a Basic_03-IO tárolót, alternatív szolgáltatás implementációklehetnek a Basic-04-Networking, Basic_05-JDBC tárolókban is.

## Hivatalos specifikáció
[jcp.org/pdf](https://jcp.org/aboutJava/communityprocess/final/jsr365/index.html)

## Maven
            <dependency>

                        <groupId>javax.enterprise </groupId>
            
                        <artifactId>cdi-api </artifactId>
            
                        <version>2.0 </version>
            
            </dependency>


## Osztály referencia
[@RequestScoped](https://docs.oracle.com/javaee/7/api/javax/enterprise/context/RequestScoped.html)

[@SessionScoped](https://docs.oracle.com/javaee/7/api/javax/enterprise/context/SessionScoped.html)

[@AppalicationScoped](https://docs.oracle.com/javaee/7/api/javax/enterprise/context/c.html)

[@Inject](https://docs.oracle.com/javaee/7/api/index.html?javax/enterprise/context/ApplicationScoped.html)

## Mintapélda
[HeroServiceCDI](https://raw.githubusercontent.com/JavaEducationTeam/WEB_02_CDI/master/heroesofempires/webapplication/src/main/java/hu/javagladiator/app/heroesofempires/webapplication/HeroServiceCDI.java)  Automatikusan "létrejövő" példány. Csak az annotáció miatt szükséges.

[HeroServlet](https://raw.githubusercontent.com/JavaEducationTeam/WEB_02_CDI/master/heroesofempires/webapplication/src/main/java/hu/javagladiator/app/heroesofempires/webapplication/HeroServlet.java) Példány felhasználás.
