|    | Path                                                                          | Change                               | Comment | ER         | Link                                 |
|----|-------------------------------------------------------------------------------|--------------------------------------|---------|------------|--------------------------------------|
| 1  | paths.[*].[*].requestBody.content.[*].[*]. examples                           | add-examples-object-for-request-body |         | annotation | add-examples-object-for-request-body |
| 2  | paths.[*].[*].requestBody.content.[*].[*].examples. [*]                       | add-additional-examples-object       |         | annotation | add-additional-examples-object       |
| 3  | paths.[*].[*].requestBody.content.[*].[*].examples.[*].value. <value>         | update-example-value                 |         | annotation | update-example-value                 |
| 4  | paths.[*].[*].requestBody.content.[*].[*].examples. [*]                       | update-name-of-example               |         | annotation | update-name-of-example               |
| 5  | paths.[*].[*].requestBody.content.[*].[*].examples.[*].externalValue. <value> | update-external-value-of-example     |         | annotation | update-external-value-of-example     |
| 6  |                                                                               | remove-external-value-of-example     |         | annotation | remove-external-value-of-example     |
| 7  | paths.[*].[*].requestBody.content.[*].[*].examples.[*].summary. <value>       | add-summary-of-example               |         | annotation | add-summary-of-example               |
| 8  | paths.[*].[*].requestBody.content.[*].[*].examples.[*].summary. <value>       | update-summary-of-example            |         | annotation | update-summary-of-example            |
| 9  | paths.[*].[*].requestBody.content.[*].[*].examples.[*].summary. <value>       | remove-summary-of-example            |         | annotation | remove-summary-of-example            |
| 10 | paths.[*].[*].requestBody.content.[*].[*].examples.[*].description. <value>   | add-description-of-example           |         | annotation | add-description-of-example           |
| 11 | paths.[*].[*].requestBody.content.[*].[*].examples.[*].description. <value>   | update-description-of-example        |         | annotation | update-description-of-example        |
| 12 | paths.[*].[*].requestBody.content.[*].[*].examples.[*].description. <value>   | remove-description-of-example        |         | annotation | remove-description-of-example        |
