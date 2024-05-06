---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "grafana_oncall_integration Data Source - terraform-provider-grafana"
subcategory: "OnCall"
description: |-
  HTTP API https://grafana.com/docs/oncall/latest/oncall-api-reference/integrations/
---

# grafana_oncall_integration (Data Source)

* [HTTP API](https://grafana.com/docs/oncall/latest/oncall-api-reference/integrations/)

## Example Usage

```terraform
data "grafana_oncall_integration" "example_integration" {
  id = "CEXAMPLEID123"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `id` (String) The integration ID.

### Read-Only

- `name` (String) The integration name.