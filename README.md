# maven-angular-base

This images contains all the dependencies required to work with the
[yeoman-maven-plugin](https://github.com/trecloux/yeoman-maven-plugin). The
configuration has been kept minimal making this image useful only when having
an internet access without proxy. It is mostly an intermediate layer to save
build time of images depending on this one:
- [maven-angular](https://github.com/pbarnoux/maven-angular)

### Included software licence

This image ships with an Oracle JDK 8. By using this image, or any image
deriving from this one, you implicetely accept the [Oracle JDK software
licence](http://java.com/license).

In order to save space in the resulting image, sources and manual have been
removed. You can download them from [Oracle
website](http://www.oracle.com/technetwork/java/javase/downloads/index.html).
