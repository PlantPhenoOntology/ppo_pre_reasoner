# Incoming data directory

All of the files here can be tested by running
```
ontopilot.py --reason make ontology
```

The file you run should be named "unreasoned_data.ttl" (making sure to rename files appropriately when finished!)

# A simple test:
[unreasoned_data.ttl](unreasoned_data.ttl)
This file does not produce any errors and seems to work as expected.

# A sample of what data looks like coming out of the FIMS system:
[unreasoned_data_sample.ttl](unreasoned_data_sample.ttl)
This file does not produce any errors and seems to work as expected.  It is annotated with needed changes to FIMS

# Testing measurement features:
[unreasoned_data_measurements](unreasoned_data_measurements.ttl)
This file does not produce any errors but does not deliver the inferences i would expect--- that is,  we should be inferring "leaves absent" with an upper count specified of 0
