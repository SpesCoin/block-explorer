# SpesCoin-Blockchain-Explorer
Block explorer for SpesCoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon spescoind. It should be accessible from the Internet. Run spescoind with open port as follows:
```bash
./spescoind --enable-cors=* --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=55490
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
