# Markov-Chain
Markov chain is a model of some random process that happens over time. Markov chains are called that because they follow a rule called Markov property. The Markov property says that whatever happens next depends on how it is right now (it does not have a memory).

**SAS Code Snippets**
* Step 1: Setting up the Transition Matrix: The historical transition data is analysed and the transition matrix is calculated
* Step 2: Defining Starting Population: The starting population is the number of accounts in various delinquency buckets at the start of the observation window
* Step 3: Matrix multiplication: The transition matrix is multiplied with the number of accounts in each bucket (for time period T) to get the number of accounts in each bucket (for time period T+1)
