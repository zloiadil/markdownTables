|   | Change id                                        | ER           | Storybook                                        | Priority | AR           | Questions                     | Test   |
|---|--------------------------------------------------|--------------|--------------------------------------------------|----------|--------------|-------------------------------|--------|
| 1 | mark-optional-output-type-as-mandatory           | non-breaking | mark-optional-output-type-as-mandatory           | 2        | non-breaking | now action is remove          | exists |
| 2 | mark-mandatory-output-type-as-optional           | breaking     | mark-mandatory-output-type-as-optional           | 2        | breaking     | now action is add             | exists |
| 3 | change-output-type                               | breaking     | change-output-type                               | 2        | breaking     |                               | exists |
| 4 | add-list-type-for-output-type                    | breaking     | add-list-type-for-output-type                    | 2        | breaking     | returns 2 diff (add, replace) | exists |
| 5 | add-enum-value-in-output-type                    | breaking     | add-enum-value-in-output-type                    | 1        | breaking     |                               | exists |
| 6 | remove-enum-value-in-output-type                 | non-breaking | remove-enum-value-in-output-type                 | 2        | non-breaking |                               | exists |
| 7 | add-description-for-enum-value-in-output-type    | annotation   | add-description-for-enum-value-in-output-type    | 1        | annotation   |                               | exists |
| 8 | change-description-for-enum-value-in-output-type | annotation   | change-description-for-enum-value-in-output-type | 1        | annotation   |                               | exists |
| 9 | delete-description-for-enum-value-in-output-type | annotation   | delete-description-for-enum-value-in-output-type | 2        | annotation   |                               | exists |
