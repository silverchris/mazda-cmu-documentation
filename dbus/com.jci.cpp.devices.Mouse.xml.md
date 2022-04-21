
# Dbus interface API

**com.jci.cpp.devices.Mouse**


## Methods

### buttonClick



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **button** | *in* | *i* |  |
| **exception** | *out* | *i* |  |


### buttonPress



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **button** | *in* | *i* |  |
| **exception** | *out* | *i* |  |


### buttonRelease



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **button** | *in* | *i* |  |
| **exception** | *out* | *i* |  |


### enumerate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **exception** | *out* | *i* |  |
| **names** | *out* | *as* |  |


### move



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **x** | *in* | *i* |  |
| **y** | *in* | *i* |  |
| **z** | *in* | *i* |  |
| **exception** | *out* | *i* |  |


### moveAxis



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **axis** | *in* | *i* |  |
| **distance** | *in* | *i* |  |
| **exception** | *out* | *i* |  |


### scroll



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **x** | *in* | *i* |  |
| **y** | *in* | *i* |  |
| **z** | *in* | *i* |  |
| **exception** | *out* | *i* |  |


### scrollAxis



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **name** | *in* | *s* |  |
| **axis** | *in* | *i* |  |
| **distance** | *in* | *i* |  |
| **exception** | *out* | *i* |  |



## Signals
