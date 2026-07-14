# PermitTypedData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Types** | [**map[string][]TypedDataField**](array.md) | EIP-712 type definitions, keyed by type name (&#39;EIP712Domain&#39; and &#39;Permit&#39;). | 
**PrimaryType** | **string** | Always &#39;Permit&#39;. | 
**Domain** | [**PermitDomain**](PermitDomain.md) |  | 
**Message** | [**PermitMessage**](PermitMessage.md) |  | 

## Methods

### NewPermitTypedData

`func NewPermitTypedData(types map[string][]TypedDataField, primaryType string, domain PermitDomain, message PermitMessage, ) *PermitTypedData`

NewPermitTypedData instantiates a new PermitTypedData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermitTypedDataWithDefaults

`func NewPermitTypedDataWithDefaults() *PermitTypedData`

NewPermitTypedDataWithDefaults instantiates a new PermitTypedData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTypes

`func (o *PermitTypedData) GetTypes() map[string][]TypedDataField`

GetTypes returns the Types field if non-nil, zero value otherwise.

### GetTypesOk

`func (o *PermitTypedData) GetTypesOk() (*map[string][]TypedDataField, bool)`

GetTypesOk returns a tuple with the Types field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypes

`func (o *PermitTypedData) SetTypes(v map[string][]TypedDataField)`

SetTypes sets Types field to given value.


### GetPrimaryType

`func (o *PermitTypedData) GetPrimaryType() string`

GetPrimaryType returns the PrimaryType field if non-nil, zero value otherwise.

### GetPrimaryTypeOk

`func (o *PermitTypedData) GetPrimaryTypeOk() (*string, bool)`

GetPrimaryTypeOk returns a tuple with the PrimaryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryType

`func (o *PermitTypedData) SetPrimaryType(v string)`

SetPrimaryType sets PrimaryType field to given value.


### GetDomain

`func (o *PermitTypedData) GetDomain() PermitDomain`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *PermitTypedData) GetDomainOk() (*PermitDomain, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *PermitTypedData) SetDomain(v PermitDomain)`

SetDomain sets Domain field to given value.


### GetMessage

`func (o *PermitTypedData) GetMessage() PermitMessage`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PermitTypedData) GetMessageOk() (*PermitMessage, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PermitTypedData) SetMessage(v PermitMessage)`

SetMessage sets Message field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


