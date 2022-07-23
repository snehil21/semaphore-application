# semaphore-application
The Cigarette smoker's problem

Introduction :
The Cigarette smoker's problem is a concurrency problem in computer science,originally described in 1971 by Suhas Patil. In this problem The Agent represent the Operating system and smokers represent the processes/threads.In this problem The Agent should allocate resources to smokers and the same time avoid Deadlock.

problem statement :
Assume a cigarette requires three ingredients to make and smoke: tobacco, paper, and matches. There are three smokers around a table, each of whom has an infinite supply of one of the three ingredients -	one smoker has an infinite supply of tobacco, another has paper, and the third has matches.

solution :
There is also a non-smoking agent who enables the smokers to make their cigarettes by arbitrarily selecting two of the supplies to place on the table. The smoker who has the third supply should remove the two items from the table, using them (along with their own supply) to make a cigarette, which they smoke for a while. Once the smoker has finished his cigarette, the agent places two new random items on the table. This process continues forever.
