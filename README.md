# Coin Dex CLI

> Build a CLI (command line interface) for a cryptocurrency price app. 
> Use Commander.js, Inquirer, configstore and some other modules.
> Register an API key at https://nomics.com

## Usage

```
npm install

npm link
```

## Commands

```
# Help & Commands
coindex-cli -h

# Version
coindex-cli -V

# API Key Commands
coindex-cli key set
coindex-cli key show
coindex-cli key remove

# Crypto Check Commands
coindex-cli check price

# Check Specific Coins (default: BTN,ETH,XRP)
coindex-cli check --coin=BTC,ETH

# Choose Currency (Default: USD)
coindex-cli check --cur=EUR

# Example:
coindex-cli check price --coin=BTC,ETH,XRP,LTC,EOS,XMR,ADA,DASH,ZEC,BCH,XLM,NEO,XEM,BAT,QTUM,ZRX,OMG  --cur=USD