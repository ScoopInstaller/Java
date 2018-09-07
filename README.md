# scoop-java

A bucket for [Scoop](http://scoop.sh), for [Oracle Java](http://www.oracle.com/technetwork/java/javase/overview/index.html), [OpenJDK](http://openjdk.java.net), [Zulu](https://www.azul.com/products/zulu-and-zulu-enterprise), [ojdkbuild](https://github.com/ojdkbuild/ojdkbuild) and [AdoptOpenJDK](https://adoptopenjdk.net).

To make it easy to install apps from this bucket, run
    `scoop bucket add java`

For more information, read the [wiki](https://github.com/lukesampson/scoop/wiki/Java).

## News

### [2018-09-06] fatal: refusing to merge unrelated histories
Due to a problem with the git history, the master branch had to be replaced. If you see the message *fatal: refusing to merge unrelated histories* when updating scoop, remove and re-add the java bucket:
```
PS C:> scoop bucket rm java
PS C:> scoop bucket add java
```
See issue [#16](https://github.com/se35710/scoop-java/issues/16) for mote information.
