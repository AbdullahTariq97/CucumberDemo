https://www.baeldung.com/java-cucumber-gradle

If the runner class and the glue class are not in the same directory but share the same parent package then
The glue should be defined as the name of the parent package common to both the runner class and the glue class
Without doing this the tests will fail, it will complain that steps are undefined

If the runner class and the glue class are put in the same directory then the glue property does not need to be defined
