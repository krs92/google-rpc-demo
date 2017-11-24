# google-rpc-demo

simple demo of google rpc client and server from scotch tutorial


Steps to start server

1) npm install 
2) npm install -g grpcli  // gRPC client cli
3) node index.js

Steps to start client

1) node client/index.js


Command to start RPC

grpcli -f proto/work_leave.proto --ip=127.0.0.1 --port=50050 -i