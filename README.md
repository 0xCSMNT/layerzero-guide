## LayerZero in Pure Foundry

**Build using the guide provided by LayerZero Team**

[Guide](https://gist.github.com/DanL0/7eb57319646e4b1f3176d7723f84226e)

### Dependencies

LayerZero-Labs/LayerZero-v2
LayerZero-Labs/LayerZero
OpenZeppelin/openzeppelin-contracts (delete this and use OZ v4 for Testhelper)
GNSPS/solidity-bytes-utils
OpenZeppelin/openzeppelin-contracts@v4.9.6
OpenZeppelin/openzeppelin-contracts-upgradeable@v4.9.6
wighawag/hardhat-deploy

### Remappings

```
@layerzerolabs/lz-evm-oapp-v2/=lib/LayerZero-v2/oapp/
@layerzerolabs/lz-evm-protocol-v2/=lib/LayerZero-v2/protocol/
@layerzerolabs/lz-evm-messagelib-v2/=lib/LayerZero-v2/messagelib/
@layerzerolabs/lz-evm-v1-0.7/=lib/LayerZero/
@openzeppelin/contracts/=lib/openzeppelin-contracts/contracts/
@openzeppelin/contracts-upgradeable/=lib/openzeppelin-contracts-upgradeable/contracts/
solidity-bytes-utils/=lib/solidity-bytes-utils/
```




