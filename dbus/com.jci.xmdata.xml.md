
# Dbus interface API

**com.jci.xmdata**


## Methods

### GetSubscriptionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |


### GetDataServiceSubscriptions



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |


### GetDataAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |


### GetInstallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### GetESN



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### GetVehicleLocation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | *out* | *i* |  |


### AddStock



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stockSymbol** | *in* | *s* |  |
| **status** | *out* | *i* |  |


### RemoveStock



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **stockSymbol** | *in* | *s* |  |
| **status** | *out* | *i* |  |


### GetStockCount



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **count** | *out* | *u* |  |


### GetWSAlertData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |


### SaveWSAlertSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **popUpSetting** | *in* | *b* |  |


### GetWSAlertSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **popUpSetting** | *out* | *b* |  |


### WSHighAlertDataOverride



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **alertID** | *in* | *u* |  |


### GetWSHighAlertData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **alertID** | *out* | *u* |  |
| **alertName** | *out* | *s* |  |
| **alertPriority** | *out* | *q* |  |
| **alertDesc** | *out* | *s* |  |
| **alertAvailability** | *out* | *u* |  |


### SelectState



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |
| **stateName** | *in* | *s* |  |


### SelectCity



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |
| **cityName** | *in* | *s* |  |


### GetRecentCities



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |
| **cityList** | *out* | *(as)* |  |


### SetSelectedRate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |
| **rateType** | *in* | *u* |  |


### GetSelectedRate



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |
| **rateType** | *out* | *u* |  |


### SaveParkingCountrySetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **parkingCountry** | *in* | *u* |  |


### GetParkingCountrySetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **parkingCountry** | *out* | *u* |  |


### GetLastViewedSportTeamList



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |
| **sportsList** | *out* | *(as)* |  |


### SelectSportTeam



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |
| **teamInfo** | *in* | *s* |  |


### DisplayNNGServices



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **service** | *in* | *u* |  |
| **return\_value** | *out* | *u* |  |


### SaveFuelSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **fuelType** | *in* | *u* |  |


### SaveFuelBrandSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **brandList** | *in* | *(as)* |  |


### SaveFuelCountrySetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *i* |  |
| **fuelCountry** | *in* | *u* |  |


### GetFuelSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuelType** | *out* | *u* |  |


### GetFuelBrandSetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **return\_value** | *out* | *u* |  |
| **brandList** | *out* | *(as)* |  |


### GetFuelCountrySetting



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **fuelCountry** | *out* | *u* |  |


### GetWeatherCitySelect



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **selected** | *out* | *b* |  |
| **cityName** | *out* | *s* |  |



## Signals

### SubscriptionStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **subscriptionDetails** | ** | *(uyuss)* |  |


### DataServiceSubscription



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dataSubscriptions** | ** | *(a(uu))* |  |


### DataAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **dataAvailable** | ** | *(a(uu))* |  |


### InstallStatus



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **status** | ** | *i* |  |


### ESNInfo



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **esn\_val ** | ** | *s* |  |


### VehicleLocation



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **latitude** | ** | *d* |  |
| **longitude** | ** | *d* |  |
| **heading** | ** | *d* |  |


### FuelDataUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **count** | ** | *u* |  |


### StockAdded



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isAdded** | ** | *u* |  |


### StockRemoved



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **isRemoved** | ** | *b* |  |


### StockDataUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **count** | ** | *u* |  |


### StockOTAUnAvailable




### MoviesDataUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **count** | ** | *u* |  |


### WeatherForecastDataUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **count** | ** | *u* |  |


### WSAlertDataUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **wSAlertData** | ** | *(a(usqs))* |  |


### WSHighAlertData



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **alertPriority** | ** | *q* |  |


### CityListAvailable



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **count** | ** | *u* |  |


### ParkingDataUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **count** | ** | *u* |  |


### SportsDataUpdated



#### Arguments

| Name | Direction | Type | Description |
| --- | :---: | :---: | --- |
| **listType** | ** | *u* |  |
| **flag** | ** | *b* |  |


### ShowSXMServices



