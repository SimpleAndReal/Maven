https://maven.apache.org/guides/getting-started/index.html



mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.5 -DinteractiveMode=false



mvn compile
mvn package
java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App