# MS Apriori algorithm

This is an implementation of the Apriori algorithm with multiple minimum supports. The decription of the algorithm is given in the book Web Data Mining by Bing Liu.

### **PREREQUISITES**
----
- Python version 3
- Transaction file containing the all the itemsets
- Parameter file containing the minimum supports for each item, the support difference constraint, the itemsets that cannot occur together and the items that must be a part of each of the frequent itemset found

### **STEPS TO RUN**
----
Run the file `MSApriori.py` using the command `python3 MSApriori.py {path to transaction file} {path to parameter file} {path to output file}`
