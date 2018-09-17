# dspace-data-collection

**findInitialedNamesByCollection.py**

This script finds names with initials in DSpace collections based on regular expression matches and prints the results to a CSV.

In particular, it searches for names where the first name is an initial and has not been expanded. It ignores most instances of names where the initial is a middle initial.

**getKeyNamesForCollection.py**

This script prints all the dcElements being used in a specific DSpace collection.

**getMetdataForItemsInCollectionByKeyValueSearch.py**

This script produces a csv with the metadata for items from a specific DSpace collection that have a certain key/value pair.
