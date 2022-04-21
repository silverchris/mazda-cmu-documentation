
# Dbus interface API

**com.jci.tts**


## Methods

### ConnectToTTS



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clientName** | *in* | *s* |  |
| **result** | *out* | *i* |  |


### DisconnectFromTTS



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clientName** | *in* | *s* |  |
| **result** | *out* | *i* |  |


### PlayText



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clientName** | *in* | *s* |  |
| **string** | *in* | *s* |  |


### PausePlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clientName** | *in* | *s* |  |


### ResumePlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clientName** | *in* | *s* |  |


### AbortPlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **clientName** | *in* | *s* |  |



## Signals

### Status



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **result** | ** | *i* |  |

