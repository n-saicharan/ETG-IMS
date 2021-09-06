# ETG-IMS

## Inventory Management System in python

**records.json file stores the inventory details.**

**sales.json file stores the transactions details.**

### Features
It has the features like :

1 Adding a new product

2 Adding the existing product

3 Removing the product

4 Purchasing the product


**Removing the product** makes its quantity 0.

There is also an option of **Deleting the product** .It deletes the product along with its ID from records dictionary and is intended to use only if any mistake is made while adding the product to the records.

For any action the appropriate code section has to be executed.
Every transaction (adding / removing / purchasing) gets updated into transaction dictionary automatically.
Records and Transactions dictionaries can viewed whenever required by executing appropriate sections of code.

Every time the execution process has to be started with **Reading the json files** and has to be ended with the **Writing the json files** section.

