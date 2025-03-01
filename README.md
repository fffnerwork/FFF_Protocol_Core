
![FFF](https://www.fff.network/git.png)  


### What is FFF?
FFF  is a decentralized blockchain based on ***IPFS/RIPPLE***, which integrates lua virtual machine-based smart contracts. It is also a software platform designed to help coordinate voluntary free market operations amongst a set of social actors.

Replicas of the state machine are kept consistent using the Result Delegated Pows distributed consensus protocol.

FFF is making efforts to build up a high-performance decentralized enterprise blockchain platform to develop business blockchain applications, to eliminate cognitive fear of enterprises facing blockchain technology or corresponding applications, and to make the blockchain visualized and configurable.

For more information about FFF, please read the whitepaper:


[FFF White Paper ](https://fff-development.gitbook.io/a-white-paper-fff/fff)  
 
## Supported Operating Systems  

>1.Ubuntu 18.04 / 20.10

>2.Fedora 27 / 25


```
sudo apt-get update
sudo apt-get install -y build-essential libtool autotools-dev automake pkg-config libssl-dev git python python-pip
sudo apt-get install -y libdb5.3-dev libdb5.3++-dev
sudo pip install pathlib2

```

#### Clone FFF_Core

```
https://github.com/fff-source/FFF_Protocol_Core.git
```
#### Prepare to download  V8
You can use the title of pre-built and Google V8 JavaScript engine binary file download and Linux - V8. Tar expansion.


```
cd FFF_core
set FFF_HOME=$(pwd)
mkdir v8build
cd v8build
```











## Public resources

 
name  | domain   | port
 ---- | ----- | ------  
developers  | nodedev.fff.network | 8561 
faucet  | faucet.fff.network | 8561 
provids  | provids.fff.network | 8562 
enterprise(union)  | enterprise.fff.network | 8550 
 

## How to use the RPC API

[RPC API](https://app.gitbook.com/@fff-development/)   

## License

FFF Core is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.



## Translations


Changes to translations as well as new translations can be submitted to FFF Transifex page.

Translations are periodically pulled from Transifex and merged into the git repository. See the translation process for details on how this works.

Important: We do not accept translation changes as GitHub pull requests because the next pull from Transifex would automatically overwrite them again. 
