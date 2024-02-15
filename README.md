# Joops R.W.A Custom scooter transactions
This plugin contains custom transactions built for the Joops R.W.A electric scooters rental project. 

https://www.joops.app

## Installation
1 Add the plugin to your relay node. 
```bash
cd ~/{core-bridgechain}/plugins && git clone https://github.com/e-m-s-y/scooter-transactions.git
```
2 Open `~/.config/{ark-core}/{mainnet|devnet|testnet}/plugins.js` and add the plugin config at the bottom of the file.
```js
"@foly/scooter-transactions": {
    enabled: true
}
```
3 Build the plugin.
```bash
cd ~/{core-bridgechain}
yarn build
```
4 Restart your relay.

## Credits

- [e-m-s-y](https://github.com/e-m-s-y)

## License

[MIT](LICENSE)
