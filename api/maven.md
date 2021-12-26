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
    <version>1.0.0</version>
</dependency>
```