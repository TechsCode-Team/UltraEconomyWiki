# How to import our API with Maven
<br>

## Add this to your pom.xml
```xml
<repositories>
    <repository>
        <id>techscode</id>
        <url>https://repo.techscode.com/repository/maven-releases/</url>
    </repository>
</repositories>

<dependency>
    <groupId>me.TechsCode</groupId>
    <artifactId>UltraEconomyAPI</artifactId>
    <version>AnyPublicAvailableVersion</version>
</dependency>
```

Our Repository Manager houses all publicly available API versions, each of which
is linked to its corresponding, officially named release build of UltraEconomy.
[All public available Versions](https://repo.techscode.com/#browse/browse:maven-releases:me%2FTechsCode%2FUltraEconomyAPI)
