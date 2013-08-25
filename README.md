gradle-aspectj
==============

Gradle plugin for insuring ApectJ-driven compile time weaving

Completely based on the SpringSource's SpringSecurity Github repository and their Gradle build,
but embedded in a plugin to avoid gradle compilation.

This plugin ensures compilation is done via iajc compiler instead of the default one, by
altering the default java compilation worklow.

Usage is simple:

```groovy
apply plugin: 'java'
apply plugin: 'aspectj'
```
