# DMN Patterns Demo
This demo covers the Ranking and Ordered List Patterns in DMN
## DMN Patterns presentation by Trisotech and Red Hat
https://www.youtube.com/watch?v=0hQEMMRVHjA

## Running the demo locally
### Requirements
 * Java 17
 * Maven 3.x

### Executing
```
mvn quarkus:dev
```

Open the OpenAPI UI to test the DMN Endpoints at http://localhost:8080/q/swagger-ui or use the UI from http://localhost:8080/openapi-ui-forms/index.html (use `/q/openapi` as the value for the field `OpenAPI URL`)

Sample request payload:
```json
{
  "Vaccine List": [
    "Gamaleya Scientific Research Institute",
    "Johnson & Johnson & Janssen Pharmaceuticals",
    "Moderna",
    "Novavax",
    "Pfizer & BioNTech",
    "Sinovac",
    "University of Oxford & AstraZeneca"
  ]
}
```