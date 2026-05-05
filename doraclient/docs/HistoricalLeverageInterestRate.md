# HistoricalLeverageInterestRate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**UpdatedAt** | **time.Time** |  | 
**Utilization** | **float64** |  | 
**MaximumUtilization** | **float64** |  | 
**MinimumRate** | **float64** |  | 
**KinkRate** | **float64** |  | 
**MaximumRate** | **float64** |  | 
**KinkUtilization** | **float64** |  | 
**InterestRate** | **float64** |  | 

## Methods

### NewHistoricalLeverageInterestRate

`func NewHistoricalLeverageInterestRate(assetId string, updatedAt time.Time, utilization float64, maximumUtilization float64, minimumRate float64, kinkRate float64, maximumRate float64, kinkUtilization float64, interestRate float64, ) *HistoricalLeverageInterestRate`

NewHistoricalLeverageInterestRate instantiates a new HistoricalLeverageInterestRate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoricalLeverageInterestRateWithDefaults

`func NewHistoricalLeverageInterestRateWithDefaults() *HistoricalLeverageInterestRate`

NewHistoricalLeverageInterestRateWithDefaults instantiates a new HistoricalLeverageInterestRate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *HistoricalLeverageInterestRate) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *HistoricalLeverageInterestRate) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *HistoricalLeverageInterestRate) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetUpdatedAt

`func (o *HistoricalLeverageInterestRate) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *HistoricalLeverageInterestRate) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *HistoricalLeverageInterestRate) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUtilization

`func (o *HistoricalLeverageInterestRate) GetUtilization() float64`

GetUtilization returns the Utilization field if non-nil, zero value otherwise.

### GetUtilizationOk

`func (o *HistoricalLeverageInterestRate) GetUtilizationOk() (*float64, bool)`

GetUtilizationOk returns a tuple with the Utilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUtilization

`func (o *HistoricalLeverageInterestRate) SetUtilization(v float64)`

SetUtilization sets Utilization field to given value.


### GetMaximumUtilization

`func (o *HistoricalLeverageInterestRate) GetMaximumUtilization() float64`

GetMaximumUtilization returns the MaximumUtilization field if non-nil, zero value otherwise.

### GetMaximumUtilizationOk

`func (o *HistoricalLeverageInterestRate) GetMaximumUtilizationOk() (*float64, bool)`

GetMaximumUtilizationOk returns a tuple with the MaximumUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumUtilization

`func (o *HistoricalLeverageInterestRate) SetMaximumUtilization(v float64)`

SetMaximumUtilization sets MaximumUtilization field to given value.


### GetMinimumRate

`func (o *HistoricalLeverageInterestRate) GetMinimumRate() float64`

GetMinimumRate returns the MinimumRate field if non-nil, zero value otherwise.

### GetMinimumRateOk

`func (o *HistoricalLeverageInterestRate) GetMinimumRateOk() (*float64, bool)`

GetMinimumRateOk returns a tuple with the MinimumRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumRate

`func (o *HistoricalLeverageInterestRate) SetMinimumRate(v float64)`

SetMinimumRate sets MinimumRate field to given value.


### GetKinkRate

`func (o *HistoricalLeverageInterestRate) GetKinkRate() float64`

GetKinkRate returns the KinkRate field if non-nil, zero value otherwise.

### GetKinkRateOk

`func (o *HistoricalLeverageInterestRate) GetKinkRateOk() (*float64, bool)`

GetKinkRateOk returns a tuple with the KinkRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinkRate

`func (o *HistoricalLeverageInterestRate) SetKinkRate(v float64)`

SetKinkRate sets KinkRate field to given value.


### GetMaximumRate

`func (o *HistoricalLeverageInterestRate) GetMaximumRate() float64`

GetMaximumRate returns the MaximumRate field if non-nil, zero value otherwise.

### GetMaximumRateOk

`func (o *HistoricalLeverageInterestRate) GetMaximumRateOk() (*float64, bool)`

GetMaximumRateOk returns a tuple with the MaximumRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumRate

`func (o *HistoricalLeverageInterestRate) SetMaximumRate(v float64)`

SetMaximumRate sets MaximumRate field to given value.


### GetKinkUtilization

`func (o *HistoricalLeverageInterestRate) GetKinkUtilization() float64`

GetKinkUtilization returns the KinkUtilization field if non-nil, zero value otherwise.

### GetKinkUtilizationOk

`func (o *HistoricalLeverageInterestRate) GetKinkUtilizationOk() (*float64, bool)`

GetKinkUtilizationOk returns a tuple with the KinkUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinkUtilization

`func (o *HistoricalLeverageInterestRate) SetKinkUtilization(v float64)`

SetKinkUtilization sets KinkUtilization field to given value.


### GetInterestRate

`func (o *HistoricalLeverageInterestRate) GetInterestRate() float64`

GetInterestRate returns the InterestRate field if non-nil, zero value otherwise.

### GetInterestRateOk

`func (o *HistoricalLeverageInterestRate) GetInterestRateOk() (*float64, bool)`

GetInterestRateOk returns a tuple with the InterestRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterestRate

`func (o *HistoricalLeverageInterestRate) SetInterestRate(v float64)`

SetInterestRate sets InterestRate field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


