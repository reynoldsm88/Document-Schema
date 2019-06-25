# World Modelers Document Management
This repository aims to establish a framework for managing documents collected and curated _prior_ to these documents being used by machine reading software. There are 3 primary goals for this effort:

1. Ensure that documents available to readers are consistently structured.
2. Ensure traceability of documents across the World Modelers pipeline.
3. Ensure that World Modeler teams understand the document schema as well as how to access the documents.

## Schema
The `document-schema.json` file contains a [JSON Schema](http://json-schema.org/) for World Modeler documents prior them being processed by machine reading software. This schema file can be loaded to [the JSON Schema tool](https://jsonschema.net/) for for review through a graphical interface.

This schema was collaboratively designed by World Modeler teams at the UAZ hackathon on 6/11/2019. The goal was to create a flexible schema that is extensible to a wide range of document types and use cases, but maintains key information about document provenance.