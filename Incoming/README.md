# Incoming data directory

All of the files here can be tested by running
```
ontopilot.py --reason make ontology
```

The file you run should be named "unreasoned_data.ttl" (making sure to rename files appropriately when finished!)

# A simple test
[unreasoned_data.ttl](unreasoned_data.ttl)

This file does not produce any errors and seems to work as expected.

# FIMS output test (single record sample)
[unreasoned_data_sample.ttl](unreasoned_data_sample.ttl)

This file reproduces (mostly) output from the FIMS system using the [biocode-fims-configurator](https://github.com/biocodellc/biocode-fims-configurator).  This file does not produce any errors and seems to work as expected.  It is annotated with a couple of needed changes to FIMS output which can be easily corrected. 

# Presence/absence test
[unreasoned_data_measurements.ttl](unreasoned_data_measurements.ttl)

This file does not produce any errors but does not deliver the inferences i would expect--- that is,  we should be inferring "leaves absent" with an upper count specified of 0
