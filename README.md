# Theory Essay

### Difference between a View function and Pure function
In Solidity, a view functon declares that no state will be changes, view indicates that the storage state will not be altered in anyway but allows you to "view" it. Whereas, a Pure function declares that no state variable will be either changed or read.

### Difference between a Payable and Non Payable function 
 A payable modifier meaning the function can process transactions with more than or equal to Zero ether. The keyword "payable" lets someone to send ether to a contract and run code to account for a deposit deposit. A non payable accounct lacks this feature.
 
### Difference between Constant data types and immutable data types
Constant variables will and can never  be changed after compilation. Whereas, immutable variables can be assinged in the constructor.

### Difference between a Read function and Write function
