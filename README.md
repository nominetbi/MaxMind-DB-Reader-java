# MaxMind DB Reader #

## Description ##

This is a fork of the 1.2.3 Java API for reading MaxMind DB files. 
It uses jackson 2.6.5 for compatability with Spark 2.2.0

MaxMind DB is a binary file format that stores data indexed by IP 
address subnets (IPv4 or IPv6).

see https://github.com/maxmind/MaxMind-DB-Reader-java for the 
original project the fork has been taken from

## Installation ##

### Maven ###

Installation is currently via building from source and adding
the jar file to the local maven installation

The following dependency can then be added to your pom.xml:

```xml
    <dependency>
        <groupId>uk.nominet</groupId>
        <artifactId>maxmind-db</artifactId>
        <version>1.2.3-jackson-2.6.5</version>
    </dependency>
```

## Copyright and License ##

Original software is Copyright (c) 2014 by MaxMind, Inc.

This is free software, licensed under the Apache License, Version 2.0.
