# A-smart-contract-that-tracks-ownership-of-items-in-a-supply-chain.
Flowchart of Code Execution
plaintext
Copy code
 Start
 |
 User Calls transferItem
 |
 Is Caller the Owner? -----> No -----> Revert with Error "Not the owner"
 |
 Is New Owner Valid? -----> No -----> Revert with Error "Invalid new owner"
 |
 Update Item Ownership in Mapping
 |
 End
