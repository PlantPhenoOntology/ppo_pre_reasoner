# PPO prereasoner
The PPO prereasoner takes input files containing triples generated directly from raw plant phenology data and outputs triples generated by running a reasoner over the data, in combination with the Plant Phenology Ontology, and adding full type (class assertion) information to all class instances.

# Key directories

## Incoming
This directory holds incoming turtle files with instance data that have been generated using PPO/PO terms with raw plant phenology data.  The working input file should be named `unreasoned_data.ttl`.

## Outgoing
This directory receives the pre-reasoned instance data in OWL format.  After running ontobuilder on the incoming data, the prereasoned output data will be in the file `data-reasoned.owl`.

# How to generate prereasoned output data.

1. Place the input data in a file called `Incoming/unreasoned_data.ttl`.
1. From the main project directory, run `$ ontobuilder.py --reason make ontology`.
1. The prereasoned output data will be in `Outgoing/data-reasoned.owl`.

That's it!

