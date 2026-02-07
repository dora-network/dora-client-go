# UnitedPosition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GlobalPositionId** | **string** |  | 
**TransactionIds** | Pointer to **[]string** |  | [optional] 

## Methods

### NewUnitedPosition

`func NewUnitedPosition(globalPositionId string, ) *UnitedPosition`

NewUnitedPosition instantiates a new UnitedPosition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUnitedPositionWithDefaults

`func NewUnitedPositionWithDefaults() *UnitedPosition`

NewUnitedPositionWithDefaults instantiates a new UnitedPosition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGlobalPositionId

`func (o *UnitedPosition) GetGlobalPositionId() string`

GetGlobalPositionId returns the GlobalPositionId field if non-nil, zero value otherwise.

### GetGlobalPositionIdOk

`func (o *UnitedPosition) GetGlobalPositionIdOk() (*string, bool)`

GetGlobalPositionIdOk returns a tuple with the GlobalPositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalPositionId

`func (o *UnitedPosition) SetGlobalPositionId(v string)`

SetGlobalPositionId sets GlobalPositionId field to given value.


### GetTransactionIds

`func (o *UnitedPosition) GetTransactionIds() []string`

GetTransactionIds returns the TransactionIds field if non-nil, zero value otherwise.

### GetTransactionIdsOk

`func (o *UnitedPosition) GetTransactionIdsOk() (*[]string, bool)`

GetTransactionIdsOk returns a tuple with the TransactionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionIds

`func (o *UnitedPosition) SetTransactionIds(v []string)`

SetTransactionIds sets TransactionIds field to given value.

### HasTransactionIds

`func (o *UnitedPosition) HasTransactionIds() bool`

HasTransactionIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


