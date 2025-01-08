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

<div id="version-container">
  <button class="version-button" style="background-color: #007bff; color: white; border: none; padding: 5px 10px; border-radius: 3px; font-size: 14px; cursor: pointer;">
    Fetching...
  </button>
</div>

<script>
  async function fetchLatestVersion() {
    try {
      const response = await fetch('https://repo.techscode.com/service/rest/v1/search?repository=techscode-apis&group=me.TechsCode&name=UltraEconomyAPI');
      const data = await response.json();
      const items = data.items;
      const latestVersion = items[0].version; // Assuming the first item is the latest
      document.querySelector('.version-button').textContent = latestVersion;
    } catch (error) {
      document.querySelector('.version-button').textContent = 'Error fetching version';
      console.error('Error fetching version:', error);
    }
  }

  fetchLatestVersion();
</script>

## Getting the API Instance

To obtain an instance of the Ultra Economy API, use the following method:

```java
UltraEconomyAPI api = UltraEconomy.getAPI();
```

This instance provides various methods for managing economic features, which are explained in detail on the other pages of this API documentation.
