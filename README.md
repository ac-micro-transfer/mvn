# Gradle dependency

- Use repository of snapshots

```groovy
repositories {
  maven {
    url "https://raw.githubusercontent.com/ac-micro-transfer/mvn/master/repository/snapshots"
  }
}
```

- Use repository of releases

```groovy
repositories {
  maven {
    url "https://raw.githubusercontent.com/ac-micro-transfer/mvn/master/repository/releases"
  }
}
```

# Maven dependency

- Use repository of snapshots

  ```xml
  <repositories>
  <repository>
    <id>ac-maven</id>
    <url>https://raw.githubusercontent.com/ac-micro-transfer/mvn/master/repository/snapshots</url>
  </repository>
  </repositories>
  ```

- Use repository of releases

  ```xml
  <repositories>
  <repository>
    <id>ac-maven</id>
    <url>https://raw.githubusercontent.com/ac-micro-transfer/mvn/master/repository/releases</url>
  </repository>
  </repositories>
  ```
