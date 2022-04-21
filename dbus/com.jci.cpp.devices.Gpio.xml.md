
# Dbus interface API

**com.jci.cpp.devices.Gpio**


## Methods

### enumerate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **exception** | *out* | *i* |  |
| **names** | *out* | *as* |  |


### getValue



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **exception** | *out* | *i* |  |
| **value** | *out* | *b* |  |


### setValue



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **value** | *in* | *b* |  |
| **exception** | *out* | *i* |  |
| **changed** | *out* | *b* |  |



## Signals
