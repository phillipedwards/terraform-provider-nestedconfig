---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "nestedconfig Provider"
subcategory: ""
description: |-
  
---

# nestedconfig Provider



## Example Usage

```terraform
# Copyright (c) HashiCorp, Inc.
# SPDX-License-Identifier: MPL-2.0

provider "scaffolding" {
  # example configuration here
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `access_key` (String, Sensitive) Some fake access key

### Optional

- `nested_config` (Block List, Max: 1) (see [below for nested schema](#nestedblock--nested_config))

<a id="nestedblock--nested_config"></a>
### Nested Schema for `nested_config`

Required:

- `nested_access_key` (String, Sensitive) Some fake nested access key
