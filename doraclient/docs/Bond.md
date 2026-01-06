# Bond

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Kind** | Pointer to [**BondKind**](BondKind.md) |  | [optional] 
**CouponStartAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**FinalCouponAt** | Pointer to **NullableTime** |  | [optional] 
**Isin** | Pointer to **string** |  | [optional] 
**IssuedAt** | Pointer to **time.Time** |  | [optional] 
**Issuer** | Pointer to **string** |  | [optional] 
**MaturityAt** | Pointer to **time.Time** |  | [optional] 
**PrincipalValue** | Pointer to **float64** |  | [optional] 
**PaymentsPerYear** | Pointer to **int32** |  | [optional] 
**PaymentsEvery** | Pointer to **int32** | Coupon payment frequency in nanoseconds (minimum 1000 i.e. 1 microsecond) | [optional] 
**NextCouponPayment** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewBond

`func NewBond() *Bond`

NewBond instantiates a new Bond object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBondWithDefaults

`func NewBondWithDefaults() *Bond`

NewBondWithDefaults instantiates a new Bond object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Bond) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Bond) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Bond) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Bond) HasId() bool`

HasId returns a boolean if a field has been set.

### GetKind

`func (o *Bond) GetKind() BondKind`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *Bond) GetKindOk() (*BondKind, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *Bond) SetKind(v BondKind)`

SetKind sets Kind field to given value.

### HasKind

`func (o *Bond) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetCouponStartAt

`func (o *Bond) GetCouponStartAt() time.Time`

GetCouponStartAt returns the CouponStartAt field if non-nil, zero value otherwise.

### GetCouponStartAtOk

`func (o *Bond) GetCouponStartAtOk() (*time.Time, bool)`

GetCouponStartAtOk returns a tuple with the CouponStartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCouponStartAt

`func (o *Bond) SetCouponStartAt(v time.Time)`

SetCouponStartAt sets CouponStartAt field to given value.

### HasCouponStartAt

`func (o *Bond) HasCouponStartAt() bool`

HasCouponStartAt returns a boolean if a field has been set.

### SetCouponStartAtNil

`func (o *Bond) SetCouponStartAtNil(b bool)`

 SetCouponStartAtNil sets the value for CouponStartAt to be an explicit nil

### UnsetCouponStartAt
`func (o *Bond) UnsetCouponStartAt()`

UnsetCouponStartAt ensures that no value is present for CouponStartAt, not even an explicit nil
### GetCreatedAt

`func (o *Bond) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Bond) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Bond) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Bond) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetFinalCouponAt

`func (o *Bond) GetFinalCouponAt() time.Time`

GetFinalCouponAt returns the FinalCouponAt field if non-nil, zero value otherwise.

### GetFinalCouponAtOk

`func (o *Bond) GetFinalCouponAtOk() (*time.Time, bool)`

GetFinalCouponAtOk returns a tuple with the FinalCouponAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalCouponAt

`func (o *Bond) SetFinalCouponAt(v time.Time)`

SetFinalCouponAt sets FinalCouponAt field to given value.

### HasFinalCouponAt

`func (o *Bond) HasFinalCouponAt() bool`

HasFinalCouponAt returns a boolean if a field has been set.

### SetFinalCouponAtNil

`func (o *Bond) SetFinalCouponAtNil(b bool)`

 SetFinalCouponAtNil sets the value for FinalCouponAt to be an explicit nil

### UnsetFinalCouponAt
`func (o *Bond) UnsetFinalCouponAt()`

UnsetFinalCouponAt ensures that no value is present for FinalCouponAt, not even an explicit nil
### GetIsin

`func (o *Bond) GetIsin() string`

GetIsin returns the Isin field if non-nil, zero value otherwise.

### GetIsinOk

`func (o *Bond) GetIsinOk() (*string, bool)`

GetIsinOk returns a tuple with the Isin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsin

`func (o *Bond) SetIsin(v string)`

SetIsin sets Isin field to given value.

### HasIsin

`func (o *Bond) HasIsin() bool`

HasIsin returns a boolean if a field has been set.

### GetIssuedAt

`func (o *Bond) GetIssuedAt() time.Time`

GetIssuedAt returns the IssuedAt field if non-nil, zero value otherwise.

### GetIssuedAtOk

`func (o *Bond) GetIssuedAtOk() (*time.Time, bool)`

GetIssuedAtOk returns a tuple with the IssuedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuedAt

`func (o *Bond) SetIssuedAt(v time.Time)`

SetIssuedAt sets IssuedAt field to given value.

### HasIssuedAt

`func (o *Bond) HasIssuedAt() bool`

HasIssuedAt returns a boolean if a field has been set.

### GetIssuer

`func (o *Bond) GetIssuer() string`

GetIssuer returns the Issuer field if non-nil, zero value otherwise.

### GetIssuerOk

`func (o *Bond) GetIssuerOk() (*string, bool)`

GetIssuerOk returns a tuple with the Issuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuer

`func (o *Bond) SetIssuer(v string)`

SetIssuer sets Issuer field to given value.

### HasIssuer

`func (o *Bond) HasIssuer() bool`

HasIssuer returns a boolean if a field has been set.

### GetMaturityAt

`func (o *Bond) GetMaturityAt() time.Time`

GetMaturityAt returns the MaturityAt field if non-nil, zero value otherwise.

### GetMaturityAtOk

`func (o *Bond) GetMaturityAtOk() (*time.Time, bool)`

GetMaturityAtOk returns a tuple with the MaturityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaturityAt

`func (o *Bond) SetMaturityAt(v time.Time)`

SetMaturityAt sets MaturityAt field to given value.

### HasMaturityAt

`func (o *Bond) HasMaturityAt() bool`

HasMaturityAt returns a boolean if a field has been set.

### GetPrincipalValue

`func (o *Bond) GetPrincipalValue() float64`

GetPrincipalValue returns the PrincipalValue field if non-nil, zero value otherwise.

### GetPrincipalValueOk

`func (o *Bond) GetPrincipalValueOk() (*float64, bool)`

GetPrincipalValueOk returns a tuple with the PrincipalValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrincipalValue

`func (o *Bond) SetPrincipalValue(v float64)`

SetPrincipalValue sets PrincipalValue field to given value.

### HasPrincipalValue

`func (o *Bond) HasPrincipalValue() bool`

HasPrincipalValue returns a boolean if a field has been set.

### GetPaymentsPerYear

`func (o *Bond) GetPaymentsPerYear() int32`

GetPaymentsPerYear returns the PaymentsPerYear field if non-nil, zero value otherwise.

### GetPaymentsPerYearOk

`func (o *Bond) GetPaymentsPerYearOk() (*int32, bool)`

GetPaymentsPerYearOk returns a tuple with the PaymentsPerYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentsPerYear

`func (o *Bond) SetPaymentsPerYear(v int32)`

SetPaymentsPerYear sets PaymentsPerYear field to given value.

### HasPaymentsPerYear

`func (o *Bond) HasPaymentsPerYear() bool`

HasPaymentsPerYear returns a boolean if a field has been set.

### GetPaymentsEvery

`func (o *Bond) GetPaymentsEvery() int32`

GetPaymentsEvery returns the PaymentsEvery field if non-nil, zero value otherwise.

### GetPaymentsEveryOk

`func (o *Bond) GetPaymentsEveryOk() (*int32, bool)`

GetPaymentsEveryOk returns a tuple with the PaymentsEvery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentsEvery

`func (o *Bond) SetPaymentsEvery(v int32)`

SetPaymentsEvery sets PaymentsEvery field to given value.

### HasPaymentsEvery

`func (o *Bond) HasPaymentsEvery() bool`

HasPaymentsEvery returns a boolean if a field has been set.

### GetNextCouponPayment

`func (o *Bond) GetNextCouponPayment() time.Time`

GetNextCouponPayment returns the NextCouponPayment field if non-nil, zero value otherwise.

### GetNextCouponPaymentOk

`func (o *Bond) GetNextCouponPaymentOk() (*time.Time, bool)`

GetNextCouponPaymentOk returns a tuple with the NextCouponPayment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCouponPayment

`func (o *Bond) SetNextCouponPayment(v time.Time)`

SetNextCouponPayment sets NextCouponPayment field to given value.

### HasNextCouponPayment

`func (o *Bond) HasNextCouponPayment() bool`

HasNextCouponPayment returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


