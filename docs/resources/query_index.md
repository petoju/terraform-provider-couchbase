---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "couchbase_query_index Resource - terraform-provider-couchbase"
subcategory: ""
description: |-
  Manage query indexes in couchbase
---

# couchbase_query_index (Resource)

Manage query indexes in couchbase



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **bucket** (String) Query index bucket name
- **fields** (List of String) Query index fields
- **name** (String) Query index name

### Optional

- **condition** (String) Query index where statement
- **id** (String) The ID of this resource.
- **num_replica** (Number) Query index number of replica


