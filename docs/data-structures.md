# Data Structures

The entire project will be built on a foundation of gRPC APIs. Therefore, all the domain driven entity data structures will be based on Google Protobuf.
The proto files can then be imported into gRPC definitions in subsequent API projects or used in message producers/consumers. 

## Project Structure

[https://github.com/osetrm/osetrm-schema-proto](https://github.com/osetrm/osetrm-schema-proto)

The proto projects are organized in a Maven parent-child structure. 

- osetrm-schema-proto
    - osetrm-schema-proto-common
    - osetrm-schema-proto-instrument
    - osetrm-schema-proto-legal-entity
    - osetrm-schema-proto-trade
