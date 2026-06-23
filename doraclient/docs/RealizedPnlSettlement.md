# RealizedPnlSettlement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The ID of the realized PnL settlement | 
**UserId** | **string** | The ID of the user associated with the realized PnL settlement | 
**TenantId** | **string** | The ID of the tenant associated with the realized PnL settlement | 
**PositionId** | **string** | The ID of the position associated with the realized PnL settlement | 
**OrderId** | **string** | The ID of the position-closing order associated with the realized PnL settlement | 
**RealizedUsd** | **string** | The amount of realized PnL in USD | 
**SettledAt** | Pointer to **time.Time** | The timestamp when the realized PnL settlement was settled | [optional] 
**CreatedAt** | **time.Time** | The timestamp when the realized PnL settlement was created | 

## Methods

### NewRealizedPnlSettlement

`func NewRealizedPnlSettlement(id string, userId string, tenantId string, positionId string, orderId string, realizedUsd string, createdAt time.Time, ) *RealizedPnlSettlement`

NewRealizedPnlSettlement instantiates a new RealizedPnlSettlement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRealizedPnlSettlementWithDefaults

`func NewRealizedPnlSettlementWithDefaults() *RealizedPnlSettlement`

NewRealizedPnlSettlementWithDefaults instantiates a new RealizedPnlSettlement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RealizedPnlSettlement) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RealizedPnlSettlement) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RealizedPnlSettlement) SetId(v string)`

SetId sets Id field to given value.


### GetUserId

`func (o *RealizedPnlSettlement) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *RealizedPnlSettlement) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *RealizedPnlSettlement) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetTenantId

`func (o *RealizedPnlSettlement) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *RealizedPnlSettlement) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *RealizedPnlSettlement) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetPositionId

`func (o *RealizedPnlSettlement) GetPositionId() string`

GetPositionId returns the PositionId field if non-nil, zero value otherwise.

### GetPositionIdOk

`func (o *RealizedPnlSettlement) GetPositionIdOk() (*string, bool)`

GetPositionIdOk returns a tuple with the PositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionId

`func (o *RealizedPnlSettlement) SetPositionId(v string)`

SetPositionId sets PositionId field to given value.


### GetOrderId

`func (o *RealizedPnlSettlement) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *RealizedPnlSettlement) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *RealizedPnlSettlement) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.


### GetRealizedUsd

`func (o *RealizedPnlSettlement) GetRealizedUsd() string`

GetRealizedUsd returns the RealizedUsd field if non-nil, zero value otherwise.

### GetRealizedUsdOk

`func (o *RealizedPnlSettlement) GetRealizedUsdOk() (*string, bool)`

GetRealizedUsdOk returns a tuple with the RealizedUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealizedUsd

`func (o *RealizedPnlSettlement) SetRealizedUsd(v string)`

SetRealizedUsd sets RealizedUsd field to given value.


### GetSettledAt

`func (o *RealizedPnlSettlement) GetSettledAt() time.Time`

GetSettledAt returns the SettledAt field if non-nil, zero value otherwise.

### GetSettledAtOk

`func (o *RealizedPnlSettlement) GetSettledAtOk() (*time.Time, bool)`

GetSettledAtOk returns a tuple with the SettledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettledAt

`func (o *RealizedPnlSettlement) SetSettledAt(v time.Time)`

SetSettledAt sets SettledAt field to given value.

### HasSettledAt

`func (o *RealizedPnlSettlement) HasSettledAt() bool`

HasSettledAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *RealizedPnlSettlement) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RealizedPnlSettlement) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RealizedPnlSettlement) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


