---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "couchbase_bucket_manager Resource - terraform-provider-couchbase"
subcategory: ""
description: |-
  Manage buckets in couchbase
---

# couchbase_bucket_manager (Resource)

Manage buckets in couchbase



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String) Bucket name
- **ram_quota_mb** (Number) Ram quota for bucket

### Optional

- **bucket_type** (String) Bucket type:
memcached
ephemeral
membase
- **compression_mode** (String) Compression mode:
off
active
passive
- **conflict_resolution_type** (String) Conflict resolution type:
seqno
lww
- **durability_level** (Number) Durability level:
0
1
2
3
- **eviction_policy_type** (String) Eviction policy type:
fullEviction
valueOnly
nruEviction
noEviction
- **flush_enabled** (Boolean) Bucket flush enable/disable
- **id** (String) The ID of this resource.
- **max_expire** (Number) Max expiry in seconds
- **num_replicas** (Number) Number of bucket replicas
- **replica_index_disable** (Boolean) Bucket index replicas

