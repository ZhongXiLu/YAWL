# Modelling and Analyzing YAWL in AToMPM

### Abstract

It's no surprise that nowadays, we want to model as much as possible whereas modelling can help us in varies aspects. YAWL (Yet Another Workflow Language) in particular models the workflow of a process from start to end. However, after designing such a flow, we also want to be able to derive certain properties from a given model. This research will go deeper on this analysis step and how it's done in YAWL. To be specific, I will model (a subset of) YAWL in AToMPM, creating a visual modelling environment. I will further continue by allowing the user to be able to perform some analysis (such as finding deadlock). Behind the scenes, it will map the YAWL net to a petri net where it will do the actual analysis and the results will be back imported in AToMPM to show it to the user. 

For more information, read the [final report](papers/final-report.pdf).

### Directory Structure

- `papers`: the papers I wrote for my research
  - `reading-report.pdf`: an overview of the language YAWL and a few desirable properties to have
  - `final-report.pdf`: the report of my implementation; how YAWL is modelled in AToMPM and how we can verify a model on certain properties
- `YAWL`: the YAWL formalism written in AToMPM
  - `Analysis`: transformation rules required for the analysis
  - `Simulation`: transformation rules required for the simulation
  - `ToPetriNet`: transformation rules required for the mapping to petri-nets
  - `examples`: a couple example models
