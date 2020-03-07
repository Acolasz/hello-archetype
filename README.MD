[Creating-archetypes](https://maven.apache.org/guides/mini/guide-creating-archetypes.html)

# Generate archetype command

mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-archetype -DarchetypeVersion=1.4 -DgroupId=hu.kukutyin.archetype -DartifactId=test -Dversion=1.0.0-SNAPSHOT

# Create dummy-application
mvn archetype:generate -DarchetypeGroupId=hu.kukutyin.archetype -DarchetypeArtifactId=test -DarchetypeVersion=1.0.0-SNAPSHOT -DgroupId=hu.kukutyin.app -DartifactId=run-test -Dversion=0.0.1
