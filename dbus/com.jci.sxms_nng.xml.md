
# Dbus interface API

**com.jci.sxms_nng**


## Methods

### GetDataServiceSubscriptions



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |


### Apogee\_CreateCollectionReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mbr** | *in* | *((dd)(dd))* |  |
| **types** | *in* | *u* |  |
| **collectionID** | *out* | *u* |  |
| **return\_value** | *out* | *u* |  |


### Apogee\_ModifyCollectionReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | *in* | *u* |  |
| **mbr** | *in* | *((dd)(dd))* |  |
| **return\_value** | *out* | *u* |  |


### Apogee\_RemoveCollectionReq



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | *in* | *u* |  |
| **return\_value** | *out* | *u* |  |


### Apogee\_GetBSAList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **mbr** | *in* | *((dd)(dd))* |  |
| **bsaList** | *out* | *(a(u))* |  |
| **return\_value** | *out* | *u* |  |


### Apogee\_SetExtractionFilter



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | *in* | *u* |  |
| **mbr** | *in* | *((dd)(dd))* |  |
| **bsaList** | *in* | *(a(u))* |  |
| **return\_value** | *out* | *u* |  |


### Apogee\_ExtractData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | *in* | *u* |  |
| **type** | *in* | *u* |  |
| **return\_value** | *out* | *u* |  |


### AGWeather\_GetData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **type** | *in* | *u* |  |
| **return\_value** | *out* | *u* |  |



## Signals

### Apogee\_DataAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | ** | *u* |  |
| **types** | ** | *u* |  |


### Apogee\_RealTimeFlowData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | ** | *u* |  |
| **flowVector** | ** | *(a(ua(uu(a(yy))(a(yy))u)))* |  |


### Apogee\_P1FlowData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | ** | *u* |  |
| **flowVector** | ** | *(a(ua(uu(a(yy))(a(yy))u)))* |  |


### Apogee\_P2FlowData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | ** | *u* |  |
| **flowVector** | ** | *(a(ua(uu(a(yy))(a(yy))u)))* |  |


### Apogee\_P3FlowData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | ** | *u* |  |
| **flowVector** | ** | *(a(ua(uu(a(yy))(a(yy))u)))* |  |


### Apogee\_P4FlowData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | ** | *u* |  |
| **flowVector** | ** | *(a(ua(uu(a(yy))(a(yy))u)))* |  |


### Apogee\_RampData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | ** | *u* |  |
| **rampData** | ** | *(a(u((a(y))(a(u))u)))* |  |


### Apogee\_ConstructionIncidentData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **collectionID** | ** | *u* |  |
| **ciData** | ** | *(a(uuy(uyyyuy)((dd)s)ys))* |  |


### DataServiceSubscription



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dataSubscriptions** | ** | *(a(uu))* |  |


### AGweather\_DatasetStart



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **product** | ** | *u* |  |


### AGweather\_NowRadData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nowRadData** | ** | *(u(dd)(dd)uusu)* |  |


### AGweather\_FrontData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **frontData** | ** | *(uu(a(dd))u)* |  |


### AGweather\_SurfaceIsobar



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isobarData** | ** | *(u(a(dd))du)* |  |


### AGweather\_PressureCenter



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pressureCenterData** | ** | *(u(a(dd))udu)* |  |


### AGweather\_StormAttributes



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stormAttributesData** | ** | *(u(a(dd))sduddu)* |  |


### AGweather\_StormPosition



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stormPositionData** | ** | *(u(a(dd))ssu(ddddd)uuu(a(u(a(dd))d)))* |  |


### AGweather\_DatasetStop



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **product** | ** | *u* |  |

