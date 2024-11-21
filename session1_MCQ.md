The main differences between AND and OR logic in our network are:
1. The paths through which states transition
2. The conditions required for Z activation
3. The network's response to transient signals

Both networks maintain the same attractors (000 and 111), but their dynamics and signal processing capabilities differ.

These questions test understanding of:
- Network dynamics
- Signal processing
- Logic gate effects
- State transitions
- Biological implications
- System stability
- Temporal behavior
- Noise filtering properties

The correct answers are based on the theoretical principles of FFLs and the computational results from the exercises.





1. In the C1-FFL network with AND logic, when starting from the initial state {'X': 0, 'Y': 1, 'Z': 1}, what happens to Z?
a) Z remains active indefinitely
**b) Z deactivates immediately**
c) Z oscillates between active and inactive states
d) Z's state depends on random fluctuations
e) Z maintains its state until X becomes active

2. What is the primary difference between AND and OR logic in the FFL's response to transient signals?
a) AND logic requires more network nodes
b) OR logic maintains Z's activation longer
**c) AND logic provides better noise filtering**
d) OR logic makes the network bistable
e) AND logic makes X and Y independent

3. When Y's activation delay is reduced from 6 to 2 time steps, what effect is observed?
a) The network loses all steady states
**b) Z responds more quickly to X activation**
c) X becomes permanently inactive
d) Y becomes independent of X
e) The network develops new cyclical attractors

4. In the state transition graph of the AND logic network, steady states are characterized by:
a) The highest number of incoming edges
**b) No outgoing edges**
c) The most centrally located nodes
d) Bidirectional connections only
e) The largest node size

5. How does changing to OR logic affect the network's attractors compared to AND logic?
a) It increases the number of attractors
b) It eliminates all steady states
c) It only allows cyclic attractors
**d) It maintains the same attractors (000 and 111)**
e) It changes the type of attractors


6. What happens to signal processing when quick_deactivation_step is decreased?
**a) The network becomes more sensitive to noise**
b) Z never achieves activation
c) Y becomes permanently active
d) The network shows stronger filtering
e) X and Y become decoupled

7. In the Boolean network with AND logic, what conditions are required for Z activation?
a) Either X or Y must be active
b) Only X must be active
c) Only Y must be active
**d) Both X and Y must be active**
e) Z activates independently of X and Y

8. How does the persistence of Z's activity differ between AND and OR logic?
a) It's identical in both cases
b) OR logic shows shorter persistence
c) AND logic shows no persistence
**d) OR logic shows longer persistence**
e) Persistence is random in both cases

9. When analyzing the state transition graph, what indicates a limit cycle?
a) A single node with no edges
**b) A sequence of states that repeats**
c) States with only incoming edges
d) Isolated nodes
e) States with highest degree centrality

10. What biological feature is best captured by the delay in Y's activation?
a) Protein degradation
b) DNA replication
**c) Transcriptional/translational delay**
d) Cell division
e) Membrane transport

11. The synchronous update scheme in the simulation means:
a) Only one node updates at a time
b) Nodes update in random order
**c) All nodes update simultaneously**
d) Updates occur only when X is active
e) Updates depend on Z's state

12. In the OR logic network, Z deactivation requires:
a) Either X or Y to be inactive
b) Only X to be inactive
c) Only Y to be inactive
**d) Both X and Y to be inactive**
e) Z never deactivates

13. The initial transient in the network represents:
a) The steady state behavior
**b) The network's adjustment period**
c) Random fluctuations
d) Programming errors
e) System failure

14. What does the presence of multiple attractors in a network indicate?
a) The network is unstable
**b) The system has multiple stable states**
c) The simulation is incorrect
d) The network is too simple
e) The updates are asynchronous

15. How does the network's response to noise differ between AND and OR logic?
a) They respond identically to noise
b) AND logic amplifies noise more
c) OR logic provides better filtering
**d) AND logic provides better filtering**
e) Neither logic affects noise response


16. What is the key difference in Z's behavior between AND and OR logic circuits?
a) The total number of possible states
**b) The conditions required for Z activation**
c) The number of steady states
d) The dependency on initial conditions
e) The time needed to reach steady state

17. In the state transition graph, what path is followed when starting from state 110 (X=1, Y=1, Z=0)?
a) It remains in 110 indefinitely
b) It moves to 000
**c) It moves to 111**
d) It oscillates between 110 and 101
e) It moves randomly through states

18. Which statement is true about the network's steady states?
a) They only occur with AND logic
b) They depend on the update scheme
**c) They are the same for both AND and OR logic (000 and 111)**
d) They change with different initial conditions
e) They only exist when X is active

19. When analyzing the simulation results with quick_deactivation_step=5, what happens to node states after X is deactivated?
a) Y remains active indefinitely
**b) Both Y and Z eventually deactivate**
c) Only Z remains active
d) The system oscillates indefinitely
e) The states become random

20. What feature of the C1-FFL network makes it useful for biological signal processing?
a) Its ability to generate random patterns
b) Its large number of attractors
**c) Its ability to filter out brief input signals**
d) Its capacity to amplify weak signals
e) Its oscillatory behavior



21. True/False: In a C1-FFL network with AND logic, Z can be active even when X is inactive.
**Answer: False**

22. True/False: The synchronous update scheme means that all nodes update their states simultaneously at each time step.
**Answer: True**

23. True/False: Changing from AND to OR logic affects the number of attractors in our network.
**Answer: False**

24. True/False: The delay in Y's activation helps the network filter out transient signals.
**Answer: True**

25. True/False: In the OR logic configuration, Z requires both X and Y to be inactive to deactivate.
**Answer: True**

26. What happens to network dynamics if we remove the delay in Y's activation?
a) The network becomes unstable
**b) The network loses its noise filtering capability**
c) New attractors emerge
d) X becomes independent of Y
e) Z becomes permanently active

27. How do the initial conditions affect the network's behavior?
a) They only matter for OR logic
b) They determine the number of attractors
**c) They determine which attractor the system reaches**
d) They affect the update scheme
e) They have no effect on long-term behavior

28. Which statement about the state transition graph is correct?
**a) It shows all possible state transitions under the given update rules**
b) It depends on the initial conditions
c) It changes with different simulation times
d) It only shows stable states
e) It represents only transient behaviors

29. What biological scenario could this FFL network model?
a) Cell division
**b) Gene regulation with transcriptional delay**
c) Protein degradation
d) DNA replication
e) Membrane transport

30. How would introducing randomness in the update scheme affect the network?
a) It would create new steady states
**b) It would make state transitions non-deterministic**
c) It would eliminate all attractors
d) It would remove the delay in Y
e) It would change the logic gates

