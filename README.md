# SQLite dialect for Hibernate 4.x

[![Build Status][1]][2]

With this dialect the Hibernate can use SQLite database.

Based on Hibernate 4.3.11.Final.

## Source
This code is based on SQLite dialect for Hibernate 5: <https://github.com/gwenn/sqlite-dialect>
Thanks @gwenn (original author) for the work.

## Maven repository

```xml
<dependency>
  <groupId>com.enigmabridge</groupId>
  <artifactId>hibernate4-sqlite-dialect</artifactId>
  <version>0.1.2</version>
</dependency>
```

## Gradle

```gradle
compile 'com.enigmabridge:hibernate4-sqlite-dialect:0.1.2'
```

## Hibernate configuration
Set the dialect property `hibernate.dialect` to the class name `com.enigmabridge.hibernate.dialect.SQLiteDialect`

### Hibernate
`hibernate.properties`
```properties
hibernate.dialect = com.enigmabridge.hibernate.dialect.SQLiteDialect
```

### Spring boot
`application.properties`
```properties
spring.jpa.properties.hibernate.dialect = com.enigmabridge.hibernate.dialect.SQLiteDialect
```

## Contributing

Pull requests and bug reports are welcome

[1]: https://travis-ci.org/EnigmaBridge/hibernate4-sqlite-dialect.svg
[2]: https://travis-ci.org/EnigmaBridge/hibernate4-sqlite-dialect

