Clean
 & "C:\Users\estani002\Downloads\apache-maven-3.9.6-bin\apache-maven-3.9.6\bin\mvn.cmd" clean -f "c:\Users\estani002\Downloads\demo\demo\pom.xml"

Build
 & "C:\Users\estani002\Downloads\apache-maven-3.9.6-bin\apache-maven-3.9.6\bin\mvn.cmd" package assembly:single  -f "c:\Users\estani002\Downloads\demo\demo\pom.xml" -s settings.xml

Execure
cd .\target\
java -jar .\demo-1.0-SNAPSHOT-jar-with-dependencies.jar    