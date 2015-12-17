# mamohr/centos-java
This is a simple docker image for Oracle Java 8 based on a centos 7 image.

# Supported tags and respective `Dockerfile` links

-	[`jdk8`, `latest` (*jdk8/Dockerfile*)](https://github.com/mamohr/docker-centos-java/blob/master/jdk8/Dockerfile)
-	[`jre8` (*jre8/Dockerfile*)](https://github.com/mamohr/docker-centos-java/blob/master/jre8/Dockerfile)

# Usage

You can use this image as a base image to install arbitrary java software in a Docker container. 
The JAVA_HOME environment variable will be set and java will be in the path.

Example run:

    docker run --rm mamohr/centos-java java -version

# License

View [license information](http://www.oracle.com/technetwork/java/javase/terms/license/index.html) for the software contained in this image.

# Issues

If you have any problems with or questions about this image, please contact me through a [GitHub issue](https://github.com/mamohr/docker-centos-java/issues).
