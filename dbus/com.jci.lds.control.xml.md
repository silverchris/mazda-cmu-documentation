
# Dbus interface API

**com.jci.lds.control**


## Methods

### ReadControl



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **command** | *in* | *i* |  |


### DRTestScreenRequest



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dRUnitTestScreenRequest** | *in* | *i* |  |


### GetDRUnitStatus\_sync



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connected** | *out* | *b* |  |
| **status** | *out* | *b* |  |
| **result** | *out* | *i* |  |


### GetLastKnownPosition\_sync



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **positionAccuracy** | *out* | *i* |  |
| **uTCtime** | *out* | *t* |  |
| **latitude** | *out* | *d* |  |
| **longitude** | *out* | *d* |  |
| **altitude** | *out* | *i* |  |
| **heading** | *out* | *d* |  |
| **velocity** | *out* | *d* |  |
| **horizontalAccuracy** | *out* | *d* |  |
| **verticalAccuracy** | *out* | *d* |  |
| **result** | *out* | *i* |  |


### SetLastKnownPosition\_sync



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **positionAccuracy** | *in* | *i* |  |
| **uTCtime** | *in* | *t* |  |
| **latitude** | *in* | *d* |  |
| **longitude** | *in* | *d* |  |
| **altitude** | *in* | *i* |  |
| **heading** | *in* | *d* |  |
| **velocity** | *in* | *d* |  |
| **horizontalAccuracy** | *in* | *d* |  |
| **verticalAccuracy** | *in* | *d* |  |
| **result** | *out* | *i* |  |


### DRReloadRequest





## Signals

### ReadStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **commandReply** | ** | *i* |  |
| **status** | ** | *i* |  |

