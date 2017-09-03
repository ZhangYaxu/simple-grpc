# simple-grpc

Demo code that highlights gRPC based communication between client and server.

Assuming you are at the top of the project tree 'simple-grpc'

There are three directories
```
proto
client
server
```

##### proto
the service is expressed as a 'proto' file
leave.proto

##### server
run the server as `node server` or `node server/index.js`

##### client 
there are two clients, implemented in 'node' and 'python 3.x' respectively.

run the 'node' client as
`node client/node/` or `node client/node/index.js'

run the 'python' client as
```
cd client/python
./do_1_gen.sh
./do_2_run.sh
```


