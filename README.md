# Handshake Address

Convenience `Address` class for HNS addresses.

## Installation

```
npm i hns-address
```

## Usage

```js
const Address = require('hns-address');

// validate addresses
Address.isValid('hs1qsy0zl3ddmf5ex99pg25jp34uyeey20eyc0gw8m'); // true
Address.isValid('hs1qsy0zl3ddmf5'); // false

// or create an Address instance
const address = new Address('hs1qsy0zl3ddmf5ex99pg25jp34uyeey20eyc0gw8m');
address.isValid(); // true
```

If you're already using [hsd](https://github.com/handshake-org/hsd), then you should just import directly:
```js
const Address = require('hsd/lib/primitives/address');
```
