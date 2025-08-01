# Mnemonic module

## Maven [![Maven Central][maven-central-svg]][maven-central]

```xml
<dependency>
    <groupId>io.github.neodix42</groupId>
    <artifactId>mnemonic</artifactId>
    <version>1.0.0</version>
</dependency>
```

## Jitpack

```xml
<dependency>
    <groupId>io.github.neodix42.ton4j</groupId>
    <artifactId>mnemonic</artifactId>
    <version>1.0.0</version>
</dependency>
```

## Usage example

```java
List<String> mnemonic=Mnemonic.generate(24,pwd);
String mnemonicPhrase=String.join(" ",mnemonic);

//result
<<mnemonicPhrase containing 24 random words>>
```

More examples on how to construct [Mnemonic](../mnemonic/src/main/java/org/ton/ton4j/mnemonic/Mnemonic.java) can be
found in [TestMnemonic](../mnemonic/src/test/java/org/ton/ton4j/mnemonic/TestMnemonic.java) class.

[maven-central-svg]: https://img.shields.io/maven-central/v/io.github.neodix42/mnemonic

[maven-central]: https://mvnrepository.com/artifact/io.github.neodix42/mnemonic

[ton-svg]: https://img.shields.io/badge/Based%20on-TON-blue

[ton]: https://ton.org