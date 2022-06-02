# quarkus-app-cds-bug Project

This shows that app-cds does not work if we use tests residing in src/integrationTest. The behaviour can be reproduced by invoking 

```./gradlew clean quarkusIntTest --info```

