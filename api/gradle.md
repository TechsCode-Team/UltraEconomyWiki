# How to import our API with Gradle
<br>

## Add this to your build.gradle
```gradle
repositories {
    maven {
        name = 'TechsCodeAPI'
        url = 'https://repo.techscode.com/repository/maven-releases/'
        }
}
dependencies {
    compileOnly 'me.TechsCode:UltraEconomyAPI:1.0.0'
}
```