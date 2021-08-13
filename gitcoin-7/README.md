### 🍪 Gitcoin: 7) Port An Existing Ethereum DApp To Polyjuice

- ### Video and Screenshot

<a href="https://youtu.be/lfxB_64YPsc"> Project Video </a>

<img src="https://github.com/alanfreud/Nervos-gitcoin-projects/blob/master/gitcoin-7/cookies.png"/>

- ### Github Repo

<a href="https://github.com/alanfreud/Nervos-fortune-telling"> GITHUB PROJECT SOURCE CODE </a>

- ### Transaction hash,Contract address and the ABI of the deployed smart contract

Transaction hash:

```bash
0x9a1aa5e1e185a537d8a7820118f1183e3f541a8dd090f17ae54e25fae7778cee
```

Contract Address:

```bash
0x286adFEEE1d5e91B12F644c672D499BBdB42197e
```

ABI:

```javascript
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "fortunes",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "text",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "totalFortune",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_text",
          "type": "string"
        }
      ],
      "name": "createFortune",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]
```
