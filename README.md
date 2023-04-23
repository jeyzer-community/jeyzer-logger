# jeyzer-logger
Jeyzer logger is a derived version of the Java 8 util logging (JUL) implementation.

It has been derived to remove the hard dependency on the java.util.logging.manager system property which is set only once by the JVM.
This permits to be independent from JUL and leave it fully under control of any monitored application (like JBoss for example).

It is Java 7 compatible. 


Build instructions
------------------

Jeyzer Logger project can be built with Maven.

Under the current directory, execute :

> mvn clean package

The jeyzer-all project is responsible for calling the current project build.


License
-------

Licensed under the [GNU General Public License (GPL), Version 2.0](https://github.com/openjdk/jdk/blob/jdk8-b120/LICENSE)

