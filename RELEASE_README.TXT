
Please use tasks the following to sign and upload artifacts to the sonatype staging:
  - ant stage-javadoc
  - ant stage-sources
  - ant stage-jar

You can find details how to release them in the document: https://docs.sonatype.org/display/Repository/Sonatype+OSS+Maven+Repository+Usage+Guide.

If it's required to install artifact to the local private maven repository only please use:
  - deploy.sh

