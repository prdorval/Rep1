# AI to VPN to Customers


## Naming convention
Our Gateway: <SP>_vpn_gateway  
Customer Gateway: <customer>_customer_gateway
Connection Instance: to_<customer>
VPN Routes: to_<customer>_nets

## Gateways
### Our Gateway
Title: <Service Provider Name (SP)>
* vpc_id
* tags


## <Customer1>
### Customer Router 
Title: <Customer Name>
* bgp_asn
* ip_address
* type
* tags

### Connection Instance
* vpn_gateway_id
* customer_gateway_id
* type
* tags
* static_routes_only

### Customer Routes
* destination_cidr_block
* vpn_connection_id


## <Customer2>
### Customer Router
* bgp_asn
* ip_address
* type
* tags

### Connection Instance
* vpn_gateway_id
* customer_gateway_id
* type
* tags
* static_routes_only

### Customer Routes
* destination_cidr_block
* vpn_connection_id
