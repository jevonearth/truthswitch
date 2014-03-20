TruthSwitch
===========

The truth is out there.


Data
---
TruthSwitch is a dataset suitable to load into a SIP switch.
The dataset is switch vendor neutral, but may resemble data from some telecom carriers.

Glue
---
TruthSwitch is also a set of glue tools that are vendor switch specific. The glue attempts to take the dataset and load it into the switch, following the standard interfaces of that switch. The tools also measure the time it takes to do such operations. The complexity of the tools for a specific switch represents the complexity of the switch itself.

Load
---
TruthSwitch is a set of simple load tests. It generates SIP call traffic based on the above data set, and runs that traffic against the given switch. TruthSwitch records the performance and latency for this base set of tests.

TruthSwitch is an idea, it doesn't exist.
