
# Dbus interface API

**com.jci.cpp.devices.Display**


## Methods

### enumerate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **exception** | *out* | *i* |  |
| **names** | *out* | *as* |  |


### getContrast



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **exception** | *out* | *i* |  |
| **contrast** | *out* | *q* |  |


### getContrastSteps



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **exception** | *out* | *i* |  |
| **contrast** | *out* | *q* |  |


### setContrast



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **contrast** | *in* | *q* |  |
| **exception** | *out* | *i* |  |
| **changed** | *out* | *b* |  |



## Signals
