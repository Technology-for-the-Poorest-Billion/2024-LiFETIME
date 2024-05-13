# Project Objectives from LiFETIME
### Objective One: Review existing literature on lithium-ion cell modeling. Consider metrics such as model complexity, applicability to real-world cells, accuracy, and flexibility (i.e. is the model specific to one cell, or could it be used generally).

### Objective Two: Building on the knowledge gained from literature, develop a model suitable for practical analysis of real-world cells. The goal here is to produce a model which captures the complexity of Li-Ion cells well enough for sufficiently accurate modeling (you will need to decide what ‘sufficient’ means), without being so complex that it’s either highly specific to one cell, or impractical to measure/infer parameters from a cell. This could be achieved by replicating/combining elements of models from literature or developing a novel model.

### Objective Three: Validate the model against cell cycling data and discuss how well it captures real cell behaviour, consider what trade-offs were necessary for practical model implementation. What do you need to be able to measure/infer from a real cell for a suitably accurate model? Consider evaluating the model for a range of possible uses e.g. on-device implementation, power requirements, synthetic data generation, unsupervised machine learning coupling.

# Initial proposal on Thursday 11am requiring:

### Each team is asked to address the following elements in a markdown document. Students will have 10 minutes to present their idea, with a few slides as appropriate, followed by a discussion. 
- Brief overview of the problem, context and engineering approach to tackle the problem
- Technical presentation of the proposal
- Evaluate its value in the context of the project. What will it solve, is it safe, etc. Check Lara’s slides for what to cover. 
- Project management plan
  - Present team members’ strengths and weaknesses to tackle the proposal
  - Identify skills required, and training needed
  - Present a development timeline
- Costing, parts required
- Risk assessment for the work done by the students.
- Contingency plan
  - What could possibly go wrong?
  - What would you do when it happens?

### We need to:
- Understand the problem better
  - Physics of degradation
  - What indicates different modes of degradation (can it be inferred from the data?)
  - EIS
  - ECMs for relevant batteries
- Define our own objectives more precisely, our approach, division of work
- Plan time… Gantt chart? What are our aims and who is going to focus on what

### Questions for team:
- What is data from (is it EIS, charging), format
- Can you add the data to the repository
- Which battery type is the data from, can we focus on this or do we need to consider various cell types?

An interesting paper:
Zhang, Y., Tang, Q., Zhang, Y. et al. Identifying degradation patterns of lithium ion batteries from impedance spectroscopy using machine learning. Nat Commun 11, 1706 (2020). https://doi.org/10.1038/s41467-020-15235-7

https://youtu.be/_lkkm3CHuJA?si=D884nAByqnKl3JT3
https://github.com/rochan17/degradation-patterns-of-lithium-ion-batteries-from-impedance-spectroscopy
https://www.nature.com/articles/s41467-020-15235-7#citeas
