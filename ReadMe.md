To execute the scenario one:

Navigate to scenarioone folder under Week-05, the JAVA code is available here.
Execute the program in the following way:

1.hadoop com.sun.tools.javac.Main WordCount.java
2.jar cf wc.jar WordCount*.class
3.hadoop jar wc.jar WordCount [Input location] [Output location]
4.hadoop fs -cat [Output File] | | sort -n -r -k2| head -n 10

To execute the scenario two:

Navigate to scenariotwo folder under Week-05, the JAVA code is available here.
Execute the program in the following way:

1.hadoop com.sun.tools.javac.Main WordCount2.java
2.jar cf wc2.jar WordCount*.class
3.hadoop jar wc2.jar WordCount2 [Input location] [Output location]
4.hadoop fs -cat [Output File] | | sort -n -r -k2| head -n 10

To execute the scenario three:

Navigate to scenariothree folder under Week-05, the JAVA code is available here.
Execute the program in the following way:

1.hadoop com.sun.tools.javac.Main WordCount.java
2.jar cf wc.jar WordCount*.class
3.hadoop jar wc.jar WordCount [Input location] [Output location]
4.hadoop fs -cat [Output File] | | sort -n -r -k2| head -n 10

To execute the scenario four:

Navigate to scenariofour folder under Week-05, the JAVA code is available here.
The pattern.txt should be placed within the pattern folder under week-05.
Execute the program in the following way:

1.hadoop com.sun.tools.javac.Main WordCount.java
2.jar cf wc.jar WordCount*.class
3.hadoop jar wc.jar WordCount2 -Dwordcount.case.sensitive=true [Input location] [Output location] -skip [pattern.txt]
4.hadoop fs -cat [Output File] | | sort -n -r -k2| head -n 10


