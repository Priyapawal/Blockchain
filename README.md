
# Blockchain concepts

We will launch an ERC20 token on the Ropsten Network and distribute it to ten other Metamask accounts using Node js in this project.

To begin, we must first establish 11 metamask accounts, one of which will be your main account and the other ten will be your distribution accounts.


## Deployment
Prerequisites:

For the Deployment, we first need to install node.js and vs code.

Then we use "'bash node —version"' to check the node version.

To generate node modules, use the following command after validating the node version.


"'bash npm I fs big-number dotenv web3 ethereumjs-tx 

We need to deploy the smartcontract using the remix ethereum editor once the node modules have been generated.

To modify IDE, copy the deploymentcontract.sol code and change the token name to suit your needs.


## Screenshots


Deploy the contract after modifying the token.


Select 0.8.0 from the solidity compiler's drop-down menu and click compile.

After that, pick Injected Web3 as the environment and click the Deploy & execute transactions option.


On the right, your metamask account will open and ask for authentication.


Metamask will open and ask you to confirm the transaction when you select the custom token contract and click deploy.



## Roadmap

- After making changes to the token, it's time to deploy the contract.


Click compile after selecting 0.8.0 from the solidity compiler's drop-down menu.

After that, select Injected Web3 as the environment and select Deploy & execute transactions from the drop-down menu.


Your metamask account will open on the right and ask for authentication.


When you pick the custom token contract and click deploy, Metamask will open and ask you to confirm the transaction.



Now Run

```bash
  node distribute.js
```

Following the execution of the code, 5% of the total tokens will be awarded to ten separate metamask accounts.


