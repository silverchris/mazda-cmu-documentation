
# Dbus interface API

**com.jci.time**


## Methods

### Connect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_name** | *in* | *s* |  |
| **status** | *out* | *i* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_name** | *in* | *s* |  |
| **status** | *out* | *i* |  |


### GetDatetime



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **field\_in** | *in* | *n* |  |
| **datetime\_out** | *out* | *u* |  |
| **field\_out** | *out* | *n* |  |
| **synchronized** | *out* | *y* |  |
| **status** | *out* | *u* |  |


### GetDatetimeComposite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **field\_in** | *in* | *n* |  |
| **datetime\_out** | *out* | *(nyyyyy)* |  |
| **field\_out** | *out* | *n* |  |
| **synchronized** | *out* | *y* |  |
| **status** | *out* | *u* |  |


### GetDatetimeComponents



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **base\_datetime** | *out* | *(nyyyyy)* |  |
| **timezone\_offset** | *out* | *(nyyyyy)* |  |
| **daylightsaving\_offset** | *out* | *(nyyyyy)* |  |
| **user\_offset** | *out* | *(nyyyyy)* |  |
| **synchronized** | *out* | *y* |  |
| **status** | *out* | *u* |  |


### RegisterForDatetimeChangeEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **time\_req** | *in* | *y* |  |
| **event\_time** | *in* | *(nyyyyy)* |  |
| **client\_name** | *in* | *s* |  |
| **time\_req\_out** | *out* | *y* |  |
| **event\_time\_out** | *out* | *(nyyyyy)* |  |
| **status** | *out* | *u* |  |


### UnregisterFromDatetimeChangeEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **time\_req** | *in* | *y* |  |
| **event\_time** | *in* | *(nyyyyy)* |  |
| **client\_name** | *in* | *s* |  |
| **time\_req\_out** | *out* | *y* |  |
| **event\_time\_out** | *out* | *(nyyyyy)* |  |
| **status** | *out* | *u* |  |


### RegisterForOffsetChangeEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **offset\_change\_type** | *in* | *y* |  |
| **offset\_change\_type\_out** | *out* | *y* |  |
| **status** | *out* | *u* |  |


### UnregisterFromOffsetChangeEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **offset\_change\_type** | *in* | *y* |  |
| **offset\_change\_type\_out** | *out* | *y* |  |
| **status** | *out* | *u* |  |


### SetDatetimeComponents



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **base\_datetime** | *in* | *(nyyyyy)* |  |
| **timezone\_offset** | *in* | *(nyyyyy)* |  |
| **daylightsaving\_offset** | *in* | *(nyyyyy)* |  |
| **user\_offset** | *in* | *(nyyyyy)* |  |
| **status** | *out* | *u* |  |


### SetDatetimeComposite



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **field\_in** | *in* | *n* |  |
| **datetime\_in** | *in* | *(nyyyyy)* |  |
| **field\_out** | *out* | *n* |  |
| **synchronized** | *out* | *y* |  |
| **status** | *out* | *u* |  |


### SetDatetime



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **field\_in** | *in* | *n* |  |
| **datetime\_in** | *in* | *u* |  |
| **field\_out** | *out* | *n* |  |
| **synchronized** | *out* | *y* |  |
| **status** | *out* | *u* |  |


### GetWeekDay



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **event\_time** | *in* | *(nyyyyy)* |  |
| **weekday** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### GetMonthDaysCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **event\_time** | *in* | *(nyyyyy)* |  |
| **monthdayscount** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### GetYearWeekNumber



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **event\_time** | *in* | *(nyyyyy)* |  |
| **weeknumber** | *out* | *u* |  |
| **status** | *out* | *u* |  |


### CalculateDateDiff



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **event\_time\_from** | *in* | *(nyyyyy)* |  |
| **event\_time\_to** | *in* | *(nyyyyy)* |  |
| **event\_diff** | *out* | *(nyyyyy)* |  |
| **status** | *out* | *u* |  |


### CalculateTimeDiff



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **event\_time\_from** | *in* | *(nyyyyy)* |  |
| **event\_time\_to** | *in* | *(nyyyyy)* |  |
| **event\_diff** | *out* | *(nyyyyy)* |  |
| **status** | *out* | *u* |  |


### CalculateDatetimeDiff



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **event\_time\_from** | *in* | *(nyyyyy)* |  |
| **event\_time\_to** | *in* | *(nyyyyy)* |  |
| **event\_diff** | *out* | *(nyyyyy)* |  |
| **status** | *out* | *u* |  |



## Signals

### FireEventMsg



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **time\_req** | ** | *y* |  |
| **event\_time** | ** | *(nyyyyy)* |  |
| **deviation\_time\_out** | ** | *(nyyyyy)* |  |
| **stat** | ** | *i* |  |


### OffsetChangeMsg



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **field\_out** | ** | *n* |  |
| **synchronized** | ** | *y* |  |
| **request\_out** | ** | *n* |  |

