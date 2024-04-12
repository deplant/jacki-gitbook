# Quick Start

Load TVM-SDK to access blocckchain

```java
EverSdk.load(new AbsolutePathLoader("~/sdk/ton_client.dll"));
```

Create new configured context

```java
int contextId = EverSdk.builder()
                 .networkEndpoints("https://ackinacki-testnet.tvmlabs.dev/landing")
                 .networkQueryTimeout(300_000L) // in milliseconds
                 .build()
                 .orElseThrow();
```

Make new pair of keys and print them

```java
var keys = Credentials.RANDOM(sdk);
System.out.println(keys.secretKey());
System.out.println(keys.publicKey());
```

Access existing contract

```java
AbstractContract contr = new AbstractContract(sdk, "0:your_contract_address");
```
