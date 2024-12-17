# Maven project for GraphHopper jsprit example

Some changes to the pom and code were necessary to make this work because the xml writer was removed from the original project for some reason.

## Usage

```cmd
mvn clean install
mvn exec:java
```

The output should be solution details on stdout as well as a GraphStream picture.
