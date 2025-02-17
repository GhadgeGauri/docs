---
title: Organization Pre-receive Hooks
intro: Use the REST API to view and modify enforcement of the pre-receive hooks that are available to an organization.
versions:
  ghes: '*'
topics:
  - API
allowTitleToDifferFromFilename: true
autogenerated: rest
---

## About organization pre-receive hooks

{% data reusables.user-settings.enterprise-admin-api-classic-pat-only %}

### Object attributes

| Name                             | Type      | Description                                               |
|----------------------------------|-----------|-----------------------------------------------------------|
| `name`                           | `string`  | The name of the hook.                                     |
| `enforcement`                    | `string`  | The state of enforcement for the hook on this repository. |
| `allow_downstream_configuration` | `boolean` | Whether repositories can override enforcement.            |
| `configuration_url`              | `string`  | URL for the endpoint where enforcement is set.            |

Possible values for `enforcement` are `enabled`, `disabled` and`testing`. `disabled` indicates the pre-receive hook will not run. `enabled` indicates it will run and reject any pushes that result in a non-zero status. `testing` means the script will run but will not cause any pushes to be rejected.

`configuration_url` may be a link to this endpoint or this hook's global configuration. Only site admins are able to access the global configuration.


<!-- Content after this section is automatically generated -->
