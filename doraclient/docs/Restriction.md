# Restriction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DepositLimit** | Pointer to **string** | Maximum deposit allowed (decimal as string) | [optional] 

## Methods

### NewRestriction

`func NewRestriction() *Restriction`

NewRestriction instantiates a new Restriction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRestrictionWithDefaults

`func NewRestrictionWithDefaults() *Restriction`

NewRestrictionWithDefaults instantiates a new Restriction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDepositLimit

`func (o *Restriction) GetDepositLimit() string`

GetDepositLimit returns the DepositLimit field if non-nil, zero value otherwise.

### GetDepositLimitOk

`func (o *Restriction) GetDepositLimitOk() (*string, bool)`

GetDepositLimitOk returns a tuple with the DepositLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepositLimit

`func (o *Restriction) SetDepositLimit(v string)`

SetDepositLimit sets DepositLimit field to given value.

### HasDepositLimit

`func (o *Restriction) HasDepositLimit() bool`

HasDepositLimit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


