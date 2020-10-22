# W2W Explorer
Block explorer for W2W CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon w2wd. It should be accessible from the Internet. Run w2wd with open port as follows:
```bash
./w2wd --enable-cors="*" --enable_blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=21016
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

### Development
Devs: @taegus @katz @devopsralf

### Note
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
