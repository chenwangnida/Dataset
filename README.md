# Augmented WSC08 and WSC09 Dataset
The new benchmark inherits the functionalities provided by services in benchmark dataset WSC-08 and WSC-09 and QoS attributes of web services in the benchmark dataset QWS. The number of web services in the service repository is doubled (with much bigger searching space).


## Introduction
Both WSC08 and WSC09 dataset includes a set of composition tasks. Each composition task consists of three XML files, which serve as input files of our algorithm. These files includes services-output.xml (i.e., a set of services with instances of inputs and outputs, and values of QoS), problem.xml (i.e., a service request that consists of required inputs and required outputs), and taxonomy.owl (i.e, a subclass hierarchy of the OWL-S Profile concept). Based on the semantics described in the taxonomy.owl file, it is feasible to perform Taxonomy-based matchmaking based on the concepts that are associated with input and output instances. 
