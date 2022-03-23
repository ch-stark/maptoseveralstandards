This repository is organized the following way:

- input: contains all Kubernestes resources we want to monitor and/or create using Policies

using Policy-Generator and a PolicyGenerator-config-file we dynamically create Policies - based on the input - for different standards.


We have the three fields:

  standards:
    - NIST
  categories:
    - CM Configuration Management
  controls: 
    - CM-2 Baseline Configuration


in this example we use NIST and BSI-Grundschutz

Example:

EtcdEncryption is necessary for both standards.

but for NIST you need to set Control  CM-2 Baseline Configuration
while for BSI-Grundschutzt you need to set it under Control TBD



Note: At we end we might also use PolicySets for better grouping

