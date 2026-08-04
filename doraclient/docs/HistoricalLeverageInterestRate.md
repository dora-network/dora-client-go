# HistoricalLeverageInterestRate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**UpdatedAt** | **time.Time** |  | 
**Utilization** | **string** |  | 
**MaximumUtilization** | **string** |  | 
**MinimumRate** | **string** |  | 
**KinkRate** | **string** |  | 
**MaximumRate** | **string** |  | 
**KinkUtilization** | **string** |  | 
**BorrowingYieldRate** | **string** |  | 
**LendingYieldRate** | **string** |  | 
**YieldToMaturity** | **string** |  | 

## Methods

### NewHistoricalLeverageInterestRate

`func NewHistoricalLeverageInterestRate(assetId string, updatedAt time.Time, utilization string, maximumUtilization string, minimumRate string, kinkRate string, maximumRate string, kinkUtilization string, borrowingYieldRate string, lendingYieldRate string, yieldToMaturity string, ) *HistoricalLeverageInterestRate`

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

`func (o *HistoricalLeverageInterestRate) GetUtilization() string`

GetUtilization returns the Utilization field if non-nil, zero value otherwise.

### GetUtilizationOk

`func (o *HistoricalLeverageInterestRate) GetUtilizationOk() (*string, bool)`

GetUtilizationOk returns a tuple with the Utilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUtilization

`func (o *HistoricalLeverageInterestRate) SetUtilization(v string)`

SetUtilization sets Utilization field to given value.


### GetMaximumUtilization

`func (o *HistoricalLeverageInterestRate) GetMaximumUtilization() string`

GetMaximumUtilization returns the MaximumUtilization field if non-nil, zero value otherwise.

### GetMaximumUtilizationOk

`func (o *HistoricalLeverageInterestRate) GetMaximumUtilizationOk() (*string, bool)`

GetMaximumUtilizationOk returns a tuple with the MaximumUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumUtilization

`func (o *HistoricalLeverageInterestRate) SetMaximumUtilization(v string)`

SetMaximumUtilization sets MaximumUtilization field to given value.


### GetMinimumRate

`func (o *HistoricalLeverageInterestRate) GetMinimumRate() string`

GetMinimumRate returns the MinimumRate field if non-nil, zero value otherwise.

### GetMinimumRateOk

`func (o *HistoricalLeverageInterestRate) GetMinimumRateOk() (*string, bool)`

GetMinimumRateOk returns a tuple with the MinimumRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumRate

`func (o *HistoricalLeverageInterestRate) SetMinimumRate(v string)`

SetMinimumRate sets MinimumRate field to given value.


### GetKinkRate

`func (o *HistoricalLeverageInterestRate) GetKinkRate() string`

GetKinkRate returns the KinkRate field if non-nil, zero value otherwise.

### GetKinkRateOk

`func (o *HistoricalLeverageInterestRate) GetKinkRateOk() (*string, bool)`

GetKinkRateOk returns a tuple with the KinkRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinkRate

`func (o *HistoricalLeverageInterestRate) SetKinkRate(v string)`

SetKinkRate sets KinkRate field to given value.


### GetMaximumRate

`func (o *HistoricalLeverageInterestRate) GetMaximumRate() string`

GetMaximumRate returns the MaximumRate field if non-nil, zero value otherwise.

### GetMaximumRateOk

`func (o *HistoricalLeverageInterestRate) GetMaximumRateOk() (*string, bool)`

GetMaximumRateOk returns a tuple with the MaximumRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumRate

`func (o *HistoricalLeverageInterestRate) SetMaximumRate(v string)`

SetMaximumRate sets MaximumRate field to given value.


### GetKinkUtilization

`func (o *HistoricalLeverageInterestRate) GetKinkUtilization() string`

GetKinkUtilization returns the KinkUtilization field if non-nil, zero value otherwise.

### GetKinkUtilizationOk

`func (o *HistoricalLeverageInterestRate) GetKinkUtilizationOk() (*string, bool)`

GetKinkUtilizationOk returns a tuple with the KinkUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinkUtilization

`func (o *HistoricalLeverageInterestRate) SetKinkUtilization(v string)`

SetKinkUtilization sets KinkUtilization field to given value.


### GetBorrowingYieldRate

`func (o *HistoricalLeverageInterestRate) GetBorrowingYieldRate() string`

GetBorrowingYieldRate returns the BorrowingYieldRate field if non-nil, zero value otherwise.

### GetBorrowingYieldRateOk

`func (o *HistoricalLeverageInterestRate) GetBorrowingYieldRateOk() (*string, bool)`

GetBorrowingYieldRateOk returns a tuple with the BorrowingYieldRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorrowingYieldRate

`func (o *HistoricalLeverageInterestRate) SetBorrowingYieldRate(v string)`

SetBorrowingYieldRate sets BorrowingYieldRate field to given value.


### GetLendingYieldRate

`func (o *HistoricalLeverageInterestRate) GetLendingYieldRate() string`

GetLendingYieldRate returns the LendingYieldRate field if non-nil, zero value otherwise.

### GetLendingYieldRateOk

`func (o *HistoricalLeverageInterestRate) GetLendingYieldRateOk() (*string, bool)`

GetLendingYieldRateOk returns a tuple with the LendingYieldRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLendingYieldRate

`func (o *HistoricalLeverageInterestRate) SetLendingYieldRate(v string)`

SetLendingYieldRate sets LendingYieldRate field to given value.


### GetYieldToMaturity

`func (o *HistoricalLeverageInterestRate) GetYieldToMaturity() string`

GetYieldToMaturity returns the YieldToMaturity field if non-nil, zero value otherwise.

### GetYieldToMaturityOk

`func (o *HistoricalLeverageInterestRate) GetYieldToMaturityOk() (*string, bool)`

GetYieldToMaturityOk returns a tuple with the YieldToMaturity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYieldToMaturity

`func (o *HistoricalLeverageInterestRate) SetYieldToMaturity(v string)`

SetYieldToMaturity sets YieldToMaturity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


