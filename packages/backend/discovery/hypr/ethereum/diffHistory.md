Generated with discovered.json: 0x26aca382028dfb2b6547e3fe0ad067fd39adbe95

# Diff at Sun, 08 Sep 2024 17:18:10 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@fd881462cca0d7ef4519f907f3c6cfd5fe1cde8f block: 19927696
- current block number: 19927696

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19927696 (main branch discovery), not current.

```diff
    contract L1StandardBridge (0x1bBde518ad01BaABFE30020407A7630FB17B545d) {
    +++ description: None
      issuedPermissions.0.target:
-        "0x20D697b63d7747cF78C94ad9ee75C1436781E27E"
+        "0x4a4962275DF8C60a80d3a25faEc5AA7De116A746"
      issuedPermissions.0.via.0:
+        {"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","delay":0}
    }
```

```diff
    contract ProxyAdmin (0x20D697b63d7747cF78C94ad9ee75C1436781E27E) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"configure","target":"0x4a4962275DF8C60a80d3a25faEc5AA7De116A746","via":[]}]
      receivedPermissions:
-        [{"permission":"configure","target":"0xeA078231B0ED94F816E57960423af6d028529b09"},{"permission":"upgrade","target":"0x1bBde518ad01BaABFE30020407A7630FB17B545d"},{"permission":"upgrade","target":"0x2e5687010b5f62Ad0ef84370325bC91DED2724fe"},{"permission":"upgrade","target":"0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD"},{"permission":"upgrade","target":"0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B"},{"permission":"upgrade","target":"0xba1ac896F3b7cB273daE94bF9A6291A432e826c7"},{"permission":"upgrade","target":"0xBB08cf90DEb93492b463f1Ee5DA9453e51643586"}]
      directlyReceivedPermissions:
+        [{"permission":"configure","target":"0xeA078231B0ED94F816E57960423af6d028529b09"},{"permission":"upgrade","target":"0x1bBde518ad01BaABFE30020407A7630FB17B545d"},{"permission":"upgrade","target":"0x2e5687010b5f62Ad0ef84370325bC91DED2724fe"},{"permission":"upgrade","target":"0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD"},{"permission":"upgrade","target":"0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B"},{"permission":"upgrade","target":"0xba1ac896F3b7cB273daE94bF9A6291A432e826c7"},{"permission":"upgrade","target":"0xBB08cf90DEb93492b463f1Ee5DA9453e51643586"}]
    }
```

```diff
    contract L1ERC721Bridge (0x2e5687010b5f62Ad0ef84370325bC91DED2724fe) {
    +++ description: None
      issuedPermissions.0.target:
-        "0x20D697b63d7747cF78C94ad9ee75C1436781E27E"
+        "0x4a4962275DF8C60a80d3a25faEc5AA7De116A746"
      issuedPermissions.0.via.0:
+        {"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","delay":0}
    }
```

```diff
    contract L2OutputOracle (0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD) {
    +++ description: None
      issuedPermissions.0.target:
-        "0x20D697b63d7747cF78C94ad9ee75C1436781E27E"
+        "0x4a4962275DF8C60a80d3a25faEc5AA7De116A746"
      issuedPermissions.0.via.0:
+        {"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","delay":0}
    }
```

```diff
    contract ConduitMultisig (0x4a4962275DF8C60a80d3a25faEc5AA7De116A746) {
    +++ description: None
      descriptions:
-        ["It can act on behalf of 0x20D697b63d7747cF78C94ad9ee75C1436781E27E, inheriting its permissions."]
      receivedPermissions.6:
+        {"permission":"upgrade","target":"0xBB08cf90DEb93492b463f1Ee5DA9453e51643586","via":[{"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E"}]}
      receivedPermissions.5:
+        {"permission":"upgrade","target":"0xba1ac896F3b7cB273daE94bF9A6291A432e826c7","via":[{"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E"}]}
      receivedPermissions.4:
+        {"permission":"upgrade","target":"0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B","via":[{"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E"}]}
      receivedPermissions.3:
+        {"permission":"upgrade","target":"0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD","via":[{"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E"}]}
      receivedPermissions.2:
+        {"permission":"upgrade","target":"0x2e5687010b5f62Ad0ef84370325bC91DED2724fe","via":[{"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E"}]}
      receivedPermissions.1:
+        {"permission":"upgrade","target":"0x1bBde518ad01BaABFE30020407A7630FB17B545d","via":[{"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E"}]}
      receivedPermissions.0.target:
-        "0x20D697b63d7747cF78C94ad9ee75C1436781E27E"
+        "0xeA078231B0ED94F816E57960423af6d028529b09"
      receivedPermissions.0.via:
+        [{"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E"}]
      directlyReceivedPermissions:
+        [{"permission":"act","target":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E"}]
    }
```

```diff
    contract OptimismMintableERC20Factory (0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B) {
    +++ description: None
      issuedPermissions.0.target:
-        "0x20D697b63d7747cF78C94ad9ee75C1436781E27E"
+        "0x4a4962275DF8C60a80d3a25faEc5AA7De116A746"
      issuedPermissions.0.via.0:
+        {"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","delay":0}
    }
```

```diff
    contract OptimismPortal (0xba1ac896F3b7cB273daE94bF9A6291A432e826c7) {
    +++ description: None
      issuedPermissions.0.target:
-        "0x20D697b63d7747cF78C94ad9ee75C1436781E27E"
+        "0x4a4962275DF8C60a80d3a25faEc5AA7De116A746"
      issuedPermissions.0.via.0:
+        {"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","delay":0}
    }
```

```diff
    contract SystemConfig (0xBB08cf90DEb93492b463f1Ee5DA9453e51643586) {
    +++ description: None
      issuedPermissions.0.target:
-        "0x20D697b63d7747cF78C94ad9ee75C1436781E27E"
+        "0x4a4962275DF8C60a80d3a25faEc5AA7De116A746"
      issuedPermissions.0.via.0:
+        {"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","delay":0}
    }
```

```diff
    contract AddressManager (0xeA078231B0ED94F816E57960423af6d028529b09) {
    +++ description: None
      issuedPermissions.0.target:
-        "0x20D697b63d7747cF78C94ad9ee75C1436781E27E"
+        "0x4a4962275DF8C60a80d3a25faEc5AA7De116A746"
      issuedPermissions.0.via.0:
+        {"address":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","delay":0}
    }
```

Generated with discovered.json: 0xcbce71be7a7558d94d53a9ff8253b7c75c8f1476

# Diff at Fri, 30 Aug 2024 07:53:07 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@6c1bd1f41fadf5f2cb1c1805b5a2c6138a3ed35a block: 19927696
- current block number: 19927696

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19927696 (main branch discovery), not current.

```diff
    contract ProxyAdmin (0x20D697b63d7747cF78C94ad9ee75C1436781E27E) {
    +++ description: None
      receivedPermissions.6.via:
-        []
      receivedPermissions.5.via:
-        []
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

```diff
    contract ConduitMultisig (0x4a4962275DF8C60a80d3a25faEc5AA7De116A746) {
    +++ description: It can act on behalf of 0x20D697b63d7747cF78C94ad9ee75C1436781E27E, inheriting its permissions.
      receivedPermissions.0.via:
-        []
    }
```

Generated with discovered.json: 0x041d5e514465c3a25421d82502c9d5e39ed99a4c

# Diff at Fri, 23 Aug 2024 09:52:31 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@67597c7d6c810bc726594446890178150240711e block: 19927696
- current block number: 19927696

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19927696 (main branch discovery), not current.

```diff
    contract L1StandardBridge (0x1bBde518ad01BaABFE30020407A7630FB17B545d) {
    +++ description: None
      values.$upgradeCount:
+        0
    }
```

```diff
    contract L1ERC721Bridge (0x2e5687010b5f62Ad0ef84370325bC91DED2724fe) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract L2OutputOracle (0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract OptimismMintableERC20Factory (0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract OptimismPortal (0xba1ac896F3b7cB273daE94bF9A6291A432e826c7) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract SystemConfig (0xBB08cf90DEb93492b463f1Ee5DA9453e51643586) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

Generated with discovered.json: 0x431079c7869c8fe0d5c7e072fbc3902adce8d20a

# Diff at Wed, 21 Aug 2024 10:03:17 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@2f6dde3357bf5d79196b6e94f79d853a6c4ec72b block: 19927696
- current block number: 19927696

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19927696 (main branch discovery), not current.

```diff
    contract L1StandardBridge (0x1bBde518ad01BaABFE30020407A7630FB17B545d) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","via":[]}]
    }
```

```diff
    contract ProxyAdmin (0x20D697b63d7747cF78C94ad9ee75C1436781E27E) {
    +++ description: None
      assignedPermissions:
-        {"upgrade":["0x1bBde518ad01BaABFE30020407A7630FB17B545d","0x2e5687010b5f62Ad0ef84370325bC91DED2724fe","0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD","0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B","0xBB08cf90DEb93492b463f1Ee5DA9453e51643586","0xba1ac896F3b7cB273daE94bF9A6291A432e826c7"],"configure":["0xeA078231B0ED94F816E57960423af6d028529b09"]}
      issuedPermissions:
+        [{"permission":"configure","target":"0x4a4962275DF8C60a80d3a25faEc5AA7De116A746","via":[]}]
      receivedPermissions:
+        [{"permission":"configure","target":"0xeA078231B0ED94F816E57960423af6d028529b09","via":[]},{"permission":"upgrade","target":"0x1bBde518ad01BaABFE30020407A7630FB17B545d","via":[]},{"permission":"upgrade","target":"0x2e5687010b5f62Ad0ef84370325bC91DED2724fe","via":[]},{"permission":"upgrade","target":"0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD","via":[]},{"permission":"upgrade","target":"0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B","via":[]},{"permission":"upgrade","target":"0xba1ac896F3b7cB273daE94bF9A6291A432e826c7","via":[]},{"permission":"upgrade","target":"0xBB08cf90DEb93492b463f1Ee5DA9453e51643586","via":[]}]
    }
```

```diff
    contract L1ERC721Bridge (0x2e5687010b5f62Ad0ef84370325bC91DED2724fe) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","via":[]}]
    }
```

```diff
    contract L2OutputOracle (0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","via":[]}]
    }
```

```diff
    contract ConduitMultisig (0x4a4962275DF8C60a80d3a25faEc5AA7De116A746) {
    +++ description: It can act on behalf of 0x20D697b63d7747cF78C94ad9ee75C1436781E27E, inheriting its permissions.
      assignedPermissions:
-        {"configure":["0x20D697b63d7747cF78C94ad9ee75C1436781E27E"]}
      receivedPermissions:
+        [{"permission":"configure","target":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","via":[]}]
    }
```

```diff
    contract OptimismMintableERC20Factory (0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","via":[]}]
    }
```

```diff
    contract OptimismPortal (0xba1ac896F3b7cB273daE94bF9A6291A432e826c7) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","via":[]}]
    }
```

```diff
    contract SystemConfig (0xBB08cf90DEb93492b463f1Ee5DA9453e51643586) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","via":[]}]
    }
```

```diff
    contract AddressManager (0xeA078231B0ED94F816E57960423af6d028529b09) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"configure","target":"0x20D697b63d7747cF78C94ad9ee75C1436781E27E","via":[]}]
    }
```

Generated with discovered.json: 0xc27c5a49b0c3924d7a714f6bbff805d68ca632cb

# Diff at Fri, 09 Aug 2024 11:59:41 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@bf40aa32f030fd312056ca0ef198c8550467d1d7 block: 19927696
- current block number: 19927696

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19927696 (main branch discovery), not current.

```diff
    contract ProxyAdmin (0x20D697b63d7747cF78C94ad9ee75C1436781E27E) {
    +++ description: None
      assignedPermissions.upgrade.5:
-        "0xBB08cf90DEb93492b463f1Ee5DA9453e51643586"
+        "0xba1ac896F3b7cB273daE94bF9A6291A432e826c7"
      assignedPermissions.upgrade.4:
-        "0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD"
+        "0xBB08cf90DEb93492b463f1Ee5DA9453e51643586"
      assignedPermissions.upgrade.3:
-        "0xba1ac896F3b7cB273daE94bF9A6291A432e826c7"
+        "0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B"
      assignedPermissions.upgrade.2:
-        "0x1bBde518ad01BaABFE30020407A7630FB17B545d"
+        "0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD"
      assignedPermissions.upgrade.0:
-        "0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B"
+        "0x1bBde518ad01BaABFE30020407A7630FB17B545d"
    }
```

Generated with discovered.json: 0x7e3e0132b64963c69a0349793b0843d7aced6948

# Diff at Fri, 09 Aug 2024 10:09:48 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@1f0da1d0aab7bc6b3b5e54e7e93480bd98e57035 block: 19927696
- current block number: 19927696

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19927696 (main branch discovery), not current.

```diff
    contract ProxyAdmin (0x20D697b63d7747cF78C94ad9ee75C1436781E27E) {
    +++ description: None
      assignedPermissions.admin:
-        ["0x1bBde518ad01BaABFE30020407A7630FB17B545d","0x2e5687010b5f62Ad0ef84370325bC91DED2724fe","0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD","0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B","0xBB08cf90DEb93492b463f1Ee5DA9453e51643586","0xba1ac896F3b7cB273daE94bF9A6291A432e826c7"]
      assignedPermissions.owner:
-        ["0xeA078231B0ED94F816E57960423af6d028529b09"]
      assignedPermissions.upgrade:
+        ["0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B","0x2e5687010b5f62Ad0ef84370325bC91DED2724fe","0x1bBde518ad01BaABFE30020407A7630FB17B545d","0xba1ac896F3b7cB273daE94bF9A6291A432e826c7","0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD","0xBB08cf90DEb93492b463f1Ee5DA9453e51643586"]
      assignedPermissions.configure:
+        ["0xeA078231B0ED94F816E57960423af6d028529b09"]
    }
```

```diff
    contract ChallengerMultisig (0x28fB4D0e436874F4107948E358df3C242De06788) {
    +++ description: None
      values.$multisigThreshold:
-        "4 of 6 (67%)"
      values.getOwners:
-        ["0xefCf0c8faFB425997870f845e26fC6cA6EE6dD5C","0x3840f487A17A41100DD1Bf0946c34f132a57Fd5f","0xa0C600a6e85bf225958FFAcC70B5FDDF9A059038","0x6D4c6D77a87F5aA89444dcCb37A65AEEb152717F","0x7A28B193dab5566bB1781f131A1d15603F2577D8","0xa4000bDD2bB92ce6750b31F1eeda47Bd1cB8e6e4"]
      values.getThreshold:
-        4
      values.$members:
+        ["0xefCf0c8faFB425997870f845e26fC6cA6EE6dD5C","0x3840f487A17A41100DD1Bf0946c34f132a57Fd5f","0xa0C600a6e85bf225958FFAcC70B5FDDF9A059038","0x6D4c6D77a87F5aA89444dcCb37A65AEEb152717F","0x7A28B193dab5566bB1781f131A1d15603F2577D8","0xa4000bDD2bB92ce6750b31F1eeda47Bd1cB8e6e4"]
      values.$threshold:
+        4
      values.multisigThreshold:
+        "4 of 6 (67%)"
    }
```

```diff
    contract ConduitMultisig (0x4a4962275DF8C60a80d3a25faEc5AA7De116A746) {
    +++ description: It can act on behalf of 0x20D697b63d7747cF78C94ad9ee75C1436781E27E, inheriting its permissions.
      assignedPermissions.owner:
-        ["0x20D697b63d7747cF78C94ad9ee75C1436781E27E"]
      assignedPermissions.configure:
+        ["0x20D697b63d7747cF78C94ad9ee75C1436781E27E"]
      values.$multisigThreshold:
-        "4 of 7 (57%)"
      values.getOwners:
-        ["0xF3313C48BD8E17b823d5498D62F37019dFEA647D","0xF0B77EaE7F2dabCC2571c7418406A0dCA3afA4f0","0xa4000bDD2bB92ce6750b31F1eeda47Bd1cB8e6e4","0x3840f487A17A41100DD1Bf0946c34f132a57Fd5f","0xa0C600a6e85bf225958FFAcC70B5FDDF9A059038","0xefCf0c8faFB425997870f845e26fC6cA6EE6dD5C","0x4D8007a0E9f293e62E2b0F43C6Cf4C4B9e135BAe"]
      values.getThreshold:
-        4
      values.$members:
+        ["0xF3313C48BD8E17b823d5498D62F37019dFEA647D","0xF0B77EaE7F2dabCC2571c7418406A0dCA3afA4f0","0xa4000bDD2bB92ce6750b31F1eeda47Bd1cB8e6e4","0x3840f487A17A41100DD1Bf0946c34f132a57Fd5f","0xa0C600a6e85bf225958FFAcC70B5FDDF9A059038","0xefCf0c8faFB425997870f845e26fC6cA6EE6dD5C","0x4D8007a0E9f293e62E2b0F43C6Cf4C4B9e135BAe"]
      values.$threshold:
+        4
      values.multisigThreshold:
+        "4 of 7 (57%)"
    }
```

Generated with discovered.json: 0x769f71c77dc775f250ed5e58797badf6a0edb6b5

# Diff at Thu, 18 Jul 2024 10:31:06 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@d89fe52cb65d643cef712d1d7910564a7acf2dce block: 19927696
- current block number: 19927696

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19927696 (main branch discovery), not current.

```diff
    contract ConduitMultisig (0x4a4962275DF8C60a80d3a25faEc5AA7De116A746) {
    +++ description: None
      descriptions:
+        ["It can act on behalf of 0x20D697b63d7747cF78C94ad9ee75C1436781E27E, inheriting its permissions."]
    }
```

Generated with discovered.json: 0x06e5f348d2fefeede00ea48b514332c748ab92d8

# Diff at Wed, 22 May 2024 20:06:37 GMT:

- author: Luca Donno (<donnoh99@gmail.com>)
- comparing to: main@bac4efad06804152ae97853892e122a801bbc509 block: 19918842
- current block number: 19927696

## Description

ConduitMultisig update.

## Watched changes

```diff
    contract ConduitMultisig (0x4a4962275DF8C60a80d3a25faEc5AA7De116A746) {
    +++ description: None
      upgradeability.threshold:
-        "3 of 5 (60%)"
+        "4 of 7 (57%)"
      values.getOwners.6:
+        "0x4D8007a0E9f293e62E2b0F43C6Cf4C4B9e135BAe"
      values.getOwners.5:
+        "0xefCf0c8faFB425997870f845e26fC6cA6EE6dD5C"
      values.getOwners.4:
-        "0x4D8007a0E9f293e62E2b0F43C6Cf4C4B9e135BAe"
+        "0xa0C600a6e85bf225958FFAcC70B5FDDF9A059038"
      values.getOwners.3:
-        "0xefCf0c8faFB425997870f845e26fC6cA6EE6dD5C"
+        "0x3840f487A17A41100DD1Bf0946c34f132a57Fd5f"
      values.getOwners.2:
-        "0xa0C600a6e85bf225958FFAcC70B5FDDF9A059038"
+        "0xa4000bDD2bB92ce6750b31F1eeda47Bd1cB8e6e4"
      values.getOwners.1:
-        "0x3840f487A17A41100DD1Bf0946c34f132a57Fd5f"
+        "0xF0B77EaE7F2dabCC2571c7418406A0dCA3afA4f0"
      values.getOwners.0:
-        "0xa4000bDD2bB92ce6750b31F1eeda47Bd1cB8e6e4"
+        "0xF3313C48BD8E17b823d5498D62F37019dFEA647D"
      values.getThreshold:
-        3
+        4
    }
```

Generated with discovered.json: 0x94f719afbbf7296c277466ef2c8ac32a8596e628

# Diff at Tue, 21 May 2024 14:21:35 GMT:

- author: Luca Donno (<donnoh99@gmail.com>)
- comparing to: main@c032520e456d0e6bee8b65e420ff7dba9f36bd48 block: 19531598
- current block number: 19918842

## Description

Name change.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19531598 (main branch discovery), not current.

```diff
    contract LyraMultisig (0x4a4962275DF8C60a80d3a25faEc5AA7De116A746) {
    +++ description: None
      name:
-        "LyraMultisig"
+        "ConduitMultisig"
    }
```

Generated with discovered.json: 0xcb35ba385fe9ac2754b38d86f7aee769f1626d94

# Diff at Thu, 28 Mar 2024 09:04:15 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@867de6120241d47b66bf76f83c490408eb3595b0 block: 19412042
- current block number: 19531598

## Description

Update discovery to include the multisig threshold.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19412042 (main branch discovery), not current.

```diff
    contract ChallengerMultisig (0x28fB4D0e436874F4107948E358df3C242De06788) {
    +++ description: None
      upgradeability.threshold:
+        "4 of 6 (67%)"
    }
```

```diff
    contract LyraMultisig (0x4a4962275DF8C60a80d3a25faEc5AA7De116A746) {
    +++ description: None
      upgradeability.threshold:
+        "3 of 5 (60%)"
    }
```

Generated with discovered.json: 0x004d2b7d11fdecf2f0a6c186a7e44db90726c052

# Diff at Mon, 11 Mar 2024 13:06:21 GMT:

- author: Michał Sobieraj-Jakubiec (<michalsidzej@gmail.com>)
- comparing to: main@64454506aee2b4b4e15b121f096369e92ec4cf20 block: 19176779
- current block number: 19412042

## Description

Update OP stack DA handler

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19176779 (main branch discovery), not current.

```diff
    contract SystemConfig (0xBB08cf90DEb93492b463f1Ee5DA9453e51643586) {
    +++ description: None
      values.opStackDA.isSequencerSendingBlobTx:
+        false
    }
```

Generated with discovered.json: 0xeb0c7bf141bfc7f188e3e3529f272eab8d5cb08f

# Diff at Wed, 07 Feb 2024 14:02:35 GMT:

- author: Michał Sobieraj-Jakubiec (<michalsidzej@gmail.com>)
- comparing to: main@2e35800e01005d93332a552032058dcd67f3631d block: 19175185
- current block number: 19176779

## Description

Added opStackSequencerInbox handler

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19175185 (main branch discovery), not current.

```diff
    contract SystemConfig (0xBB08cf90DEb93492b463f1Ee5DA9453e51643586) {
      values.sequencerInbox:
+        "0x0C57B7f3bAc278bE091431B52470fBAdBc4240E6"
    }
```

Generated with discovered.json: 0x46f4c52a626acd3dcf884cb34161e0d5fb8e3c00

# Diff at Wed, 07 Feb 2024 08:40:44 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@64f1e0f27f831d3ef860a1c2faad8c77e04e6c29 block: 19091597
- current block number: 19175185

## Description

Updated with the new OpDAHandler to remove the field.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19091597 (main branch discovery), not current.

```diff
    contract SystemConfig (0xBB08cf90DEb93492b463f1Ee5DA9453e51643586) {
      values.opStackDA.isAllTxsLengthEqualToCelestiaDAExample:
-        true
    }
```

Generated with discovered.json: 0x8a7c6367f7513d053a63c0ea8d4a59e06b34cdf8

# Diff at Fri, 26 Jan 2024 15:13:18 GMT:

- author: Michał Sobieraj-Jakubiec (<michalsidzej@gmail.com>)
- current block number: 19091597

## Description

Update discovery to include the multisig threshold.

## Initial discovery

```diff
+   Status: CREATED
    contract L1StandardBridge (0x1bBde518ad01BaABFE30020407A7630FB17B545d) {
    }
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x20D697b63d7747cF78C94ad9ee75C1436781E27E) {
    }
```

```diff
+   Status: CREATED
    contract ChallengerMultisig (0x28fB4D0e436874F4107948E358df3C242De06788) {
    }
```

```diff
+   Status: CREATED
    contract L1ERC721Bridge (0x2e5687010b5f62Ad0ef84370325bC91DED2724fe) {
    }
```

```diff
+   Status: CREATED
    contract L2OutputOracle (0x3E4F4Eb77a9c1f88c0e1F5aDCc9d3521Ce157FdD) {
    }
```

```diff
+   Status: CREATED
    contract LyraMultisig (0x4a4962275DF8C60a80d3a25faEc5AA7De116A746) {
    }
```

```diff
+   Status: CREATED
    contract OptimismMintableERC20Factory (0x5F67587FB3f1736a5a91C10E3EeB7cA92117177B) {
    }
```

```diff
+   Status: CREATED
    contract L1CrossDomainMessenger (0x9f6F58F07863D72C47D001066C65528C27D3AE19) {
    }
```

```diff
+   Status: CREATED
    contract OptimismPortal (0xba1ac896F3b7cB273daE94bF9A6291A432e826c7) {
    }
```

```diff
+   Status: CREATED
    contract SystemConfig (0xBB08cf90DEb93492b463f1Ee5DA9453e51643586) {
    }
```

```diff
+   Status: CREATED
    contract AddressManager (0xeA078231B0ED94F816E57960423af6d028529b09) {
    }
```
