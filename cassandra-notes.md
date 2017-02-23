#Cassandra Notes

###1. cqlsh settings 
   to connect from a remote machine change the rpc_address and start_rpc in cassandra.yml to the IP address of the machine and true 
  respectively.
  
  ```
    #Cassandra.yml
    rpc_address: 10.X.X.X
    start_rpc: true
  ```
