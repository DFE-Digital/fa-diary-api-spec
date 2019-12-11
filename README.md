# fa-diary-api-spec
Foster Parents' LA API OpenAPI specification

## Validating

```
$ npm i swagger-cli
$ swagger-cli validate openapi.yaml
openapi.yaml is valid
```

## Bundling into a single file
```
$ npm -i swagger-cli
$ swagger-cli bundle openapi.yaml
{
  "openapi": "3.0.0",
  "info": {
    "description": "This is an early draft of an API specification permitting a 3rd party supplier's application to retrieve records related to a set of children under care by the given local authority. Each local authority gets assigned an API key which the allows them to retrieve entries relevant to their business.",
    "version": "1.0.0",
    "title": "Fostering and Adoption Diary",
    "termsOfService": "N/A",
    "contact": {
      "name": "Jan Szumiec",
      "email": "jan.szumiec@digital.education.gov.uk"
...
```

