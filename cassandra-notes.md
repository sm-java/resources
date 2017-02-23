#Cassandra Notes

###1. cqlsh settings 
   to connect from a remote machine change the rpc_address and start_rpc in cassandra.yml to the IP address of the machine and true 
  respectively.
  
  ```
    #Cassandra.yml
    rpc_address: 10.X.X.X
    start_rpc: true
  ```
###2. Bulk uploads
[Yahoo Quotes](http://www.datastax.com/dev/blog/using-the-cassandra-bulk-loader-updated)

###3. Running Cassadra with Pelops
[Pelops](https://ria101.wordpress.com/2010/06/11/pelops-the-beautiful-cassandra-database-client-for-java/)
