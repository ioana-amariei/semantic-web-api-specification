### Introduction

The purpose of this project is to add support for Semantic Augmentation of OpenAPI specification within **Swagger Editor** and **Swagger UI** tools. This enables us to  augment the existing Web API Specifications with Semantic support in order to derive both machine and human readable content in a better, more
comprehensive way.

The Web is becoming a large repository of open data, available for rich exploratory querying, machine processing such as generating visualizations, and for combining multiple data sources. The Semantic Web (Web 3.0) has been designed as a WWW extension that allows computing tools to search, combine and process content that is based on the meaning it has for us.

### Contributions
#### Swagger Editor
Swagger Editor was extended to support custom properties (i.e.,
x-same-as and x-rdf-type), suggestions and autocomplete support for the newly added extensions,
contextual suggestions and autocomplete support for concepts retrieved from Schema.org, and the
ability to convert and save an OpenAPI definition in Turtle format. 

More info available at: https://github.com/ioanabirsan/swagger-editor

#### Swagger UI
Swagger UI was extended to
incorporate Structured Data in the generated OpenAPI definition documentation using Microdata, the
retrieval of metadata from Schema.org for each element that has been augmented with semantics and
its inclusion in the generated documentation, and the association of elements from the OpenAPI
definition with concepts from the Schema.org vocabulary.

More info available at: https://github.com/ioanabirsan/swagger-ui

### Presentation
Please consult the presentation for more details: https://github.com/ioanabirsan/semantic-web-api-specification/blob/master/Licenta2019BirsanIoana/presentation.pdf

### Demo
For more details please consult **Chapter 6: Taxi Service** of the thesis: https://github.com/ioanabirsan/semantic-web-api-specification/blob/master/Licenta2019BirsanIoana/thesis.pdf

#### Autocomplete support offered by Swagger Editor for x-same-as extension
![image](https://user-images.githubusercontent.com/22713689/202901005-b1ccf893-3f63-4e11-9bfc-66d51eb6eb44.png)

#### Display of semantic details in Swagger UI
![image](https://user-images.githubusercontent.com/22713689/202901084-6a9f2557-ba1b-4705-908a-ea22d0e289b6.png)

#### Structured data for TaxiService item detected by Google Structured Data
Testing Tool
![image](https://user-images.githubusercontent.com/22713689/202901136-31dbb0d0-59a7-4011-9367-2fad96fcec62.png)



