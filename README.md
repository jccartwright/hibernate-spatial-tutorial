# hibernate-spatial-tutorial
hibernate spatial [tutorial](http://www.hibernatespatial.org/documentation/02-Tutorial/01-tutorial4/) adapted from hibernatespatial.org

run with statements like:
* mvn exec:java -Dexec.mainClass="event.EventManager" -Dexec.args="store POINT(10 5)"
* mvn exec:java -Dexec.mainClass="event.EventManager" -Dexec.args="find 'POLYGON((1 1,20 1,20 20,1 20,1 1))'"
