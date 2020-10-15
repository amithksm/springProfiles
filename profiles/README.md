# springProfiles
Understanding Spring Profiles - application.properties

Running the code (linux)

Build the project
$ ./gradlew clean build

Go to the jar location
$ cd build/libs
Execute the jar
$ java -jar -Dspring.profiles.active=test profile-0.0.1-SNAPSHOT.jar
View the output in browser
$ Goto http://localhost:8181

Try with different profiles and observe the output
$ java -jar -Dspring.profiles.active=dev profile-0.0.1-SNAPSHOT.jar
$ java -jar profile-0.0.1-SNAPSHOT.jar
