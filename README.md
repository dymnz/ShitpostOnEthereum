### Shitpost on Ethereum

##### **Make sure you have Metamask and a few ETH in the account** (0.01ETH is enough)


#### 1. Paste the following solidity code on Solidity online compiler: [Remix](https://ethereum.github.io/browser-solidity/)
```
pragma solidity ^0.4.2;

contract Shitpost 
{
	string constant public poster = "PeenuttButler";
	string constant public message = "On 2017/4/21, I shitposted on the Ethereum blockchain.";
}
```
#### 2. Change the poster and message
The longer they are, the more expensive the transaction will cost. 
The example above cost ~$0.2

#### 3. Setting up Remix
In `Setting` tab: 
* Make sure `Current Solidity version` is `0.4.10+commit something something`
* Check the `Enable Optimization`
In `Contract` tab: 
* Make sure `Select execution environment` is `Injected Web3`, which is Metamask

#### 4. Deploy the contract
In `Contract` tab, press the pink 'Create' button, and Metamask should pop up.

Send the transaction.

*Metamask sets a high gas limit, you won't be spending that much, the example above cost ~200000gas*

#### 5. Find the contract
After the transaction is mined, go to etherscan.io and find your contract.

tx example: https://etherscan.io/tx/0xc7f0b67cdded4e5767b626ac49a3b4ea4598ee20d2d01b25daf51a18fb6e2a56

contract example: https://etherscan.io/address/0x7e96a18d7aeec64c9c99ed388ff3907d156030de

#### 6. Verify the contract
At your contract page on etherscan.io, go to `Contract Code` tab. Click `Verify And Publish`, and fill in:
* Contract Name: `Shitpost`  (The contract's name in the code)
* Compiler: `0.4.10+commit something something`
* Optimization: `Enable`
* Copy your Solidity code into the big text box

Then click `Verify And Publish` on the bottom.

#### 7. Done
Now, at your contract page there will be a `Read Contract` tab. You should see your name and message on there.
### You've just shitposted on the Ethereum blockchain!
