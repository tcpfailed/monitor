# monitor
Custom Nload Copy Network Monitor For Purely Traffic Made By TCP

# SETUP

1. apt-get update
2. apt install golang-go 
3. apt install git
4. apt install screen
5. git clone https://github.com/tcpfailed/monitor
6. cd monitor
7. go mod init monitor or go mod init
8. go mod tidy 
9. go build nload.go
10. chmod 777 * (only if compiling)

# RUNNING THE SCRIPT

1. (manual non compiled) go run nload.go [optional parameters: -t timeout]
2. (manual compiled) go run ./nload [optional parameters: -t timeout]
3. (auto compiled) screen go run ./nload [optional parameters: -t timeout]
4. (auto non compiled) screen go run nload.go [optional parameters: -t timeout]

# ADDITIONAL
if it doesnt fit your screen size edit line 21 : GRAPH_HEIGHT = 20 and replace the number to your needed height. or just resize your ssh terminal

# CHANGES
