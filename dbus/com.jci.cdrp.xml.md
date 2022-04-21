
# Dbus interface API

**com.jci.cdrp**


## Methods

### SetConfirmationDialogResult



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **index** | *in* | *u* |  |
| **serialId** | *in* | *s* |  |
| **size** | *in* | *u* |  |


### SetDeviceSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **index** | *in* | *u* |  |
| **serialId** | *in* | *s* |  |
| **size** | *in* | *u* |  |


### GetConfirmationDialogRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **index** | *in* | *u* |  |



## Signals

### ConnectedDeviceSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **index** | ** | *u* |  |
| **serialId** | ** | *s* |  |
| **size** | ** | *u* |  |


### ConfirmationDialogSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **friendName** | ** | *s* |  |
| **friendNameSize** | ** | *u* |  |
| **serialId** | ** | *s* |  |
| **serialIdSize** | ** | *u* |  |


### ErrorNotificationSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **errorType** | ** | *u* |  |

