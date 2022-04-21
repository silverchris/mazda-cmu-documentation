
# Dbus interface API

**com.jci.blm_nms**


## Methods

### GetConnectionState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **connectionState** | *out* | *i* |  |


### GetConnectionState\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **connectionState** | *out* | *i* |  |


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


### SetWiFiAutoconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **state** | *in* | *b* |  |


### SetWiFiAutoconnect\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **state** | *in* | *b* |  |


### GetWiFiAutoconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **state** | *out* | *b* |  |


### GetWiFiAutoconnect\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **state** | *out* | *b* |  |


### SetModemAutoconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **state** | *in* | *b* |  |


### SetModemAutoconnect\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **state** | *in* | *b* |  |


### GetModemAutoconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **state** | *out* | *b* |  |


### GetModemAutoconnect\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **state** | *out* | *b* |  |


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


### DHCP\_ServerGetClients



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **clients** | *out* | *(a(ssss))* |  |


### DHCP\_ServerGetClients\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **clients** | *out* | *(a(ssss))* |  |


### ActivateNAT



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **enable** | *in* | *b* |  |


### ActivateNAT\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **enable** | *in* | *b* |  |


### AdvancedRouting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **enable** | *in* | *b* |  |


### AdvancedRouting\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **enable** | *in* | *b* |  |


### SetHostname



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **hostname** | *in* | *s* |  |


### SetHostname\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **hostname** | *in* | *s* |  |


### GetHostname



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **hostname** | *out* | *s* |  |


### GetHostname\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **hostname** | *out* | *s* |  |


### MonitorInterface



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **turn** | *in* | *b* |  |


### MonitorInterface\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **turn** | *in* | *b* |  |


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
| **network** | *in* | *(ssibs)* |  |
| **networkId** | *out* | *i* |  |


### WIFI\_AddNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **network** | *in* | *(ssibs)* |  |
| **networkId** | *out* | *i* |  |


### WIFI\_AddNetwork\_Ex



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **network** | *in* | *(ssiibs(ssss)(iiiii))* |  |
| **networkId** | *out* | *i* |  |


### WIFI\_AddNetwork\_Ex\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **network** | *in* | *(ssiibs(ssss)(iiiii))* |  |
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


### WIFI\_UpdateNetworkPass



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *u* |  |
| **password** | *in* | *s* |  |


### WIFI\_UpdateNetworkPass\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *u* |  |
| **password** | *in* | *s* |  |


### WIFI\_UpdateConfiguredNetwork



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |
| **network** | *in* | *(ssiibs(ssss)(iiiii))* |  |


### WIFI\_UpdateNetwork\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **networkId** | *in* | *i* |  |
| **network** | *in* | *(ssiibs(ssss)(iiiii))* |  |


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


### WIFI\_GetScanResults



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **scanList** | *out* | *(a(ssuuuuuuui))* |  |


### WIFI\_GetScanResults\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **scanList** | *out* | *(a(ssuuuuuuui))* |  |


### WIFI\_GetConfiguredNetworks



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netList** | *out* | *(a(ussibsi))* |  |


### WIFI\_GetConfiguredNetworks\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netList** | *out* | *(a(ussibsi))* |  |


### WIFI\_GetConfiguredNetworks\_Ex



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netList** | *out* | *(a(ussiibs(ssss)(iiiii)))* |  |


### WIFI\_GetConfiguredNetworks\_Ex\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netList** | *out* | *(a(ussiibs(ssss)(iiiii)))* |  |


### WIFI\_GetNetCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netCount** | *out* | *i* |  |
| **maxNetCount** | *out* | *i* |  |


### WIFI\_GetNetCount\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netCount** | *out* | *i* |  |
| **maxNetCount** | *out* | *i* |  |


### WIFI\_GetConnectionInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **connInfo** | *out* | *(u(ssuuuuuuui))* |  |


### WIFI\_GetConnectionInfo\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **connInfo** | *out* | *(u(ssuuuuuuui))* |  |


### WIFI\_GetCombinedNetworksList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netList** | *out* | *(a(ussiiii))* |  |


### WIFI\_GetCombinedNetworksList\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **netList** | *out* | *(a(ussiiii))* |  |


### AP\_SelectConfiguration



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **secType** | *in* | *i* |  |


### AP\_SelectConfiguration\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **secType** | *in* | *i* |  |


### AP\_GetSelectedConfiguration



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **secType** | *out* | *i* |  |


### AP\_GetSelectedConfiguration\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **secType** | *out* | *i* |  |


### AP\_SetHostConfig



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **config** | *in* | *(ssib)* |  |


### AP\_SetHostConfig\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **config** | *in* | *(ssib)* |  |


### AP\_GetHostConfig



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **secSettings** | *in* | *i* |  |
| **config** | *out* | *(ssib)* |  |


### AP\_GetHostConfig\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **secSettings** | *in* | *i* |  |
| **config** | *out* | *(ssib)* |  |


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


### AP\_GetBlacklist



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **list** | *out* | *(as)* |  |


### AP\_GetBlacklist\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **ifcId** | *in* | *i* |  |
| **list** | *out* | *(as)* |  |


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


### Get\_ModemList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **params** | *out* | *(a(iisssssssibas))* |  |


### Get\_ModemList\_Async



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **params** | *out* | *(a(iisssssssibas))* |  |


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



## Signals

### ConnectResult



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **reqId** | ** | *i* |  |
| **result** | ** | *i* |  |


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


### WIFI\_ScanResultsReady



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |


### InterfaceWiFiModeChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **mode** | ** | *i* |  |


### WIFI\_ApClientConnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **bssid** | ** | *s* |  |


### WIFI\_ApClientDisconnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **ifcId** | ** | *i* |  |
| **bssid** | ** | *s* |  |


### ConnectionStateChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connState** | ** | *i* |  |


### WifiStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *(iiiiiu)* |  |


### BLMStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *(i)* |  |


### ConnectionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *(iiitt)* |  |

