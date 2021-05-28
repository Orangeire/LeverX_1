# LeverX_1
Tutorial how to create .jar file:

cd C:/LeverX/LeverX_1/LeverX_1/src/com/LeverX

javac Main.java

jar -cf Main.jar Main.class

Tutorial how to run the file:

javac Main.java

java -classpath . Main

The result will be: Hello, Yuriy!

Tutorial how to import a new lib: 

javac -d bin -classpath bin:libs/apache-commons.jar -sourcepath src src/com/LeverX/Main.java
