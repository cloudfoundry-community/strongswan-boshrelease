# Bug Fixes

Fixed issues preventing traffic from being routed across the tunnels

**NOTE**: these changes changed the structure of properties. Each tunnel
definition no longer gets a `properties.strongswan.tunnels.*.subnet` parameter.
Instead, the remote subnet is specified as `properties.strongswan.remote_subnet`.
