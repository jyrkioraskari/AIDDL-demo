You may need to install Maven Scala and add it to the path.
https://www.scala-lang.org/download/

To Compile (in this directory=:
mvn scala:compile


Run this with:

mvn scala:run -DmainClass=de.aachen.rwth.ip.Main


Package:
mvn clean package

java -jar target\aiddl-qtest-scala-0.0.1-jar-with-dependencies.jar