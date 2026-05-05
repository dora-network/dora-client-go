# HistoricalLeverageInterestRates

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**StartTime** | **time.Time** |  | 
**EndTime** | **time.Time** |  | 
**Rates** | [**[]HistoricalLeverageInterestRate**](HistoricalLeverageInterestRate.md) |  | 

## Methods

### NewHistoricalLeverageInterestRates

`func NewHistoricalLeverageInterestRates(assetId string, startTime time.Time, endTime time.Time, rates []HistoricalLeverageInterestRate, ) *HistoricalLeverageInterestRates`

NewHistoricalLeverageInterestRates instantiates a new HistoricalLeverageInterestRates object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoricalLeverageInterestRatesWithDefaults

`func NewHistoricalLeverageInterestRatesWithDefaults() *HistoricalLeverageInterestRates`

NewHistoricalLeverageInterestRatesWithDefaults instantiates a new HistoricalLeverageInterestRates object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *HistoricalLeverageInterestRates) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *HistoricalLeverageInterestRates) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *HistoricalLeverageInterestRates) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetStartTime

`func (o *HistoricalLeverageInterestRates) GetStartTime() time.Time`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *HistoricalLeverageInterestRates) GetStartTimeOk() (*time.Time, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *HistoricalLeverageInterestRates) SetStartTime(v time.Time)`

SetStartTime sets StartTime field to given value.


### GetEndTime

`func (o *HistoricalLeverageInterestRates) GetEndTime() time.Time`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *HistoricalLeverageInterestRates) GetEndTimeOk() (*time.Time, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *HistoricalLeverageInterestRates) SetEndTime(v time.Time)`

SetEndTime sets EndTime field to given value.


### GetRates

`func (o *HistoricalLeverageInterestRates) GetRates() []HistoricalLeverageInterestRate`

GetRates returns the Rates field if non-nil, zero value otherwise.

### GetRatesOk

`func (o *HistoricalLeverageInterestRates) GetRatesOk() (*[]HistoricalLeverageInterestRate, bool)`

GetRatesOk returns a tuple with the Rates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRates

`func (o *HistoricalLeverageInterestRates) SetRates(v []HistoricalLeverageInterestRate)`

SetRates sets Rates field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


