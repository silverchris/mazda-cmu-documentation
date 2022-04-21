
# Dbus interface API

**com.jci.itt**


## Methods

### RequestMemoryInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **memInfo** | *out* | *(a(ius)u)* |  |


### ProcessTag



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tagStoreStatus** | *out* | *i* |  |
| **memInfo** | *out* | *(a(ius)u)* |  |


### GetTaggingAvailability



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enableTagging** | *out* | *i* |  |



## Signals

### TaggingAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enableTagging** | *in* | *i* |  |


### TagTransfer



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tagTransferStatus** | *in* | *i* |  |
| **memInfo** | *in* | *(a(ius)u)* |  |


### TaggingErrorDevice



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **tagTransferStatus** | *in* | *i* |  |

