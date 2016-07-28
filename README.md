
1. Start with "sbt" in the folder 
 
2. When showing up the prompt ">" , type "reStart"
 
3. If not have jar file from "ATMS-Project-Spark", make a jar file using below command.
    sbt -Dscala.version=2.10.4 package

4. Next, Open new Terminal and input command below (jar path is at "ATMS-Project-Spark" Project)
    curl --data-binary @target/scala-2.10/atms_proj_2.10-1.0.jar localhost:8090/jars/atms

5. Open "ATMS-Browser" and use it.


- ref job-server : https://github.com/spark-jobserver/spark-jobserver
