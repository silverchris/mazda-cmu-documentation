
# Dbus interface API

**com.jci.cpp.devices.Keyboard**


## Methods

### enumerate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **exception** | *out* | *i* |  |
| **names** | *out* | *as* |  |


### keyClick



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **code** | *in* | *i* |  |
| **shift** | *in* | *b* |  |
| **exception** | *out* | *i* |  |


### keyPress



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **code** | *in* | *i* |  |
| **exception** | *out* | *i* |  |


### keyRelease



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **code** | *in* | *i* |  |
| **exception** | *out* | *i* |  |


### keySequence



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **string** | *in* | *s* |  |
| **exception** | *out* | *i* |  |



## Signals
