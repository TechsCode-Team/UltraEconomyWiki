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
    <version>2.6.4</version>
</dependency>
```

Our `Repository Manager` houses all publicly available API versions, each of which
is linked to its corresponding, officially named release build of UltraEconomy.
**View all public available** [**versions**](https://repo.techscode.com/#browse/browse:maven-releases:me%2FTechsCode%2FUltraEconomyApi)

<br>

# Recomendation
When using methods of our API in the startup of your plugin you will need to add `UltraEconomy` to your softdepend or depend section in your plugin.yml

<br>

## Table of contents
- [Instance](./instance) - Getting the API instance

<br>

