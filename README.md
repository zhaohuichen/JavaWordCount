# JavaWordCount
This project is the first Java WordCount example using spark 
it includes: 
    pom.xml
    src/
Check out and add to intellij, You can use Maven to compile it to a jar file: sparkjavawordcount-0.0.1-SNAPSHOT.jar

The way to run this in standalone spark: 
$SPARK_HOME/bin/spark-submit --class ai.celential.spark.JavaWordCount --master local[8] $PathToJar/sparkjavawordcount-0.0.1-SNAPSHOT.jar test.txt
