# Ultra Economy API Documentation

## Introduction

The Ultra Economy API allows you to integrate the economy system and other features of Ultra Economy into your plugin. This documentations provides information on how to import the API library, find the latest version, obtain the API instance, and how to use the API instance.

## Importing the API

We provide importation of the API’s using our personally hosted library repository manager. This allows you to import the API using Maven and Gradle for easy access around the world.
<br>

To add the Ultra Economy API library to your project you need to add the following information to your `package.xml`.

To use the Ultra Economy API, add the following repository and dependency information to your project’s build file:

```xml
<repositories>
    <repository>
        <id>techscode</id>
        <url>https://repo.techscode.com/repository/techscode-apis/</url>
    </repository>
</repositories>

<dependency>
    <groupId>me.TechsCode</groupId>
    <artifactId>UltraEconomyAPI</artifactId>
    <version>VERSION</version>
    <scope>provided</scope>
</dependency>
```

Make sure to replace `VERSION` with the desired version. You can browse available versions **[here](https://repo.techscode.com/#browse/browse:techscode-apis:me%2FTechsCode%2FUltraEconomyAPI)**.

## Getting the API Instance

To obtain an instance of the Ultra Economy API, use the following method:

```java
UltraEconomyAPI api = UltraEconomy.getAPI();
```

This instance provides various methods for managing economic features, which are explained in detail on the other pages of this API documentation.