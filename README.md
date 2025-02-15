# ecdna-coamp
Graph visualizer to view genes coamplified on ecDNA focal amplifications. 

## Neo4j Download Instructions
For macOS users, enter the following commands to set up Neo4j Community Edition:

Download and unzip the tar file:<br>
```curl -O -C - http://dist.neo4j.org/neo4j-community-5.12.0-unix.tar.gz```<br>
```tar -xvzf neo4j-community-5.12.0-unix.tar.gz```<br>

Start neo4j with the console command:<br>
```cd neo4j-community-5.12.0```<br>
```bin/neo4j console```<br>

Go to http://localhost:7474/browser/ and change the auth settings. By default, both user and password are 'neo4j'. Keep user as 'neo4j' and change password to 'password'.

The environment is now set up. Ensure that neo4j is running before querying the graph.


> Alternatively, go to https://neo4j.com/deployment-center/, then download the rpm file for the latest Community Edition under the section titled 'Graph Database Self-Managed'. Further instructions are available upon clicking Download. Note that this method has not been tested by our team.

