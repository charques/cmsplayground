# cmsplayground

https://documentation.bloomreach.com/14/trails/getting-started/get-started.html

Create project:
mvn org.apache.maven.plugins:maven-archetype-plugin:2.4:generate \
-DarchetypeRepository=https://maven.onehippo.com/maven2 \
-DarchetypeGroupId=org.onehippo.cms7 \
-DarchetypeArtifactId=hippo-project-archetype \
-DarchetypeVersion=14.1.0

Build your project:
mvn clean verify 

Run the project: mvn -Pcargo.run -Drepo.path=./storage

You can now access the CMS UI at http://localhost:8080/cms. The following user accounts are set up by default (username / password):
admin / admin
editor / editor
author / author

