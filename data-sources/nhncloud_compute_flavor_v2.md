# Data Source: nhncloud_compute_flavor_v2

## Example Usage

```
data "nhncloud_compute_flavor_v2" "u2c2m4"{
  name = "u2.c2m4"
}
```

## Argument Reference

* `name` - (Optional) The name of the flavor to query.

## Attribute Reference

`id` is set to the ID of the found flavor. In addition, the following attributes are exported:

* `extra_specs` - The key/value pairs of metadata for the flavor.