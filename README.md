# mstor
Mbox parser of ePADD<br>

Clone of mstor (http://sourceforge.net/projects/mstor/files/mstor/0.9.13/) with fixes and improvements.

Removed the dependency of pom.xml on non-existent parent-pom.
mvn -DskipTests=true should work.

TODO
Some of the system properties like disable cache buffers are not even used, fix this.
Should also fix wrong tests.