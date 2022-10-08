# How to gradle
## gradle.properties

To add, modify, delete variables accessible from the /build.gradle open the /gradle.properties file and do what you want with the variables.

> To add a new variable with the name date and 01:01:1971 as a value in the gradle.properties, append date="01:01:1971" to it.

From the build.gradle folder the variables are accessible as a map of properties, you can access the values using **prop["my_property"]**.

> ex:   
> build.gradle -> print prop["date"]   
> output -> 01:01:1971

# How to build the project

Using the command line, simply go in the root of the project and enter *./gradlew build*