## Important info

Please read before changing anything

### Explorer API

- All fields are required for Exilibrium to work properly,
- Addresses & slugs should be formatted without prefixing and trailing slashes

### Stakepools API

- Required fields are [typescript style notation]:
  ```
  {
      "Host": String,
      "APIEnabled": Boolean,
      "Network": "mainnet" | "testnet",
      "APIVersionsSupported": Array<1 | 2>
  }
  ```
