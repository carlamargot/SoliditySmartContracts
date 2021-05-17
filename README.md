# SoliditySmartContracts


## Associate ProfitSplitter 

![image](https://user-images.githubusercontent.com/73208140/118420385-b7c8d100-b68c-11eb-8937-d500e10225a4.png)

This contract will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

Before deploying the contract make sure your MetamMask is connected and pointed to localhost:8545.
 
To deploy a contract using Remix IDE to your local Ganache chain by connecting to Injected Web3 and ensuring MetaMask is pointed to localhost:8545.

You will need to fill in the constructor parameters with your designated employee addresses.
Test the deposit function by sending various values. 

Screen Shot 2021-05-16 at 9.44.20 PM![image](https://user-images.githubusercontent.com/73208140/118421863-fc09a080-b68f-11eb-9af0-ab10f9119f96.png)

Keep an eye on the employee balances as you send different amounts of Ether to the contract and ensure the logic is executing properly.

Screen Shot 2021-05-16 at 8.18.14 PM![image](https://user-images.githubusercontent.com/73208140/118421907-1774ab80-b690-11eb-8b23-2675b8e0a576.png)

## TieredProfitSplitter

In this contract, rather than splitting the profits evenly between Associate-level employees, you will calculate different  percentages for different tiers of employees (CEO 60%, CTO 25%, and Associate 15%). This contract also sends the remainder amount to the employee with the highest percentage, which in this case is the CEO. 

Screen Shot 2021-05-16 at 10.09.54 PM![image](https://user-images.githubusercontent.com/73208140/118423637-7c7dd080-b693-11eb-9017-af88accdd394.png)

