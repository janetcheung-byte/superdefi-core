# SuperDefi Core Contracts

The SuperDefi **Core** contracts model the UniswapV2 binary contract system for the Binance Smart Chain (BSC). 

Core contracts provide the fundamental functionality to swap tokens between parties when interacting with SuperDefi. **Periphery** contracts interact with one or more contracts but are themselves not part of the core. 

*For more information on **Periphery** contracts refer to the [links to Periphery docs]*


## Project tree
___
 * [/contracts](./contracts) 
    * [/flats](./contracts/flats)
        * [SuperDefiERC20_flat.sol](./contracts/flats/SuperDefiERC20_flat.sol)
        * [SuperDefiFactory_flat.sol](./contracts/flats/SuperDefiFactory_flat.sol)
        * [SuperDefiPair_flat.sol](./contracts/flats/SuperDefiPair_flat.sol)
   * [/interfaces](./contracts/interfaces)
     * [IERC20.sol](./contracts/interfaces/IERC20.sol)
     * [ISuperDefiCallee.sol](./contracts/interfaces/ISuperDefiCallee.sol)
     * [ISuperDefiERC20.sol](./contracts/interfaces/ISuperDefiERC20.sol)
     * [ISuperDefiFactory.sol](./contracts/interfaces/ISuperDefiFactory.sol)
     * [ISuperDefiPair.sol](./contracts/interfaces/ISuperDefiPair.sol)
   * [/libraries](./contracts/libraries)
     * [Math.sol](./contracts/libraries/Math.sol)
     * [SafeMath.sol](./contracts/libraries/SafeMath.sol)
     * [UQ112x112.sol](./contracts/libraries/UQ112x112.sol)
   * [/test](./contracts/test)
     * [ERC20.sol](./contracts/test/ERC20.sol)
   * [SuperDefiERC20.sol](./contracts/SuperDefiERC20.sol)
   * [SuperDefiFactory.sol](./contracts/SuperDefiFactory.sol)
   * [SuperDefiPair.sol](./contracts/SuperDefiPair.sol)

## Contracts
___
@TODO


## Deployments
___

## Testnet


### SuperDefiFactory: 
* Address: 0xC7fD68B1338714d3e36592fc6fA4505fCc5eF33E
* Link: [testnet.bscscan.com](https://testnet.bscscan.com/address/0xC7fD68B1338714d3e36592fc6fA4505fCc5eF33E)

### SuperDefiERC20: 
* Address: 0x5f8216450d318378E06379CbeF674Cf6d2B47465 
* Link: [testnet.bscscan.com](https://testnet.bscscan.com/address/0x5f8216450d318378E06379CbeF674Cf6d2B47465)

### SuperDefiPair: 
* Address: 0x8bbd8043BC7B41629f8922c52f8a767824712a2f
* Link: [testnet.bscscan.com](https://testnet.bscscan.com/address/0x8bbd8043BC7B41629f8922c52f8a767824712a2f)


## Mainnet
___

