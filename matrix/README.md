# matrix

## Inputs

<!-- AUTO-DOC-INPUT:START - Do not remove or modify this section -->

|    INPUT    |  TYPE  | REQUIRED |  DEFAULT  |                            DESCRIPTION                            |
|-------------|--------|----------|-----------|-------------------------------------------------------------------|
| STACKS_DIR  | string |   true   |           |                         Stacks directory                          |
| TRIGGER_ALL | string |  false   | `"false"` | If 'true', skips change detection and marks all stacks as changed |
|  UNITS_DIR  | string |   true   |           |                          Units directory                          |

<!-- AUTO-DOC-INPUT:END -->

## Outputs

<!-- AUTO-DOC-OUTPUT:START - Do not remove or modify this section -->

| OUTPUT |  TYPE  |           DESCRIPTION            |
|--------|--------|----------------------------------|
| STACKS | string | JSON array of all changed stacks |

<!-- AUTO-DOC-OUTPUT:END -->

