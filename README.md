Clean
 & "C:\Users\estani002\Downloads\apache-maven-3.9.6-bin\apache-maven-3.9.6\bin\mvn.cmd" clean -f "pom.xml"

Build
 & "C:\Users\estani002\Downloads\apache-maven-3.9.6-bin\apache-maven-3.9.6\bin\mvn.cmd" package assembly:single  -f "pom.xml" -s settings.xml

Execure
cd .\target\
java -jar .\demo-1.0-SNAPSHOT-jar-with-dependencies.jar    