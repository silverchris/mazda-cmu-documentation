
# Dbus interface API

**com.jci.audioPlayer**


## Methods

### Open



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_id** | *out* | *i* |  |
| **result** | *out* | *i* |  |


### OpenByName



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device** | *in* | *s* |  |
| **client\_id** | *out* | *i* |  |
| **result** | *out* | *i* |  |


### Close



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_id** | *in* | *i* |  |
| **result** | *out* | *i* |  |


### PlaySync



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_id** | *in* | *i* |  |
| **fileName** | *in* | *s* |  |
| **mode** | *in* | *i* |  |
| **result** | *out* | *i* |  |


### PlayASync



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_id** | *in* | *i* |  |
| **fileName** | *in* | *s* |  |
| **mode** | *in* | *i* |  |
| **result** | *out* | *i* |  |


### AbortSync



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_id** | *in* | *i* |  |
| **fileName** | *in* | *s* |  |
| **abort\_type** | *in* | *i* |  |
| **result** | *out* | *i* |  |


### AbortASync



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_id** | *in* | *i* |  |
| **fileName** | *in* | *s* |  |
| **abort\_type** | *in* | *i* |  |
| **result** | *out* | *i* |  |



## Signals

### Exception



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **id** | ** | *n* |  |
| **message** | ** | *s* |  |

