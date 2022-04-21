
# Dbus interface API

**com.jci.vdt**


## Methods

### MMUI\_Startup\_Initiated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vdt\_mmui\_init** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### DriveLogRecordingStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **record\_status** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |


### One\_HrLog\_File\_Protect\_Delete



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **one\_hrlog\_info** | *in* | *(yy)* |  |


### File\_List\_Req




### DiagnosticsMode\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **testscreen\_ID** | *in* | *q* |  |
| **return\_value** | *out* | *i* |  |


### UserMode\_Setting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | *in* | *q* |  |
| **value** | *in* | *b* |  |
| **return\_value** | *out* | *i* |  |


### UserMode\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **request\_type** | *in* | *q* |  |
| **return\_value** | *out* | *i* |  |


### PIN\_Request



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pin\_req\_type** | *in* | *q* |  |
| **value** | *in* | *q* |  |
| **return\_value** | *out* | *i* |  |


### Screen\_Req



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **vDTScreen** | *in* | *u* |  |
| **return\_value** | *out* | *i* |  |



## Signals

### Drv\_File\_List



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **file\_list** | *in* | *(ya(syub))* |  |


### UMASS\_Device\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **umass\_status** | ** | *q* |  |


### MD\_Device\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **md\_status** | ** | *q* |  |
| **is\_drvchart** | ** | *b* |  |


### ClearDataStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clr\_data\_sts** | ** | *q* |  |


### UmassTransferProgress



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **current\_count** | ** | *q* |  |
| **total\_count** | ** | *q* |  |


### ActivateDeactivateRecordingStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **recording\_status** | ** | *u* |  |


### Send\_Pin\_Validation\_Result



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pin\_validation\_result** | ** | *b* |  |


### Send\_Pin\_Updation\_Result



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **pin\_updation\_result** | ** | *b* |  |
| **req\_type** | ** | *q* |  |


### Send\_EOLConfig\_Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **eol\_config\_type** | ** | *q* |  |
| **value** | ** | *b* |  |


### Send\_HVD\_Setting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **hvd\_setting\_type** | ** | *q* |  |
| **value** | ** | *b* |  |


### Delete\_DriveRecord\_DataStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **del\_drv\_data\_sts** | ** | *q* |  |

