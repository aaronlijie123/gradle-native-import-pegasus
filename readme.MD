How to reproduce the issue:
1. clone this repo
2. run `./gradlew build`
3. open the repo with intellij and run gradle sync command
4. go to `/server/.../FortunesResource.java` file and click `com.example.fortune.Fortune`. It would direct you to compiled class file instead of the java source file.