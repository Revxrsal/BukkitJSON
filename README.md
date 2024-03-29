# Notice
This repository has been officially moved to https://github.com/moltenjson/BukkitJSON and hence been deprecated in favor of it. This repository will no longer be receiving updates and will be archived.
------

# BukkitJSON
BukkitJSON is a Bukkit plugin, which acts like an alternative to [SimpleJSON](https://www.github.com/ReflxctionDev/SimpleJSON). This allows developers to have SimpleJSON as a dependency without needing to embed it in the plugin JAR. It also allows multiple plugins that use BukkitJSON to have a relatively small JAR size, all through BukkitJSON.

# Developers
If you're a developer and would like to use BukkitJSON:

**[1]** Add it as a dependency to your **plugin.yml**:
`depend: [BukkitJSON]`

#### Maven:
**[2]** Add it to your **pom.xml**:

 ```xml
<repositories>
    <repository>
	    <id>jitpack.io</id>
	    <url>https://jitpack.io</url>
    </repository>
</repositories>
```

...and to your dependencies:
```xml
<dependency>
    <groupId>com.github.ReflxctionDev</groupId>
    <artifactId>BukkitJSON</artifactId>
    <version>VERSION</version>
    <scope>provided</scope>
</dependency>
```

#### Gradle
**[2]** Add this to your **build.gradle**:

```gradle
repositories {
    maven { url 'https://jitpack.io' }
}
```

...and to your dependencies:
```gradle
compile 'com.github.ReflxctionDev:BukkitJSON:VERSION'
```

#### JAR classpath
If you are not using any build system like Gradle or Maven, you can add BukkitJSON JAR to your classpath.

[Download latest JAR here](https://github.com/ReflxctionDev/BukkitJSON/releases/latest)

# Server Administrators
If you are a server owner/admin, and a plugin asked you to download BukkitJSON, simply drag and drop 
[the latest JAR](https://github.com/ReflxctionDev/BukkitJSON/releases/latest) to your **plugins** folder, and all should be good.


# Plugins that use BukkitJSON

* None!

*If your plugin uses BukkitJSON, feel free to open an issue requesting your plugin page to be added below.*
