- https://trufflesuite.com/docs/truffle/reference/configuration#compiler-configuration

```
[init]
mkdir defilab
cd defilab
truffle init
git init
git remote add origin git@github.com:frank4g/defilab.git

[create.contract]
truffle create contract JTNToken.sol

[deps]
npm install --save-dev @openzeppelin/contracts-ethereum-package
npm install --save-dev @openzeppelin/contracts@3.4.0
```