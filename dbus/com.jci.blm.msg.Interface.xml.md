
# Dbus interface API

**com.jci.blm.msg.Interface**


## Methods

### Connect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **context\_in** | *in* | *u* |  |
| **client\_type\_in** | *in* | *i* |  |
| **callbacks\_in** | *in* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **client\_type\_out** | *out* | *i* |  |
| **callbacks\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **connection** | *out* | *u* |  |


### Disconnect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **context\_in** | *in* | *u* |  |
| **connection\_in** | *in* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### GetInstanceList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **instance\_list** | *out* | *(ua(qs))* |  |


### GetMessageList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **filter** | *in* | *(q(uu(ua(ius))))* |  |
| **request\_type** | *in* | *i* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **message\_list** | *out* | *(bbbuua(itiusss))* |  |


### GetNewMessagesList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **request\_type** | *in* | *i* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **message\_list** | *out* | *(ua(itiusss))* |  |


### GetNewMessagesInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **info** | *out* | *((ua(iub)))* |  |


### GetMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message\_id** | *in* | *t* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **message** | *out* | *((qs)tiu(iss(ua(ius)))(ua(iss(ua(ius))))ssttbu)* |  |


### SetMessageStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message\_id** | *in* | *t* |  |
| **message\_status** | *in* | *i* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### DeleteMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message\_id\_in** | *in* | *t* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **message\_id\_out** | *out* | *t* |  |


### DeleteSavedMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### GetOutgoingMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message\_id** | *in* | *t* |  |
| **send\_type** | *in* | *i* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **message** | *out* | *(ss(qs)(ua(iss(ua(ius)))))* |  |


### GetSavedMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **message** | *out* | *(ss(qs)(ua(iss(ua(ius)))))* |  |


### SendMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message** | *in* | *(ss(qs)(ua(iss(ua(ius)))))* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### SaveMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message** | *in* | *(ss(qs)(ua(iss(ua(ius)))))* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### GetAutoDownload



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **client\_type\_in** | *in* | *i* |  |
| **type** | *in* | *i* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **client\_type\_out** | *out* | *i* |  |
| **status** | *out* | *i* |  |
| **enabled** | *out* | *b* |  |


### SetAutoDownload



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **client\_type\_in** | *in* | *i* |  |
| **enabled** | *in* | *b* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **client\_type\_out** | *out* | *i* |  |
| **status** | *out* | *i* |  |


### GetNotify



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **client\_type\_in** | *in* | *i* |  |
| **type** | *in* | *i* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **client\_type\_out** | *out* | *i* |  |
| **status** | *out* | *i* |  |
| **enabled** | *out* | *b* |  |


### SetNotify



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **client\_type\_in** | *in* | *i* |  |
| **enabled** | *in* | *b* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **client\_type\_out** | *out* | *i* |  |
| **status** | *out* | *i* |  |


### StartMessagePlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message\_id** | *in* | *t* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### StartOutgoingMessagePlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message** | *in* | *(ss(qs)(ua(iss(ua(ius)))))* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### PauseMessagePlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### ResumeMessagePlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### StopMessagePlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### CancelPendingMessagePlayback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### AddPresetMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message** | *in* | *s* |  |
| **type** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### DeletePresetMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message\_id** | *in* | *u* |  |
| **type** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### MovePresetMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message\_id\_from** | *in* | *u* |  |
| **message\_id\_to** | *in* | *u* |  |
| **type** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### EditPresetMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **message\_id** | *in* | *u* |  |
| **message** | *in* | *s* |  |
| **type** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### GetPresetMessageList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **type** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **list** | *out* | *(uas)* |  |


### ApplySettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |


### ResetSettings



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection\_in** | *in* | *u* |  |
| **context\_in** | *in* | *u* |  |
| **settings\_in** | *in* | *u* |  |
| **connection\_out** | *out* | *u* |  |
| **context\_out** | *out* | *u* |  |
| **status** | *out* | *i* |  |
| **settings\_out** | *out* | *u* |  |



## Signals

### AutoDownloadChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_type** | ** | *i* |  |
| **enabled** | ** | *b* |  |


### NotifyChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **client\_type** | ** | *i* |  |
| **enabled** | ** | *b* |  |


### PresetMessageListChanged




### NewMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection** | ** | *u* |  |
| **newMessage** | ** | *(itss)* |  |


### NewMessagesInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection** | ** | *u* |  |
| **info** | ** | *((ua(iub)))* |  |


### Notification



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection** | ** | *u* |  |
| **type** | ** | *i* |  |


### DownloadCompleted



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection** | ** | *u* |  |
| **status** | ** | *i* |  |
| **message\_list** | ** | *(bbbuua(itiusss))* |  |


### MessagePlaybackStatusChanged



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection** | ** | *u* |  |
| **status** | ** | *i* |  |
| **message\_id** | ** | *t* |  |


### InstancesDisconnected



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **connection** | ** | *u* |  |
| **instance\_list** | ** | *(ua(qs))* |  |

