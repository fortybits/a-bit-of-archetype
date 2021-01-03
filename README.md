# FortyBits

Repository for an archetype to be followed across Maven based Java repositories for FortyBits

1. Build the project on the local using ```mvn clean install```
2. Execute the following command with varied groupId and artifactId to create a project further:

       mvn archetype:generate -DarchetypeGroupId=edu.forty.bits -DarchetypeArtifactId=a-bit-of-archetype -DarchetypeVersion=1.0.0-SNAPSHOT -DgroupId=edu.forty.bits -DartifactId=a-bit-of-sample -Dversion=1.0.0-SNAPSHOT