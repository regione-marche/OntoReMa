# Example Guide

This guide describes the fields present in the body of the request for inserting a Structured Content.

To make the request, credentials will be required.

## Example

**Request Type:** POST

**URL:**
```
https://digitalhub.regione.marche.it/o/headless-delivery/v1.0/structured-content-folders/15363611/structured-contents
```

This request will insert our Structured Content into a predefined folder.

## Explanation of the fields in the request body:

- **contentStructureId**: ID of the structure being inserted.
- **externalReferenceCode**: A unique code. It is recommended to use a unique syntax to avoid conflicts.
- **title**: The title of the Structured Content.
- **taxonomyCategoryIds**: The IDs of the categories associated with this Structured Content. These can be checked in the structure's README.

### contentFields

Depending on the type of field, a different `contentFieldValue` must be set.

- **data**: String-type field, used in most cases:
  - **string**: Simple string (e.g., `example test`)
  - **integer**: Integer value (e.g., `12345`)
  - **double**: Decimal value (e.g., `123.45`)
  - **date**: Date value (e.g., `2025-01-01T01:00:00Z`)
  - **boolean**: Boolean value (e.g., `true`)
  - **radio**: Single-option field, where the value of one of the options must be inserted.
  - **select**: Single-option field, where the value of one of the options must be inserted.

- **document**: These are files or images uploaded to the site. To associate an image, it must first be uploaded via a separate request to obtain the ID.

- **structuredContentLink**: This field is used to link a Structured Content. In this case, the content ID must be provided.

### nestedContentFields

These are groups of fields that may or may not be required.

- Even if a field group is not required, it must be included in the JSON with `nestedContentFields` set as an empty array if you do not want to populate any fields.
- When inserting a `nestedContentFields`, the `contentFieldValue` field must not be set, as the values will be inside the nested fields.
