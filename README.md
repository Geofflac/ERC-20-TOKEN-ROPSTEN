# ERC-20-TOKEN-ROPSTEN
Create a Simple Token in Remix IDE

## 1 - Open a METAMASK wallet
Download the chrome extension, follow the step to create an account, and switch to the ROPSTEN TEST NETWORK.
![image](https://user-images.githubusercontent.com/84672157/148392801-6ac446a5-0435-48c1-af8d-c841f4e9f7d4.png)

## 2 - Provide ETH to the wallet
Use a ROPSTEN FAUCET - https://faucet.egorfine.com/<br />
![image](https://user-images.githubusercontent.com/84672157/148396822-e77a4294-be4d-465c-8d3f-efe5a6ef32a8.png)

## 3 - Write the smart contract
Inside the REMIX IDE, select INJECTED WEB3 environment and connect your METAMASK - https://remix.ethereum.org/<br />
![image](https://user-images.githubusercontent.com/84672157/148502011-192bfe06-23a0-4171-901a-d3735503fdcc.png)<br />
Create a file .sol and place the solidity code from the file token.sol in this repo.

## 4  - Deploy the contract
The gas fees will appear<br />
![image](https://user-images.githubusercontent.com/84672157/148502243-3cc523ee-cc92-41d1-a7a9-014851cf02f1.png)<br />
Once the contract is deployed, the contract details appear in the terminal, take note of the transaction hash<br />
![image](https://user-images.githubusercontent.com/84672157/148504917-397aaf63-5ae2-4379-ad11-a4548ab87ed4.png)

## 5 - Collect contract hash
Details can also be seen on ROPSTEN ETHERSCAN, just copy the transaction hash from REMIX TERMINAL inside ETHERSCAN search bar - https://ropsten.etherscan.io/<br />
From there, you can retrieve the contract hash<br />
![image](https://user-images.githubusercontent.com/84672157/148503889-e6b2e496-5a91-46db-9cd8-df208562017d.png)

## 6 - Retrieve token to your METAMASK wallet
From your METAMASK, click on the button import token<br />
![image](https://user-images.githubusercontent.com/84672157/148503922-cd4793a8-3ffc-4fdd-8ed8-a8fb0bfbc3aa.png)<br />
Copy the contract hash, and confim<br />
![image](https://user-images.githubusercontent.com/84672157/148503958-92d55dcf-ce97-4a21-a11b-2c11cf064a65.png)<br />
The tokens will appear in your account<br />
![image](https://user-images.githubusercontent.com/84672157/148503992-4bd30c74-b30a-4db1-992b-443a5e7224f4.png)




