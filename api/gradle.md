# How to import our API with Gradle
<br>

## Add this to your build.gradle
```groovy
repositories {
    maven {
        name = 'TechsCodeAPI'
        url = 'https://repo.techscode.com/repository/maven-releases/'
        }
}
dependencies {
    compileOnly 'me.TechsCode:UltraEconomyAPI:AnyPublicAvailableAPIVersion'
}
```

Our Repository Manager houses all publicly available API versions, each of which
is linked to its corresponding, officially named release build of UltraEconomy.
View all public available [versions](https://repo.techscode.com/#browse/browse:maven-releases:me%2FTechsCode%2FUltraEconomyAPI)


