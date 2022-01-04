# CryptoCompare
A stupid simple crypto model in Excel VBA

To run the simulation go to the tab Analysis, Enable Macros, and hit "Run".
Parameters:
Stake Per Currency: This is how much you would spend on each crypto currency. Ignoring trading fees the results scale in a linear fashion so this is really just for display purposes and does nothing important.
Itterations: How many times should we run the simulation. Excel has an internal limit of 16,384. I don't use more than 1000 as anything more than that doesn't seem to make much difference.
Number of Currencies: How many currencies / coins from the input set should be taken? You can only pick from the coins exposed by the parameter Max Rows to Read, and you need to be well less than that number to avoid collissions, so you are limited to about 800 here. 
Max Rows To Read: How many coins should we allow ourselves to pick from? there are 1,200 coins in the source data and I like to avoid the bottom few hundred so this limits this field to about 1,000
