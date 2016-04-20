# maven-repo

A BioJava specific maven repository, for legacy BioJava releases.  All new releases are on `Maven Central` nowadays.

## How to add the legacy repository to your project's pom.xml

```xml
<repository>
    <id>biojava-legacy-repo</id>
    <name>BioJava's Git based legacy maven repo</name>
    <url>https://github.com/biojava/maven-repo/raw/master/</url>
</repository>
```

### How to add the most recent BioJava release to your project's pom.xml

Note: this is not hosted here, but on `Maven Central`


```xml
    <dependencies>
      <dependency>
        <groupId>org.biojava</groupId>
        <artifactId>biojava-core</artifactId>
        <version>4.2.0</version>
      </dependency>
      <!-- other biojava jars as needed -->
    </dependencies>
```
