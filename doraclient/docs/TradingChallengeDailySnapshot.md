# TradingChallengeDailySnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TradingChallengeId** | Pointer to **string** |  | [optional] 
**UserId** | Pointer to **string** |  | [optional] 
**UserName** | Pointer to **string** |  | [optional] 
**TradingDate** | Pointer to **string** |  | [optional] 
**DailyVolume** | Pointer to **string** |  | [optional] 
**DailyPnl** | Pointer to **string** |  | [optional] 
**DailyTrades** | Pointer to **int32** |  | [optional] 
**VolumeCompliant** | Pointer to **bool** |  | [optional] 
**EodEquity** | Pointer to **string** |  | [optional] 
**ActiveDay** | Pointer to **bool** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewTradingChallengeDailySnapshot

`func NewTradingChallengeDailySnapshot() *TradingChallengeDailySnapshot`

NewTradingChallengeDailySnapshot instantiates a new TradingChallengeDailySnapshot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTradingChallengeDailySnapshotWithDefaults

`func NewTradingChallengeDailySnapshotWithDefaults() *TradingChallengeDailySnapshot`

NewTradingChallengeDailySnapshotWithDefaults instantiates a new TradingChallengeDailySnapshot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTradingChallengeId

`func (o *TradingChallengeDailySnapshot) GetTradingChallengeId() string`

GetTradingChallengeId returns the TradingChallengeId field if non-nil, zero value otherwise.

### GetTradingChallengeIdOk

`func (o *TradingChallengeDailySnapshot) GetTradingChallengeIdOk() (*string, bool)`

GetTradingChallengeIdOk returns a tuple with the TradingChallengeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingChallengeId

`func (o *TradingChallengeDailySnapshot) SetTradingChallengeId(v string)`

SetTradingChallengeId sets TradingChallengeId field to given value.

### HasTradingChallengeId

`func (o *TradingChallengeDailySnapshot) HasTradingChallengeId() bool`

HasTradingChallengeId returns a boolean if a field has been set.

### GetUserId

`func (o *TradingChallengeDailySnapshot) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *TradingChallengeDailySnapshot) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *TradingChallengeDailySnapshot) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *TradingChallengeDailySnapshot) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetUserName

`func (o *TradingChallengeDailySnapshot) GetUserName() string`

GetUserName returns the UserName field if non-nil, zero value otherwise.

### GetUserNameOk

`func (o *TradingChallengeDailySnapshot) GetUserNameOk() (*string, bool)`

GetUserNameOk returns a tuple with the UserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserName

`func (o *TradingChallengeDailySnapshot) SetUserName(v string)`

SetUserName sets UserName field to given value.

### HasUserName

`func (o *TradingChallengeDailySnapshot) HasUserName() bool`

HasUserName returns a boolean if a field has been set.

### GetTradingDate

`func (o *TradingChallengeDailySnapshot) GetTradingDate() string`

GetTradingDate returns the TradingDate field if non-nil, zero value otherwise.

### GetTradingDateOk

`func (o *TradingChallengeDailySnapshot) GetTradingDateOk() (*string, bool)`

GetTradingDateOk returns a tuple with the TradingDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTradingDate

`func (o *TradingChallengeDailySnapshot) SetTradingDate(v string)`

SetTradingDate sets TradingDate field to given value.

### HasTradingDate

`func (o *TradingChallengeDailySnapshot) HasTradingDate() bool`

HasTradingDate returns a boolean if a field has been set.

### GetDailyVolume

`func (o *TradingChallengeDailySnapshot) GetDailyVolume() string`

GetDailyVolume returns the DailyVolume field if non-nil, zero value otherwise.

### GetDailyVolumeOk

`func (o *TradingChallengeDailySnapshot) GetDailyVolumeOk() (*string, bool)`

GetDailyVolumeOk returns a tuple with the DailyVolume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyVolume

`func (o *TradingChallengeDailySnapshot) SetDailyVolume(v string)`

SetDailyVolume sets DailyVolume field to given value.

### HasDailyVolume

`func (o *TradingChallengeDailySnapshot) HasDailyVolume() bool`

HasDailyVolume returns a boolean if a field has been set.

### GetDailyPnl

`func (o *TradingChallengeDailySnapshot) GetDailyPnl() string`

GetDailyPnl returns the DailyPnl field if non-nil, zero value otherwise.

### GetDailyPnlOk

`func (o *TradingChallengeDailySnapshot) GetDailyPnlOk() (*string, bool)`

GetDailyPnlOk returns a tuple with the DailyPnl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyPnl

`func (o *TradingChallengeDailySnapshot) SetDailyPnl(v string)`

SetDailyPnl sets DailyPnl field to given value.

### HasDailyPnl

`func (o *TradingChallengeDailySnapshot) HasDailyPnl() bool`

HasDailyPnl returns a boolean if a field has been set.

### GetDailyTrades

`func (o *TradingChallengeDailySnapshot) GetDailyTrades() int32`

GetDailyTrades returns the DailyTrades field if non-nil, zero value otherwise.

### GetDailyTradesOk

`func (o *TradingChallengeDailySnapshot) GetDailyTradesOk() (*int32, bool)`

GetDailyTradesOk returns a tuple with the DailyTrades field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyTrades

`func (o *TradingChallengeDailySnapshot) SetDailyTrades(v int32)`

SetDailyTrades sets DailyTrades field to given value.

### HasDailyTrades

`func (o *TradingChallengeDailySnapshot) HasDailyTrades() bool`

HasDailyTrades returns a boolean if a field has been set.

### GetVolumeCompliant

`func (o *TradingChallengeDailySnapshot) GetVolumeCompliant() bool`

GetVolumeCompliant returns the VolumeCompliant field if non-nil, zero value otherwise.

### GetVolumeCompliantOk

`func (o *TradingChallengeDailySnapshot) GetVolumeCompliantOk() (*bool, bool)`

GetVolumeCompliantOk returns a tuple with the VolumeCompliant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumeCompliant

`func (o *TradingChallengeDailySnapshot) SetVolumeCompliant(v bool)`

SetVolumeCompliant sets VolumeCompliant field to given value.

### HasVolumeCompliant

`func (o *TradingChallengeDailySnapshot) HasVolumeCompliant() bool`

HasVolumeCompliant returns a boolean if a field has been set.

### GetEodEquity

`func (o *TradingChallengeDailySnapshot) GetEodEquity() string`

GetEodEquity returns the EodEquity field if non-nil, zero value otherwise.

### GetEodEquityOk

`func (o *TradingChallengeDailySnapshot) GetEodEquityOk() (*string, bool)`

GetEodEquityOk returns a tuple with the EodEquity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEodEquity

`func (o *TradingChallengeDailySnapshot) SetEodEquity(v string)`

SetEodEquity sets EodEquity field to given value.

### HasEodEquity

`func (o *TradingChallengeDailySnapshot) HasEodEquity() bool`

HasEodEquity returns a boolean if a field has been set.

### GetActiveDay

`func (o *TradingChallengeDailySnapshot) GetActiveDay() bool`

GetActiveDay returns the ActiveDay field if non-nil, zero value otherwise.

### GetActiveDayOk

`func (o *TradingChallengeDailySnapshot) GetActiveDayOk() (*bool, bool)`

GetActiveDayOk returns a tuple with the ActiveDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveDay

`func (o *TradingChallengeDailySnapshot) SetActiveDay(v bool)`

SetActiveDay sets ActiveDay field to given value.

### HasActiveDay

`func (o *TradingChallengeDailySnapshot) HasActiveDay() bool`

HasActiveDay returns a boolean if a field has been set.

### GetCreatedAt

`func (o *TradingChallengeDailySnapshot) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TradingChallengeDailySnapshot) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TradingChallengeDailySnapshot) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *TradingChallengeDailySnapshot) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


