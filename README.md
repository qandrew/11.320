# 11.320
code for my final project (EcoCycle). 

This is a simple demo of a client-server interaction for the EcoCycel bin. The client (a bin) can send put and get requests to a server (the central database). This uses a TCP connection in which the client runs RPC commands on the server

## How to run
* you need go installed on your computer
* run the following commands to setup the environment
~~~~
git clone https://github.com/qandrew/11.320.git
cd 11.320
export GOPATH=$PWD
export PATH=$PATH:$GOPATH/bin
cd $GOPATH/src/client
go install client
cd $GOPATH/src/server
go install server
~~~~
* to run the client, open a terminal and run
~~~~
cd $GOPATH/bin
client
~~~~

* to run the server, open a terminal and run
~~~~
cd $GOPATH/bin
server
~~~~
