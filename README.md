# connector-externalGroovyScript
Description : Update an external groovy script without recompiling the process

Author : Frederic KREBS

Bonita BPM version : 6.3.3

##Objectives : Execute an external groovy script
You can edit the script without recompiling neither redeploying the process on the server. 
Use as a Form transiant data, it allows you to edit the script externaly and refresh the form or start a new process instance to see the result without recompiling the process 

##Connector Parameter : 
	filePath : the full file path to the script
	inputMap : a java.util.Map variable to pass data to the script
##Connector Output : 
	result : Java Object

##Installation and usage:
* copie the script file in your hardrive
* In the process, change the connector file path
* Execute the process
* Go to step 1 form
* Change the script and save the script
* Refresh your navigator
