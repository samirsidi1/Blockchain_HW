# Blockchain_HW
Blockchain Homework
##Creating a Genesis Block
###Puppeth & Proof of Work

![](assets/README-84879cf5.png)
![](assets/README-117b4cd0.png)
![](assets/README-cf16b8bc.png)

##Import Dependencies MyCrypto ETH Wallet

![](assets/README-53d02bde.png)

##Configure Genesis Block (Chain ID 1234)

![](assets/README-e1c25a92.png)

##Export JSON FILE (Puppernet.Json)

![](assets/README-ac050911.png)

##Creating Nodes & Initializing JSON

###./geth account new --datadir node1
###./geth account new --datadir node2
###./geth init puppernet_config/puppernet.json --datadir node1
![](assets/README-5ab3a11a.png)
![](assets/README-e6addc28.png)
![](assets/README-5473fb3e.png)

##Bringing Blockchain to Life (Mining)
###./geth --datadir node 1 --mine --minerthread1
###./geth --datadir node 2 --bootnodes "enode" --port30304 --rpc
![](assets/README-93c2aeec.png)
###Ecode
![](assets/README-2c1a8084.png)

#Sending Transactions (Walet)
##Crypto Wallet
###Opening Crypto Wallet to Configure the ETH Testnet
![](assets/README-9ac26a86.png)

###Creating Puppernet ETH (Chain ID 1234)
![](assets/README-ed6986af.png)
![](assets/README-c4502121.png)

###Keystone File
![](assets/README-12a24c03.png)

###Transfer Funds
![](assets/README-1d9e9c32.png)

###Sending ETH
![](assets/README-14c01568.png)
