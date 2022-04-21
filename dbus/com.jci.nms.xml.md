
# Dbus interface API

**com.jci.nms**


## Methods

### GetInterfaceList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcList** | *out* | *(ai)* |  |


### GetInterfaceList\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcList** | *out* | *(ai)* |  |


### Connect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **reqId** | *out* | *i* |  |


### Connect\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **reqId** | *out* | *i* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### Disconnect\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### Abort



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **reqId** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### Abort\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **reqId** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### GetInterfaceParams



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **ifcParams** | *out* | *(iissssssssiiii)* |  |


### GetInterfaceParams\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **ifcParams** | *out* | *(iissssssssiiii)* |  |


### SetInterfaceParams



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **ifcParams** | *in* | *(ssssssii)* |  |
| **setMask** | *in* | *i* |  |


### SetInterfaceParams\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **ifcParams** | *in* | *(ssssssii)* |  |
| **setMask** | *in* | *i* |  |


### WIFI\_SetMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **mode** | *in* | *i* |  |


### WIFI\_SetMode\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **mode** | *in* | *i* |  |


### WIFI\_GetMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **mode** | *out* | *i* |  |


### WIFI\_GetMode\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **mode** | *out* | *i* |  |


### WIFI\_SelectNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |


### WIFI\_SelectNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |


### WIFI\_GetSelectNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *out* | *i* |  |


### WIFI\_GetSelectNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *out* | *i* |  |


### WIFI\_AddNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **network** | *in* | *(uussuubs(ssss)(iiiii))* |  |
| **networkId** | *out* | *i* |  |


### WIFI\_AddNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **network** | *in* | *(uussuubs(ssss)(iiiii))* |  |
| **networkId** | *out* | *i* |  |


### WIFI\_RemoveConfiguredNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |


### WIFI\_RemoveConfiguredNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |


### WIFI\_UpdateConfiguredNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **network** | *in* | *(uussuubs(ssss)(iiiii))* |  |


### WIFI\_UpdateConfiguredNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **network** | *in* | *(uussuubs(ssss)(iiiii))* |  |


### WIFI\_StartScan



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **refreshTime** | *in* | *i* |  |


### WIFI\_StartScan\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **refreshTime** | *in* | *i* |  |


### WIFI\_StopScan



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### WIFI\_StopScan\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### WIFI\_GetConfiguredNetworks



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netList** | *out* | *(a(uussuubs(ssss)(iiiii)))* |  |


### WIFI\_GetConfiguredNetworks\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netList** | *out* | *(a(uussuubs(ssss)(iiiii)))* |  |


### WIFI\_GetScanResults



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **scanList** | *out* | *(a(ssuuuuuuu(iiiii)))* |  |


### WIFI\_GetScanResults\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **scanList** | *out* | *(a(ssuuuuuuu(iiiii)))* |  |


### WIFI\_GetConnectionInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **connInfo** | *out* | *(ui(ssuuuuuuu(iiiii)))* |  |


### WIFI\_GetConnectionInfo\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **connInfo** | *out* | *(ui(ssuuuuuuu(iiiii)))* |  |


### WIFI\_SaveConfiguredNetworks



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### WIFI\_SaveConfiguredNetworks\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### AP\_SelectProfile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **profile** | *in* | *i* |  |


### AP\_SelectProfile\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **profile** | *in* | *i* |  |


### AP\_GetInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### AP\_GetInfo\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### DHCP\_ServerSetConfig



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **dhcpConf** | *in* | *(ss)* |  |


### DHCP\_ServerSetConfig\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **dhcpConf** | *in* | *(ss)* |  |


### DHCP\_ServerGetConfig



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **dhcpConf** | *out* | *(ss)* |  |


### DHCP\_ServerGetConfig\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **dhcpConf** | *out* | *(ss)* |  |


### DHCP\_ServerStart



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### DHCP\_ServerStart\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### DHCP\_ServerStop



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### DHCP\_ServerStop\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### MonitorInterface



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **turn** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### MonitorInterface\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **turn** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### SOCKET\_NewConnection



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **settings** | *in* | *(isii)* |  |
| **return\_value** | *out* | *i* |  |


### SOCKET\_NewConnection\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **settings** | *in* | *(isii)* |  |
| **return\_value** | *out* | *i* |  |


### AdvancedRouting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flag** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### AdvancedRouting\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flag** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### ActivateNAT



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flag** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### ActivateNAT\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flag** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### DHCP\_ServerGetClients



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **dhcpClients** | *out* | *(a(ssss))* |  |


### DHCP\_ServerGetClients\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **dhcpClients** | *out* | *(a(ssss))* |  |


### SetHostname



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hostname** | *in* | *s* |  |
| **return\_value** | *out* | *i* |  |


### SetHostname\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hostname** | *in* | *s* |  |
| **return\_value** | *out* | *i* |  |


### GetHostname



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hostname** | *out* | *s* |  |
| **return\_value** | *out* | *i* |  |


### GetHostname\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hostname** | *out* | *s* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetClients



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **clients** | *out* | *(a(ssss))* |  |


### AP\_GetClients\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **clients** | *out* | *(a(ssss))* |  |


### AP\_AddToBlacklist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **mac** | *in* | *s* |  |


### AP\_AddToBlacklist\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **mac** | *in* | *s* |  |


### AP\_RemoveFromBlacklist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **mac** | *in* | *s* |  |


### AP\_RemoveFromBlacklist\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **mac** | *in* | *s* |  |


### AP\_ClearBlacklist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### AP\_ClearBlacklist\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |


### AP\_SetOpenProfile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **confAp** | *in* | *(suii)* |  |
| **return\_value** | *out* | *i* |  |


### AP\_SetOpenProfile\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **confAp** | *in* | *(suii)* |  |
| **return\_value** | *out* | *i* |  |


### AP\_SetWepProfile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *in* | *((suii)(ssss))* |  |
| **return\_value** | *out* | *i* |  |


### AP\_SetWepProfile\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *in* | *((suii)(ssss))* |  |
| **return\_value** | *out* | *i* |  |


### AP\_SetWpaProfile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *in* | *((suii)(is))* |  |
| **return\_value** | *out* | *i* |  |


### AP\_SetWpaProfile\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *in* | *((suii)(is))* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetOpenProfile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *out* | *(suii)* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetOpenProfile\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *out* | *(suii)* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetWepProfile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *out* | *((suii)(ssss))* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetWepProfile\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *out* | *((suii)(ssss))* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetWpaProfile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *out* | *((suii)(is))* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetWpaProfile\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **profile** | *out* | *((suii)(is))* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetSelectedProfile



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **selected** | *out* | *i* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetSelectedProfile\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **selected** | *out* | *i* |  |
| **return\_value** | *out* | *i* |  |


### AP\_SetHiddenNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flag** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### AP\_SetHiddenNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flag** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetHiddenNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flag** | *out* | *i* |  |
| **return\_value** | *out* | *i* |  |


### AP\_GetHiddenNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **flag** | *out* | *i* |  |
| **return\_value** | *out* | *i* |  |


### WIFI\_GetScanResultsByMatch



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **matchType** | *in* | *i* |  |
| **matchValue** | *in* | *s* |  |
| **scanList** | *out* | *(a(ssuuuuuuu(iiiii)))* |  |
| **return\_value** | *out* | *i* |  |


### WIFI\_GetScanResultsByMatch\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **matchType** | *in* | *i* |  |
| **matchValue** | *in* | *s* |  |
| **scanList** | *out* | *(a(ssuuuuuuu(iiiii)))* |  |
| **return\_value** | *out* | *i* |  |


### WIFI\_EnableNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### WIFI\_EnableNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### WIFI\_DisableNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### WIFI\_DisableNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |
| **return\_value** | *out* | *i* |  |


### WIFI\_MonitorStrength



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **turn** | *in* | *b* |  |
| **rate** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### WIFI\_MonitorStrength\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | *in* | *i* |  |
| **turn** | *in* | *b* |  |
| **rate** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### Get\_ModemParams



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **mId** | *in* | *i* |  |
| **params** | *out* | *(iisssssssibas)* |  |


### Get\_ModemParams\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **mId** | *in* | *i* |  |
| **params** | *out* | *(iisssssssibas)* |  |


### Set\_ModemParams



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **mId** | *in* | *i* |  |
| **params** | *in* | *(sssss)* |  |
| **updateMask** | *in* | *i* |  |


### Set\_ModemParams\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **mId** | *in* | *i* |  |
| **params** | *in* | *(sssss)* |  |
| **updateMask** | *in* | *i* |  |


### AddModem



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **modemId** | *in* | *s* |  |
| **vendor** | *in* | *s* |  |
| **ports** | *in* | *(as)* |  |


### RemoveModem



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **modemId** | *in* | *s* |  |
| **vendor** | *in* | *s* |  |


### Debug\_ModemDump



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### Debug\_ListDump




### AP\_GetBlacklist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **list** | *out* | *(as)* |  |



## Signals

### InterfaceArrive



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |


### InterfaceDeparture



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |


### InterfaceChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **changeMask** | ** | *i* |  |


### InterfaceConnecting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |


### InterfaceDisconnecting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |


### InterfaceConnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |


### InterfaceDisconnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **reason** | ** | *i* |  |


### WifiScanResultsReady



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |


### ConnectResult



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **reqId** | ** | *i* |  |
| **result** | ** | *i* |  |


### InterfaceWiFiModeChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **mode** | ** | *i* |  |


### WiFiAPClientConnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **bssid** | ** | *s* |  |


### WiFiAPClientDisconnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **bssid** | ** | *s* |  |


### APOpenInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **config** | ** | *(suii)* |  |


### APWepInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **config** | ** | *((suii)(ssss))* |  |


### APWpaInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **config** | ** | *((suii)(is))* |  |


### InterfaceMonitorData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **statistics** | ** | *(tt)* |  |


### WifiSignalStrength



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **strength** | ** | *u* |  |

