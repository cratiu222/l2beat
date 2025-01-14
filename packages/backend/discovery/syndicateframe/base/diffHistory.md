Generated with discovered.json: 0x8213fa83edf87c6a80c7884b871e9e4834d8f7a4

# Diff at Sun, 08 Sep 2024 17:20:10 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@fd881462cca0d7ef4519f907f3c6cfd5fe1cde8f block: 18674800
- current block number: 18674800

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 18674800 (main branch discovery), not current.

```diff
    contract L2OutputOracle (0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"
+        "0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d"
      issuedPermissions.0.via.0:
+        {"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","delay":0}
    }
```

```diff
    contract OptimismPortal (0x52fA397D799f1CE416a2089B964Aa293c347994F) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"
+        "0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d"
      issuedPermissions.0.via.0:
+        {"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","delay":0}
    }
```

```diff
    contract GnosisSafeL2 (0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d) {
    +++ description: None
      descriptions:
-        ["It can act on behalf of 0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E, inheriting its permissions."]
      receivedPermissions.4:
+        {"permission":"upgrade","target":"0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b","via":[{"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"}]}
      receivedPermissions.3:
+        {"permission":"upgrade","target":"0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4","via":[{"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"}]}
      receivedPermissions.2:
+        {"permission":"upgrade","target":"0x52fA397D799f1CE416a2089B964Aa293c347994F","via":[{"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"}]}
      receivedPermissions.1:
+        {"permission":"upgrade","target":"0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5","via":[{"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"}]}
      receivedPermissions.0.target:
-        "0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"
+        "0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0"
      receivedPermissions.0.via:
+        [{"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"}]
      directlyReceivedPermissions:
+        [{"permission":"act","target":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"}]
    }
```

```diff
    contract AddressManager (0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"
+        "0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d"
      issuedPermissions.0.via.0:
+        {"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","delay":0}
    }
```

```diff
    contract SystemConfig (0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"
+        "0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d"
      issuedPermissions.0.via.0:
+        {"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","delay":0}
    }
```

```diff
    contract ProxyAdmin (0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"configure","target":"0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d","via":[]}]
      receivedPermissions:
-        [{"permission":"configure","target":"0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0"},{"permission":"upgrade","target":"0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5"},{"permission":"upgrade","target":"0x52fA397D799f1CE416a2089B964Aa293c347994F"},{"permission":"upgrade","target":"0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4"},{"permission":"upgrade","target":"0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b"}]
      directlyReceivedPermissions:
+        [{"permission":"configure","target":"0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0"},{"permission":"upgrade","target":"0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5"},{"permission":"upgrade","target":"0x52fA397D799f1CE416a2089B964Aa293c347994F"},{"permission":"upgrade","target":"0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4"},{"permission":"upgrade","target":"0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b"}]
    }
```

```diff
    contract L1StandardBridge (0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"
+        "0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d"
      issuedPermissions.0.via.0:
+        {"address":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","delay":0}
    }
```

Generated with discovered.json: 0x59c72cddb6b11c73779f7f07ea78cf0ce7383008

# Diff at Fri, 30 Aug 2024 08:17:26 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@6c1bd1f41fadf5f2cb1c1805b5a2c6138a3ed35a block: 18674800
- current block number: 18674800

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 18674800 (main branch discovery), not current.

```diff
    contract GnosisSafeL2 (0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d) {
    +++ description: It can act on behalf of 0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E, inheriting its permissions.
      receivedPermissions.0.via:
-        []
    }
```

```diff
    contract ProxyAdmin (0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E) {
    +++ description: None
      receivedPermissions.4.via:
-        []
      receivedPermissions.3.via:
-        []
      receivedPermissions.2.via:
-        []
      receivedPermissions.1.via:
-        []
      receivedPermissions.0.via:
-        []
    }
```

Generated with discovered.json: 0x0029b9aaad77af80f4c27d0af65ed3625501792d

# Diff at Fri, 23 Aug 2024 09:57:47 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@67597c7d6c810bc726594446890178150240711e block: 18674800
- current block number: 18674800

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 18674800 (main branch discovery), not current.

```diff
    contract L2OutputOracle (0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract OptimismPortal (0x52fA397D799f1CE416a2089B964Aa293c347994F) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract SystemConfig (0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract L1StandardBridge (0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b) {
    +++ description: None
      values.$upgradeCount:
+        0
    }
```

Generated with discovered.json: 0x3a4c57f9499dac76ac4ff5b032c3f107d2e96e18

# Diff at Wed, 21 Aug 2024 10:08:06 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@2f6dde3357bf5d79196b6e94f79d853a6c4ec72b block: 18674800
- current block number: 18674800

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 18674800 (main branch discovery), not current.

```diff
    contract L2OutputOracle (0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","via":[]}]
    }
```

```diff
    contract OptimismPortal (0x52fA397D799f1CE416a2089B964Aa293c347994F) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","via":[]}]
    }
```

```diff
    contract GnosisSafeL2 (0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d) {
    +++ description: It can act on behalf of 0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E, inheriting its permissions.
      assignedPermissions:
-        {"configure":["0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E"]}
      receivedPermissions:
+        [{"permission":"configure","target":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","via":[]}]
    }
```

```diff
    contract AddressManager (0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"configure","target":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","via":[]}]
    }
```

```diff
    contract SystemConfig (0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","via":[]}]
    }
```

```diff
    contract ProxyAdmin (0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E) {
    +++ description: None
      assignedPermissions:
-        {"upgrade":["0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5","0x52fA397D799f1CE416a2089B964Aa293c347994F","0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b","0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4"],"configure":["0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0"]}
      issuedPermissions:
+        [{"permission":"configure","target":"0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d","via":[]}]
      receivedPermissions:
+        [{"permission":"configure","target":"0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0","via":[]},{"permission":"upgrade","target":"0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5","via":[]},{"permission":"upgrade","target":"0x52fA397D799f1CE416a2089B964Aa293c347994F","via":[]},{"permission":"upgrade","target":"0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4","via":[]},{"permission":"upgrade","target":"0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b","via":[]}]
    }
```

```diff
    contract L1StandardBridge (0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E","via":[]}]
    }
```

Generated with discovered.json: 0x3065b0a06c9208eac37c0b38b231132169065726

# Diff at Tue, 20 Aug 2024 07:29:13 GMT:

- author: Radina Talanova (<nt.radina@gmail.com>)
- comparing to: main@5417c4717b5cefeed17cd8419a7eb2dda22d4206 block: 15661223
- current block number: 18674800

## Description

The proxy admin was updated to a 3/4 multisig (not sure why the updates below).

## Watched changes

```diff
+   Status: CREATED
    contract L1CrossDomainMessenger (0x0ED44be59Ea62a9960CB97f8aC54088304D05791)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L2OutputOracle (0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OptimismPortal (0x52fA397D799f1CE416a2089B964Aa293c347994F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafeL2 (0x87Ef0aB1189F76eBCaEe736A5EB8F639a8cF156d)
    +++ description: It can act on behalf of 0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E, inheriting its permissions.
```

```diff
+   Status: CREATED
    contract AddressManager (0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0)
    +++ description: None
```

```diff
+   Status: CREATED
    contract SystemConfig (0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1StandardBridge (0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b)
    +++ description: None
```

## Source code changes

```diff
.../syndicateframe/base/.flat/AddressManager.sol   |  112 +
 .../base/.flat/GnosisSafeL2/GnosisSafeL2.sol       | 1031 +++++++
 .../base/.flat/GnosisSafeL2/GnosisSafeProxy.p.sol  |   34 +
 .../L1CrossDomainMessenger.sol                     | 1532 ++++++++++
 .../ResolvedDelegateProxy.p.sol                    |   46 +
 .../.flat/L1StandardBridge/L1ChugSplashProxy.p.sol |  221 ++
 .../.flat/L1StandardBridge/L1StandardBridge.sol    | 1429 +++++++++
 .../base/.flat/L2OutputOracle/L2OutputOracle.sol   |  751 +++++
 .../base/.flat/L2OutputOracle/Proxy.p.sol          |  209 ++
 .../base/.flat/OptimismPortal/OptimismPortal.sol   | 3221 ++++++++++++++++++++
 .../base/.flat/OptimismPortal/Proxy.p.sol          |  209 ++
 .../syndicateframe/base/.flat/ProxyAdmin.sol       |  297 ++
 .../base/.flat/SystemConfig/Proxy.p.sol            |  209 ++
 .../base/.flat/SystemConfig/SystemConfig.sol       |  708 +++++
 14 files changed, 10009 insertions(+)
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 15661223 (main branch discovery), not current.

```diff
-   Status: DELETED
    contract L1CrossDomainMessenger (0x0ED44be59Ea62a9960CB97f8aC54088304D05791)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L2OutputOracle (0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5)
    +++ description: None
```

```diff
-   Status: DELETED
    contract OptimismPortal (0x52fA397D799f1CE416a2089B964Aa293c347994F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract AddressManager (0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0)
    +++ description: None
```

```diff
-   Status: DELETED
    contract SystemConfig (0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1StandardBridge (0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b)
    +++ description: None
```

Generated with discovered.json: 0x4c4a351cc99bdbd3869c4d7a597a94c9006d7d89

# Diff at Fri, 09 Aug 2024 12:04:14 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@bf40aa32f030fd312056ca0ef198c8550467d1d7 block: 15661223
- current block number: 15661223

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 15661223 (main branch discovery), not current.

```diff
    contract ProxyAdmin (0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E) {
    +++ description: None
      assignedPermissions.upgrade.2:
-        "0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5"
+        "0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b"
      assignedPermissions.upgrade.0:
-        "0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b"
+        "0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5"
    }
```

Generated with discovered.json: 0x06d91178325ba2b708f22d5584ed8369946ae510

# Diff at Fri, 09 Aug 2024 10:14:13 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@1f0da1d0aab7bc6b3b5e54e7e93480bd98e57035 block: 15661223
- current block number: 15661223

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 15661223 (main branch discovery), not current.

```diff
    contract ProxyAdmin (0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E) {
    +++ description: None
      assignedPermissions.admin:
-        ["0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5","0x52fA397D799f1CE416a2089B964Aa293c347994F","0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b","0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4"]
      assignedPermissions.owner:
-        ["0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0"]
      assignedPermissions.upgrade:
+        ["0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b","0x52fA397D799f1CE416a2089B964Aa293c347994F","0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5","0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4"]
      assignedPermissions.configure:
+        ["0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0"]
    }
```

Generated with discovered.json: 0x58150dfac00f75ad2c9b331523a03d2d5a33c8d9

# Diff at Tue, 11 Jun 2024 13:16:59 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@4b482f34b787e8546115b599d38d66643fc47a24 block: 13275713
- current block number: 15661223

## Description

Provide description of changes. This section will be preserved.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 13275713 (main branch discovery), not current.

```diff
    contract SystemConfig (0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4) {
    +++ description: None
      values.resourceConfig:
-        [20000000,10,8,1000000000,1000000,"340282366920938463463374607431768211455"]
+        {"maxResourceLimit":20000000,"elasticityMultiplier":10,"baseFeeMaxChangeDenominator":8,"minimumBaseFee":1000000000,"systemTxMaxGas":1000000,"maximumBaseFee":"340282366920938463463374607431768211455"}
    }
```

Generated with discovered.json: 0x147fd279bec58614540f9e2feb015f36787829b5

# Diff at Wed, 17 Apr 2024 07:59:38 GMT:

- author: Luca Donno (<donnoh99@gmail.com>)
- current block number: 13275713

## Description

Standard OP stack chain with no significant changes.

## Initial discovery

```diff
+   Status: CREATED
    contract L1CrossDomainMessenger (0x0ED44be59Ea62a9960CB97f8aC54088304D05791)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L2OutputOracle (0x520D972B4A7C1CE4d5e01bCd4349a93a8AeaEAC5)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OptimismPortal (0x52fA397D799f1CE416a2089B964Aa293c347994F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract AddressManager (0x9Bf9cd5aD745076b5bFb7Cc2d3b871532973C2c0)
    +++ description: None
```

```diff
+   Status: CREATED
    contract SystemConfig (0xc2dA6Afd69F0ce69313F01c73f77E6471f06b4E4)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0xF5BD775557F3b8817C34Fc784971A0AF1a36DD8E)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1StandardBridge (0xF7Cb313CB6D146dAbB8c5E31798BDCeFc67B831b)
    +++ description: None
```
