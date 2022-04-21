
# Dbus interface API

**com.jci.BLM_TIME**


## Methods

### GetClock



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nuHours** | *out* | *u* |  |
| **nuMins** | *out* | *u* |  |
| **u32Timestamp** | *out* | *u* |  |
| **u64CallTimestamp** | *out* | *t* |  |


### GetClockEx



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nuHours** | *out* | *u* |  |
| **nuMins** | *out* | *u* |  |
| **u64CallTimestamp** | *out* | *t* |  |



## Signals

### ClockChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **nuNewHours** | ** | *u* |  |
| **nuNewMins** | ** | *u* |  |
| **u32Timestamp** | ** | *u* |  |
| **u64CallTimestamp** | ** | *t* |  |

