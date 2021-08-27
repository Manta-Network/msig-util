# Multisig CLI Utility

Derive a multisig address.

## Install

```bash
yarn install
yarn build
```

(optional:) install `msig-util` globally

```bash
sudo npm i -g .
```

## Usage:

```bash
npx . derive --addresses addr_1,addr_2,... --threshold <num>
```

You can also do the following if you installed globally:

```bash
msig-util derive --addresses addr_1,addr_2,... --threshold <num>
```

It also takes an unrequired option to change the ss58 prefix outputted:

```zsh
... --ss58Prefix [0,2,42]
```
