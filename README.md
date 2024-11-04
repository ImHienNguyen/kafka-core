Run command to publish Java Artifact to Maven Local:

`./gradlew publishToMavenLocal`


### Prerequisite:
Add mavenLocal to your gradle repositories:

```
repositories {
    mavenLocal() 
    ....
}
```

Add gradle dependency to your project:

`implementation 'com.imhiennguyen.ws:core:0.0.4-SNAPSHOT'`
