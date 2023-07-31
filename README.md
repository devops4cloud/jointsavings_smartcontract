# Joint Savings Account 

Creation of joint savings accounts via Solidity smart contract which accepts two user addresses. These addresses will be able to control a joint savings account. The smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

## Technologies Used

Remix IDE <br>
    Remix online IDE is a powerful toolset for developing, deploying, debugging ethereum and EVM-compatible smart contracts. It requires no setup and has flexible intuitive user interface. 

 - [How to use Remix ](https://remix.ethereum.org/)


## Usage

- Copy Join_Savings.sol file into the Remix IDE
- Compile and Deploy Your Contract in the JavaScript VM within Remix.
- In the Remix IDE, navigate to the “Deploy & Run Transactions” pane, and then make sure that “JavaScript VM” is selected as the environment.
- Click the Deploy button to deploy your smart contract, and then confirm that it successfully deployed


## Application Functionality

* Setting up the joint account with two valid ethereum addresses <br>
<img title="Setting up accounts" alt="Alt text" src="/Images/account_setup.png"> <br>

* Depositing a total of 16th to the account <br>
<img title="Setting up accounts" alt="Alt text" src="/Images/depositing_eth.png"> <br>

* Checking balance after a withdrawal <br>
<img title="Balance after withdrawal" alt="Alt text" src="/Images/balance_withdraw.png"> <br>

* Unauthorized Withdrawal by an address not owning the account <br>
<img title="Unauthorized Withdrawal" alt="Alt text" src="/Images/unauthorized_withdraw.png"> <br>