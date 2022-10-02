# Theory Essay
### Difference between a View function and Pure function
In Solidity, a view function declares that no state will be changed, view indicates that the storage state will not be altered in any way but allows you to "view" it. A Pure function declares that no state variable will be changed or read.

### Difference between a Payable and Non Payable function
A payable modifier meaning the function can process transactions with more than or equal to Zero ether. The keyword "payable" lets someone send ether to a contract and run code to account for a deposit. A non payable account lacks this feature.

### Difference between Constant data types and immutable data types
Constant variables will and can never be changed after compilation. Whereas immutable variables can be assigned in the constructor.

### Difference between a Read function and Write function

