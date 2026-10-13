# UpsertAutoRebalanceConfigsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Configs** | [**[]AutoRebalanceConfigUpsert**](AutoRebalanceConfigUpsert.md) |  | 

## Methods

### NewUpsertAutoRebalanceConfigsRequest

`func NewUpsertAutoRebalanceConfigsRequest(configs []AutoRebalanceConfigUpsert, ) *UpsertAutoRebalanceConfigsRequest`

NewUpsertAutoRebalanceConfigsRequest instantiates a new UpsertAutoRebalanceConfigsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpsertAutoRebalanceConfigsRequestWithDefaults

`func NewUpsertAutoRebalanceConfigsRequestWithDefaults() *UpsertAutoRebalanceConfigsRequest`

NewUpsertAutoRebalanceConfigsRequestWithDefaults instantiates a new UpsertAutoRebalanceConfigsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfigs

`func (o *UpsertAutoRebalanceConfigsRequest) GetConfigs() []AutoRebalanceConfigUpsert`

GetConfigs returns the Configs field if non-nil, zero value otherwise.

### GetConfigsOk

`func (o *UpsertAutoRebalanceConfigsRequest) GetConfigsOk() (*[]AutoRebalanceConfigUpsert, bool)`

GetConfigsOk returns a tuple with the Configs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigs

`func (o *UpsertAutoRebalanceConfigsRequest) SetConfigs(v []AutoRebalanceConfigUpsert)`

SetConfigs sets Configs field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


