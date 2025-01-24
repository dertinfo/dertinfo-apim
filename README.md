# dertinfo-apim

This repos contains the IaC and pipelines for setting up the base infrastructure for APIM. 

This is a public repository and is therefore unsuitable for storing the configuration as the configuration for the API will have references to may peices of information that would resut in a reduced security posture.

Due to this the configuration for APIM is stored in a Azure DevOps Repository independent of this infrastucture repository. 

If updates to the APIM instance are rolled out by Infrastucture as code it is imperitive that the state configuration is also released.  