# stack-info

## Inputs

<!-- AUTO-DOC-INPUT:START - Do not remove or modify this section -->

|   INPUT   |  TYPE  | REQUIRED | DEFAULT |       DESCRIPTION        |
|-----------|--------|----------|---------|--------------------------|
| INFO_FILE | string |   true   |         | Stack info file to parse |

<!-- AUTO-DOC-INPUT:END -->

## Outputs

<!-- AUTO-DOC-OUTPUT:START - Do not remove or modify this section -->

|     OUTPUT      |  TYPE  |             DESCRIPTION              |
|-----------------|--------|--------------------------------------|
| assume-role-arn | string |        Worker role to assume         |
| aws-account-id  | string |            AWS account ID            |
|  states-bucket  | string | S3 bucket for Terraform remote state |

<!-- AUTO-DOC-OUTPUT:END -->
