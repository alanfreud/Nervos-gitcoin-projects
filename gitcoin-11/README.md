### 🍪 Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

- ### A screenshot of the accounts you created

<small> Last account("#" :2 ) used for this task </small>

<img src="https://github.com/alanfreud/Nervos-gitcoin-projects/blob/master/gitcoin-11/cookie1.png"/>

- ### A link to the Layer 1 address you funded on the Testnet Explorer.

<a href="https://explorer.nervos.org/aggron/address/ckt1qyq9mam7hr5nl2wqsj436pjhkmczemwvjvps5jxxrr"> Testnet Link </a>

- ### A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/alanfreud/Nervos-gitcoin-projects/blob/master/gitcoin-11/depostit1.png"/>

<hr/>

<b>Note: </b> <small> Output for deposit says "check with your account id". You can see that transaction has been confirmed on nervos explorer. </small>

<img src="https://github.com/alanfreud/Nervos-gitcoin-projects/blob/master/gitcoin-11/deposit2.jpg"/>

- ### A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/alanfreud/Nervos-gitcoin-projects/blob/master/gitcoin-11/contract.png" />

- ### The transaction hash of the "Contract call" from the console output 

```bash
0xbc211f6dbcc3fdd0620b694779bc40b5ef65fc7c2b44fc24186343d0596d90cc
```

- ### The contract address that you called 

```bash
0x286adFEEE1d5e91B12F644c672D499BBdB42197e
```

- ### The ABI for contract you made a call on

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

- ### Your Tron address

```bash
TVGZ866cKL6EqMmuVCDgghWGanhYNEHUPL
```
