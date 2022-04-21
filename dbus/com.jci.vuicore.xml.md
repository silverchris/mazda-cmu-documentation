
# Dbus interface API

**com.jci.vuicore**


## Methods

### SetParadigm



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **paradigm** | *in* | *i* |  |


### SetAppContext



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **appContext** | *in* | *(iiuuay)* |  |
| **action** | *in* | *i* |  |


### SendMessage



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **message** | *in* | *(iiuay)* |  |


### StartReco



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **startOfSession** | *in* | *b* |  |


### AbortSession



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **action** | *in* | *i* |  |


### SetLang



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **language** | *in* | *i* |  |


### SendAlert



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **alert** | *in* | *(iiuay)* |  |
| **alertAction** | *in* | *i* |  |


### SetTestMode



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **enableTestMode** | *in* | *b* |  |
| **enableNLU** | *in* | *b* |  |


### SetPrerecordedAudioFiles



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **audioFileAttempt1** | *in* | *s* |  |
| **audioFileAttempt2** | *in* | *s* |  |
| **audioFileAttempt3** | *in* | *s* |  |


### AlertQueueEmpty





## Signals

### AppEventCallback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **event** | ** | *(iiuayii)* |  |


### LanguageChangedCallback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **language** | ** | *i* |  |


### StateChangeCallback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **newState** | ** | *i* |  |


### AlertCompleteCallback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **alertComplete** | ** | *(iii)* |  |


### MicLevelCallback



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **micLevel** | ** | *i* |  |

