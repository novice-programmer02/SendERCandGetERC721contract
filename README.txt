REMIX EXAMPLE PROJECT;

1. Deploy robot.sol contract (erc721 contract)
2. Deploy test1.sol contract (erc20 contract)
3. Deploy test2.sol contract (erc20 contract)
4. Deploy user.sol contract by passing address of robot.sol, test1.sol, test2.sol contracts (where user send erc20 tokens and get 1 robot nft)
5. Call the transferOwnerShip() from robot.sol contract and passinf the contract address of user.sol(for make that address the admin so it can call there restricted functions).
6. now user will call the getNFT() in user.sol contract by passing number tokens of test1 and test2.
7. After calling that function the user gets 1 robot nft and those erc20 tokens are added to contract address.
8. Check the balance by calling balanceOf(). 