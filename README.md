    -------------------------------TOKEN CREATION----------------------------------

For creating a token in solidity we will use Remix Editor.
This is similar to VS Code in the cloud as it is also an IDE (integrated developer environment).
This will help you write and execute Solidity code quickly and easily.
Remix:https://remix.ethereum.org/

Steps to follow:
1.Go to remix editor .
2.Create a new file with name.sol extension for example(token.sol).
3.Now, copy and paste the code given in the assessment section of getting started with solidity.
4.Make the desired changes in the code given.
6.Define public variables as  Token Name, Token Abbrv., Total Supply.
7.The  contract will have a mapping of addresses to balances (address => uint) i.e unsigned integer.
8.Next we will have a mint function that takes two parameters: an address and a value. 
9.The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
10.Our contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
11. Lastly, our burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.
When we are done with the coding part we will go to the solidity compiler and compile the given file.
Then go to deploy and run transactions and click on deploy button.
In terminal a green tick will be displayed which denotes the successful execution of the code .

