## Spark_Structured_Streaming

####To get started run the below command to start apache zeppelin at localhost and spin up the container
* sh ./start_zeppelin.sh

####Open the below URL in your browser to access zeppelin at port 8082
* http://0.0.0.0:8082

####Import pre-created notebooks in the notebooks_repository directory one by one using the Web UI.

####Access the notebooks in the notebook section of the Web UI.

####Open the tutorial notebooks.

####Open the log files in the /data/tutorial directory and observe the data to be ingested.

####Go through the code in the notebook and try executing each paragraph to load the file and start the stream.

####Once the stream has been started, try copying each of the log files from ./data/tutorial folder and place it in the ./data directory.Execute the output query every time a single log file is copied and observe the output for each output mode.

####To stop the apache zeppelin server and kill the container 
* sh ./stop_zeppelin.sh