# ⚡ PowerMaker

Smart contracts suite of PowerMaker, an automated market maker of power perpetuals on Ethereum. 

## Installation

To install with [Foundry](https://github.com/foundry-rs/foundry):

```bash
forge install numoen/pmmp
```

## Local development

This project uses [Foundry](https://github.com/foundry-rs/foundry) as the development framework.

### Dependencies

```bash
forge install
```

### Compilation

```bash
forge build
```

### Test

```bash
forge test
```

### Local setup

In order to test third party integrations such as interfaces, it is possible to set up a forked mainnet with several positions open

```bash
sh anvil.sh
```

then, in a separate terminal,

```bash
sh setup.sh
```
