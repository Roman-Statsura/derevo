# derevo
Multiple instance derivations inside a single macro annotation

```
val version = "0.9.0"

"org.manatki" %% "derevo-core" % version  
"org.manatki" %% "derevo-cats" % version  
"org.manatki" %% "derevo-circe" % version  
"org.manatki" %% "derevo-ciris" % version  
"org.manatki" %% "derevo-tethys" % version  
"org.manatki" %% "derevo-tschema" % version  
"org.manatki" %% "derevo-rmongo" % version  
"org.manatki" %% "derevo-cats-tagless" % version  
"org.manatki" %% "derevo-pureconfig" % version
```

Requires ["paradise"](https://github.com/scalamacros/paradise) for scala older than "2.13" and "-Ymacro-annotations" scalac option for scala "2.13".
