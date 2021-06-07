NumberUtil
==========

See LICENSE for this software's licensing terms.

This project is named NumberUtil in case I broaden its scope in the future, but for now it only applies to BigDecimal.

I don't like using BigDecimal.compareTo, so I created public static methods for the boolean comparison operators.


# Building

This project is known to build on Gradle 7.0.

1.  Get [BuildScripts](https://github.com/kloverde/BuildScripts)
3.  Set `buildScriptsDir` (the path to BuildScripts) in gradle.properties
4.  Set `builtBy` in gradle.properties
5.  Run `gradle build`
