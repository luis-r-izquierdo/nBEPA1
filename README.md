# nBEPA1

In this repository we include code that is useful to analyze the **nBEPA1** revision protocol, a simple version of the **B**est **E**xperienced **P**rotocol (BEP). 

In accordance with the Evolutionary Game Theory literature, here we assume that there is a population of agents who can revise their strategy occasionally and independently, one agent at a time.

Under the general BEP revision protocol, the revising agent tests a subset of its available strategies by trying out each of them a predetermined number of times. Here we use the simplest version of the BEP protocol, i.e., the version where revising agents consider **A**ll their strategies and they try each of them only once (**1**). Crucially, the revising agent tries each one of its strategies against a randomly drawn opponent; thus, each trial is conducted with a potentially different counterpart. Once each of the candidate strategies has been tried against one opponent, the revising agent chooses the strategy that provided the greatest payoff in the test, resolving the possible ties at random. We also add some small probability of experimentation -or **n**oise- to the algorithm so that, with a small probability, revising agents adopt any of the possible strategies with equal probability. Thus, the name nBEPA1: **n**oisy **B**est **E**xperienced **P**ayoff, **A**ll strategies, **1** trial.
