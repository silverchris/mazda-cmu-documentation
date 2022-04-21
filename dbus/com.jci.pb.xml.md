
# Dbus interface API

**com.jci.pb**


## Methods

### Import



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **import\_request** | *in* | *u* |  |
| **import\_type** | *in* | *i* |  |
| **filter\_type** | *in* | *u* |  |
| **device\_id** | *in* | *u* |  |
| **import\_request\_reply** | *out* | *u* |  |
| **import\_error** | *out* | *i* |  |


### AutoDownloadSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_id** | *in* | *u* |  |
| **import\_type** | *in* | *i* |  |
| **setting\_type** | *in* | *i* |  |
| **status** | *out* | *i* |  |
| **settingsValue** | *out* | *b* |  |


### ContactNameOrderSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **setting\_type** | *in* | *i* |  |
| **status** | *out* | *i* |  |
| **settingsValue** | *out* | *i* |  |


### AllSettingsToFactoryDefault



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### GetStringVoiced



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **audio\_focus\_behaviour** | *in* | *i* |  |
| **text\_string** | *in* | *s* |  |
| **status** | *out* | *i* |  |


### StopStringVoiced



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **audio\_focus\_behaviour** | *in* | *i* |  |
| **status** | *out* | *i* |  |


### TalkEvent



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **audio\_focus\_behaviour** | *in* | *i* |  |
| **status** | *out* | *i* |  |


### RecentMissedCallsCounterGet



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_id** | *in* | *u* |  |
| **status** | *out* | *i* |  |
| **counter\_value** | *out* | *u* |  |


### RecentMissedCallsCounterReset



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_id** | *in* | *u* |  |
| **status** | *out* | *i* |  |


### Debug



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **debug\_info\_out\_to\_file** | *in* | *b* |  |
| **debug\_info\_out\_to\_log** | *in* | *b* |  |
| **cfg\_param\_name** | *in* | *s* |  |
| **cfg\_param\_valstring** | *in* | *s* |  |
| **cfg\_param\_valbool** | *in* | *b* |  |
| **cfg\_param\_valint** | *in* | *i* |  |
| **debug\_info\_filepath** | *out* | *s* |  |


### ContactDelete



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **contact\_order\_id** | *in* | *u* |  |
| **contact\_id** | *in* | *u* |  |
| **display\_name** | *in* | *s* |  |
| **status** | *out* | *i* |  |


### CallHistoryDelete



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **call\_history\_type** | *in* | *i* |  |
| **status** | *out* | *i* |  |


### DeletePhonebookData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_id** | *in* | *u* |  |
| **phonebook\_data\_type** | *in* | *i* |  |
| **entry\_order\_id** | *in* | *u* |  |
| **entry\_id** | *in* | *u* |  |
| **display\_name** | *in* | *s* |  |
| **status** | *out* | *i* |  |


### GetPhonebookDatabaseInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **phonebook\_database\_type** | *in* | *i* |  |
| **device\_id** | *in* | *u* |  |
| **status** | *out* | *i* |  |



## Signals

### AutoDownloadSettingChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_id** | ** | *u* |  |
| **import\_type** | ** | *i* |  |
| **settingsValue** | ** | *b* |  |


### ContactNameOrderSettingChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **settingsValue** | ** | *i* |  |


### StringVoicedCompleted



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *i* |  |


### RecentMissedCallsCounterSignal



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_id** | ** | *u* |  |
| **counter\_value** | ** | *u* |  |


### PhonebookDataDeleted



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **device\_id** | ** | *u* |  |
| **phonebook\_data\_type** | ** | *i* |  |
| **entry\_id** | ** | *u* |  |
| **display\_name** | ** | *s* |  |
| **first\_name** | ** | *s* |  |
| **last\_name** | ** | *s* |  |
| **phonetic\_first\_name** | ** | *s* |  |
| **phonetic\_last\_name** | ** | *s* |  |


### ImportStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **import\_request** | ** | *u* |  |
| **import\_type** | ** | *i* |  |
| **filter\_type** | ** | *u* |  |
| **device\_id** | ** | *u* |  |
| **dbAlias** | ** | *s* |  |
| **extract\_key** | ** | *u* |  |
| **import\_status** | ** | *i* |  |
| **import\_error** | ** | *i* |  |
| **numEntriesImported** | ** | *u* |  |
| **numEntriesTotal** | ** | *u* |  |


### ContactDeleted



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **contact\_id** | ** | *u* |  |
| **display\_name** | ** | *s* |  |


### CallHistoryDeleted



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **call\_history\_type** | *in* | *i* |  |


### PhonebookDatabaseInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **phonebook\_database\_type** | ** | *i* |  |
| **device\_id** | ** | *u* |  |
| **dbAlias** | ** | *s* |  |
| **import\_status** | ** | *i* |  |
| **import\_error** | ** | *i* |  |
| **contactsCount** | ** | *u* |  |
| **callhistCount** | ** | *u* |  |
| **missedCount** | ** | *u* |  |
| **time\_dbModified** | ** | *t* |  |

