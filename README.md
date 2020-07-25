# Apriori
### Apriori algorithm is for finding frequent itemsets in a dataset for boolean association rule. Name of the algorithm is Apriori because it uses prior knowledge of frequent itemset properties. We apply an iterative approach or level-wise search where k-frequent itemsets are used to find k+1 itemsets.
### Here we deal with a dataset of a market basket which has 20 columns representing the goods purchased and 7501 rows representing the users
### We use Apriori algorithm for assigning some particular goods to be placed close according to the customer needs in the shop
### In this dataset the top priority was given to the light cream and chicken which was having 
1. confidence =29% that the customer will buy light cream if he buys chicken
2. lift =4.843
3. support=0.004

# Eclat
### We use ECLAT algorithm for assigning some particular goods to be placed close according to the customer needs in the shop
### As there is a direct command in R we can directly use that command and have the results but on the other side in python we have to use mlxtend and apriori(only support parameter)
### In this dataset the top priority was given to the burger and almonds which was having
1. support=0.005
