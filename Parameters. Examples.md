|    | Path                                                                 | Change id                         | Comment | ER                                   | Link                              |
|----|----------------------------------------------------------------------|-----------------------------------|---------|--------------------------------------|-----------------------------------|
| 1  | paths.[*].[*].parameters.[*]. examples                               | add-examples-object-for-parameter |         | annotation                           | add-examples-object-for-parameter |
| 2  | paths.[*].[*].parameters.[*].examples. [*]                           | add-additional-examples-object    |         | annotation                           | add-additional-examples-object    |
| 3  | paths.[*].[*].parameters.[*].examples.[*].value. <value>             | update-example-value              |         | annotation                           | update-example-value              |
| 4  | paths.[*].[*].parameters.[*].examples. [*]                           | update-name-of-example            |         | 2 annotations (delete + add example) | update-name-of-example            |
| 5  | paths.[*].[*].parameters.[*].examples.[*].[*].externalValue. <value> | update-external-value-of-example  |         | annotation                           | update-external-value-of-example  |
| 6  | paths.[*].[*].parameters.[*].examples.[*].[*].externalValue. <value> | remove-external-value-of-example  |         | annotation                           | remove-external-value-of-example  |
| 7  | paths.[*].[*].parameters.[*].examples.[*].summary. <value>           | add-example-summary               |         | annotation                           | add-example-summary               |
| 8  | paths.[*].[*].parameters.[*].examples.[*].summary. <value>           | update-example-summary            |         | annotation                           | update-example-summary            |
| 9  | paths.[*].[*].parameters.[*].examples.[*].summary. <value>           | remove-example-summary            |         | annotation                           | remove-example-summary            |
| 10 | paths.[*].[*].parameters.[*].examples.[*].description. <value>       | add-example-description           |         | annotation                           | add-example-description           |
| 11 | paths.[*].[*].parameters.[*].examples.[*].description. <value>       | update-example-description        |         | annotation                           | update-example-description        |
| 12 | paths.[*].[*].parameters.[*].examples.[*].description. <value>       | remove-example-description        |         | annotation                           | remove-example-description        |
