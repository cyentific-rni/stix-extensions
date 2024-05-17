# Extension Definitions

This folder contains two extension definition objects:

-   x-oca-coa-playbook-ext property extension and
-   x-oca-playbook new SDO extension.

## x-oca-coa-playbook-ext Extension Definition

This schema extends the Course of Action SDO with playbook references.
**Extension Definition identifier:** `extension-definition--bbc1d5c8-7ddc-4e89-be9c-f33ad02d71dd`

```json
{
    "type": "extension-definition",
    "spec_version": "2.1",
    "id": "extension-definition--bbc1d5c8-7ddc-4e89-be9c-f33ad02d71dd",
    "created_by_ref": "identity--b085a68a-bf48-4316-9667-37af78cba894",
    "created": "2022-03-31T13:00:00.000Z",
    "modified": "2024-05-16T12:44:08.273Z",
    "name": "x-oca-coa-playbook-ext Extension Definition",
    "description": "This schema extends the Course of Action SDO with playbook references.",
    "schema": "https://github.com/opencybersecurityalliance/stix-extensions/main/playbook/schemas/x-oca-coa-playbook-ext.json",
    "version": "3.0.0",
    "extension_types": ["property-extension"]
}
```

## x-oca-playbook Extension Definition

This schema creates a new object type called x-oca-playbook.
**Extension Definition identifier:** `extension-definition--809c4d84-7a6e-4039-97b4-da9fea03fcf9`

```json
{
    "type": "extension-definition",
    "spec_version": "2.1",
    "id": "extension-definition--809c4d84-7a6e-4039-97b4-da9fea03fcf9",
    "created_by_ref": "identity--b085a68a-bf48-4316-9667-37af78cba894",
    "created": "2022-03-31T13:00:00.000Z",
    "modified": "2024-05-16T12:44:08.273Z",
    "name": "x-oca-playbook Extension Definition",
    "description": "This schema creates a new object type called x-oca-playbook.",
    "schema": "https://raw.githubusercontent.com/opencybersecurityalliance/stix-extensions/main/playbook/schemas/x-oca-playbook.json",
    "version": "3.0.0",
    "extension_types": ["new-sdo"]
}
```