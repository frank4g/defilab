- https://trufflesuite.com/docs/truffle/reference/configuration#compiler-configuration

```
[init]
mkdir defilab
cd defilab
truffle init
git init
git remote add origin git@github.com:frank4g/defilab.git

[deps]
npm install --save-dev @openzeppelin/contracts-ethereum-package
npm install --save-dev @openzeppelin/contracts@3.4.0
npm i --save @uniswap/v2-core
npm i --save @uniswap/v2-periphery

[create.contract]
truffle create contract JTNToken.sol

```