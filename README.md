# Coin Dex CLI

> Build a CLI (command line interface) for a cryptocurrency price app. 
> Use Commander.js, Inquirer, configstore and some other modules.
> Register an API key at https://nomics.com
>
>
## Usage

```
npm install

npm link
```

## Commands

```
# Help & Commands
coindex -h

# Version
coindex -V

# API Key Commands
coindex key set
coindex key show
coindex key remove

# Crypto Check Commands
coindex check price

# Check Specific Coins (default: BTN,ETH,XRP)
coindex check --coin=BTC,ETH

# Choose Currency (Default: USD)
coindex check --cur=EUR