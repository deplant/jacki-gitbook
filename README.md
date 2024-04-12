# What is Jacki?

**Jacki** is a feature-rich framework for smart-contracts development, testing & accessing TVM-compatible blockchains like [Everscale](https://everscale.network/), [Venom](https://venom.network/), [GOSH](https://gosh.sh/) & [TON](https://ton.org/).&#x20;

**Jacki** is based on [Java TVM-SDK Binding](https://app.gosh.sh/o/deplant\_dao/r/java\_sdk\_binding) and other utilities made by **Deplant** team. The only 3rd party dependencies are TVM-SDK by EverX and [Jackson](https://github.com/FasterXML/jackson) as a JSON serialisation framework. **Jacki** also uses JavaPoet for generating smart contract wrappers.

### Features

* Auto-generation of Java classes from smart contract ABIs to create, deploy and call smart contract functions from plain Java code
* Auto-conversion of ABI types to Java native types for any input/output
* Ready helper clesses to work with TIP 3.2 Fungible Tokens
* Ready helper clesses to work with TIP 4 Non-Fungible Token Standard
* Easy work with all sort of Multisig Wallets
* Access to transaction trees for complex calls debug or exception catching
* Complete typed implementation of latest [TVM-SDK](https://github.com/tonlabs/ever-sdk/blob/master/docs/SUMMARY.md) API
* Pluggable TVM-SDK library support (no rebuild or update needed, just plug-in any SDK lib you like with **Jacki** special Loaders)
