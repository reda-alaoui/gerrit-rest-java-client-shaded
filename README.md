[![Maven Central Latest](https://img.shields.io/maven-central/v/me.redaalaoui.gerrit_rest_java_client/gerrit-rest-java-client-shaded.svg)](https://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22me.redaalaoui.gerrit_rest_java_client%22%20AND%20a%3A%22gerrit-rest-java-client-shaded%22)

# gerrit-rest-java-client but shaded

This exports https://github.com/uwolfer/gerrit-rest-java-client by performing the following package relocations:
* `com.urswolfer.gerrit.client.rest` -> `me.redaalaoui.gerrit_rest_java_client.rest`
* `com.google` -> `me.redaalaoui.gerrit_rest_java_client.thirdparty.com.google`
