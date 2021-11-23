# nBEPA1

In this repository we include code that is useful to analyze the **nBEPA1** revision protocol, a simple version of the **B**est **E**xperienced **P**rotocol (BEP). 

In accordance with the Evolutionary Game Theory literature, here we assume that there is a population of agents who can revise their strategy occasionally and independently, one agent at a time.

Under the general BEP revision protocol, the revising agent tests a subset of its available strategies by trying out each of them a predetermined number of times. Here we use the simplest version of the BEP protocol, i.e., the version where revising agents consider **A**ll their strategies and they try each of them only once (**1**). Crucially, the revising agent tries each one of its strategies against a randomly drawn opponent; thus, each trial is conducted with a potentially different counterpart. Once each of the candidate strategies has been tried against one opponent, the revising agent chooses the strategy that provided the greatest payoff in the test, resolving the possible ties at random. We also add some small probability of experimentation -or **n**oise- to the algorithm so that, with a small probability, revising agents adopt any of the possible strategies with equal probability. Thus, the name nBEPA1: **n**oisy **B**est **E**xperienced **P**ayoff, **A**ll strategies, **1** trial.

References about nBEPA1:

- Izquierdo, L. R., Izquierdo, S. S. and Rodríguez, J. (In Progress). Decentralized, Fast and Scalable Almost-Global Convergence in Single-Optimum Coordination Problems. http://www.luis.izqui.org

References about BEP:

- Sandholm, W. H., Izquierdo, S. S., and Izquierdo, L. R. (2019). Best experienced payoff dynamics and cooperation in the Centipede game. *Theoretical Economics*, 14: 1347-1385. https://doi.org/10.3982/TE3565

- Sandholm, W. H., Izquierdo, S. S., and Izquierdo, L. R. (2020). Stability for best experienced payoff dynamics. *Journal of Economic Theory*, 185:104957. https://doi.org/10.1016/j.jet.2019.104957

- Izquierdo, S. S., and Izquierdo, L. R. (2021). "Test two, choose the better" leads to high cooperation in the Centipede game. *Journal of Dynamics and Games*. http://dx.doi.org/10.3934/jdg.2021018
