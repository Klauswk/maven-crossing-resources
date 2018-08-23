THIS IS A PROJECT EXAMPLE USING MAVEN TO COPY THE RESOURCES OF A PARENT PROJECT INSIDE ANOTHER PROJECT

WAS COPY FROM THE FOLLOWING TUTORIAL

 https://blog.sonatype.com/2008/04/how-to-share-resources-across-projects-in-maven/

FOR BUILD, USE `mvn clean package`

 IT CAN BE BUILD USING GRADLE TOO, USE

 `./gradlew :main-project-one:fatjar` TO BUILD A FAT JAR AND `java -jar ./main-project-one/build/libs/main-project-one-all-0.0.1-SNAPSHOT.jar` FOR RUN