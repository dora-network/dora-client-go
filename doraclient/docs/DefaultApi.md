# {{classname}}

All URIs are relative to *https://localhost:8080/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAsset**](DefaultApi.md#CreateAsset) | **Post** /assets | Create an asset
[**CreateUser**](DefaultApi.md#CreateUser) | **Post** /user | Create a new user
[**DeleteUser**](DefaultApi.md#DeleteUser) | **Delete** /user/{id} | Delete user by ID
[**GetAssetById**](DefaultApi.md#GetAssetById) | **Get** /assets/{id} | Get asset by ID
[**GetLedgerBalancesByUserID**](DefaultApi.md#GetLedgerBalancesByUserID) | **Get** /ledger/balances/{user_id} | Get a specific user&#x27;s available, locked, and borrowed assets
[**GetLedgerBalancesSelf**](DefaultApi.md#GetLedgerBalancesSelf) | **Get** /ledger/balances/self | Get your own available, locked, and borrowed assets
[**GetLedgerInterestByUserID**](DefaultApi.md#GetLedgerInterestByUserID) | **Get** /ledger/interest/{user_id} | Get a specific user&#x27;s interest
[**GetLedgerInterestSelf**](DefaultApi.md#GetLedgerInterestSelf) | **Get** /ledger/interest/self | Get your own interest
[**GetLedgerModule**](DefaultApi.md#GetLedgerModule) | **Get** /ledger/module | Get the entire module object, including unborrowed leverage assets and total leverage trackers
[**GetLedgerModuleByAsset**](DefaultApi.md#GetLedgerModuleByAsset) | **Get** /ledger/module/{asset_id} | Get the module object for a single asset ID
[**GetLedgerPositionsByUserID**](DefaultApi.md#GetLedgerPositionsByUserID) | **Get** /ledger/positions/{user_id} | Get a specific user&#x27;s positions
[**GetLedgerPositionsSelf**](DefaultApi.md#GetLedgerPositionsSelf) | **Get** /ledger/positions/self | Get your own positions
[**GetLedgerValueByUserID**](DefaultApi.md#GetLedgerValueByUserID) | **Get** /ledger/value/{user_id} | Get a specific user&#x27;s available, locked, and borrowed USD value
[**GetLedgerValueSelf**](DefaultApi.md#GetLedgerValueSelf) | **Get** /ledger/value/self | Get your own available, locked, and borrowed USD value
[**GetLeverageLiquidationTargets**](DefaultApi.md#GetLeverageLiquidationTargets) | **Get** /leverage/liquidation-targets | Get a list of users who are eligible for automatic liquidation
[**GetTransactionById**](DefaultApi.md#GetTransactionById) | **Get** /transactions/{id} | Get a transaction by ID
[**GetTransactions**](DefaultApi.md#GetTransactions) | **Get** /transactions | Get a filtered, paginated list of transactions
[**GetUserById**](DefaultApi.md#GetUserById) | **Get** /user/{id} | Get user by ID
[**GetUsers**](DefaultApi.md#GetUsers) | **Get** /user | Get all users (admin only)
[**LedgerDeposit**](DefaultApi.md#LedgerDeposit) | **Post** /ledger/deposit | Deposit assets into your account from the outside world
[**LedgerFund**](DefaultApi.md#LedgerFund) | **Post** /ledger/fund | Add or remove funds from a user
[**LedgerWithdraw**](DefaultApi.md#LedgerWithdraw) | **Post** /ledger/withdraw | Withdraw assets from your account to the outside world
[**LeverageBorrow**](DefaultApi.md#LeverageBorrow) | **Post** /leverage/borrow | Directly borrow assets
[**LeverageRepay**](DefaultApi.md#LeverageRepay) | **Post** /leverage/repay | Repay borrowed assets
[**LeverageSupply**](DefaultApi.md#LeverageSupply) | **Post** /leverage/supply | Supply leverage for a specific asset
[**LeverageWithdraw**](DefaultApi.md#LeverageWithdraw) | **Post** /leverage/withdraw | Withdraw leverage for a specific asset
[**LiquidityAdd**](DefaultApi.md#LiquidityAdd) | **Post** /liquidity/pool/{pool_id}/add | Add liquidity to a pool
[**LiquiditySubtract**](DefaultApi.md#LiquiditySubtract) | **Post** /liquidity/pool/{pool_id}/subtract | Subtract liquidity from a pool
[**ListAssets**](DefaultApi.md#ListAssets) | **Get** /assets | List assets
[**UpdateAsset**](DefaultApi.md#UpdateAsset) | **Put** /assets/{id} | Update asset by ID
[**UpdateUser**](DefaultApi.md#UpdateUser) | **Put** /user/{id} | Update user by ID (admin only)

# **CreateAsset**
> InlineResponse201 CreateAsset(ctx, body)
Create an asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateAssetReq**](CreateAssetReq.md)|  | 

### Return type

[**InlineResponse201**](inline_response_201.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateUser**
> CreateOrUpdateResponse CreateUser(ctx, body)
Create a new user

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateUserRequest**](CreateUserRequest.md)|  | 

### Return type

[**CreateOrUpdateResponse**](CreateOrUpdateResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteUser**
> DeleteUser(ctx, id)
Delete user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetAssetById**
> InlineResponse2001 GetAssetById(ctx, id)
Get asset by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse2001**](inline_response_200_1.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerBalancesByUserID**
> BalancesResponse GetLedgerBalancesByUserID(ctx, userId)
Get a specific user's available, locked, and borrowed assets

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

### Return type

[**BalancesResponse**](BalancesResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerBalancesSelf**
> BalancesResponse GetLedgerBalancesSelf(ctx, )
Get your own available, locked, and borrowed assets

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**BalancesResponse**](BalancesResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerInterestByUserID**
> UserInterestResponse GetLedgerInterestByUserID(ctx, userId)
Get a specific user's interest

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

### Return type

[**UserInterestResponse**](UserInterestResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerInterestSelf**
> UserInterestResponse GetLedgerInterestSelf(ctx, )
Get your own interest

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**UserInterestResponse**](UserInterestResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerModule**
> LeverageModuleResponse GetLedgerModule(ctx, )
Get the entire module object, including unborrowed leverage assets and total leverage trackers

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**LeverageModuleResponse**](LeverageModuleResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerModuleByAsset**
> LeverageBalanceResponse GetLedgerModuleByAsset(ctx, assetId)
Get the module object for a single asset ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **assetId** | [**string**](.md)|  | 

### Return type

[**LeverageBalanceResponse**](LeverageBalanceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerPositionsByUserID**
> PositionResponse GetLedgerPositionsByUserID(ctx, userId)
Get a specific user's positions

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

### Return type

[**PositionResponse**](PositionResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerPositionsSelf**
> PositionResponse GetLedgerPositionsSelf(ctx, )
Get your own positions

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**PositionResponse**](PositionResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerValueByUserID**
> UserValueResponse GetLedgerValueByUserID(ctx, userId)
Get a specific user's available, locked, and borrowed USD value

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

### Return type

[**UserValueResponse**](UserValueResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerValueSelf**
> UserValueResponse GetLedgerValueSelf(ctx, )
Get your own available, locked, and borrowed USD value

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**UserValueResponse**](UserValueResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLeverageLiquidationTargets**
> []string GetLeverageLiquidationTargets(ctx, )
Get a list of users who are eligible for automatic liquidation

### Required Parameters
This endpoint does not need any parameter.

### Return type

**[]string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTransactionById**
> TransactionResponse GetTransactionById(ctx, id)
Get a transaction by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**TransactionResponse**](TransactionResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTransactions**
> []TransactionResponse GetTransactions(ctx, optional)
Get a filtered, paginated list of transactions

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetTransactionsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetTransactionsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pools** | [**optional.Interface of []string**](string.md)|  | 
 **userIds** | [**optional.Interface of []string**](string.md)|  | 
 **txKinds** | [**optional.Interface of []string**](string.md)|  | 
 **start** | **optional.Time**|  | 
 **end** | **optional.Time**|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**[]TransactionResponse**](TransactionResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserById**
> User GetUserById(ctx, id)
Get user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUsers**
> []User GetUsers(ctx, optional)
Get all users (admin only)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetUsersOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUsersOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | [**optional.Interface of string**](.md)|  | 
 **limit** | **optional.Int32**|  | [default to 100]
 **offset** | **optional.Int32**|  | [default to 0]
 **email** | **optional.String**|  | 
 **name** | **optional.String**|  | 

### Return type

[**[]User**](User.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LedgerDeposit**
> FundUserResponse LedgerDeposit(ctx, body)
Deposit assets into your account from the outside world

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**FundUserRequest**](FundUserRequest.md)|  | 

### Return type

[**FundUserResponse**](FundUserResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LedgerFund**
> FundUserResponse LedgerFund(ctx, body)
Add or remove funds from a user

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**FundUserRequest**](FundUserRequest.md)|  | 

### Return type

[**FundUserResponse**](FundUserResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LedgerWithdraw**
> FundUserResponse LedgerWithdraw(ctx, body)
Withdraw assets from your account to the outside world

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**FundUserRequest**](FundUserRequest.md)|  | 

### Return type

[**FundUserResponse**](FundUserResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageBorrow**
> interface{} LeverageBorrow(ctx, body)
Directly borrow assets

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**interface{}**](interface{}.md)|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageRepay**
> interface{} LeverageRepay(ctx, body)
Repay borrowed assets

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**interface{}**](interface{}.md)|  | 

### Return type

[**interface{}**](interface{}.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageSupply**
> SupplyResponse LeverageSupply(ctx, body)
Supply leverage for a specific asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**SupplyRequest**](SupplyRequest.md)|  | 

### Return type

[**SupplyResponse**](SupplyResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageWithdraw**
> WithdrawResponse LeverageWithdraw(ctx, body)
Withdraw leverage for a specific asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**WithdrawRequest**](WithdrawRequest.md)|  | 

### Return type

[**WithdrawResponse**](WithdrawResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LiquidityAdd**
> LiquidityResponse LiquidityAdd(ctx, body, poolId)
Add liquidity to a pool

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**LiquidityRequest**](LiquidityRequest.md)|  | 
  **poolId** | [**string**](.md)|  | 

### Return type

[**LiquidityResponse**](LiquidityResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LiquiditySubtract**
> LiquidityResponse LiquiditySubtract(ctx, body, poolId)
Subtract liquidity from a pool

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**LiquidityRequest**](LiquidityRequest.md)|  | 
  **poolId** | [**string**](.md)|  | 

### Return type

[**LiquidityResponse**](LiquidityResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ListAssets**
> InlineResponse200 ListAssets(ctx, optional)
List assets

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiListAssetsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiListAssetsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createdAfter** | **optional.Time**|  | 
 **createdBefore** | **optional.Time**|  | 
 **assetKind** | **optional.String**| Asset kind (BOND, CURRENCY, INTEREST, POOLSHARE) | 
 **canAddLiquidity** | **optional.Bool**|  | 
 **canDirectBorrow** | **optional.Bool**|  | 
 **canOnboard** | **optional.Bool**|  | 
 **canTrade** | **optional.Bool**|  | 
 **canVirtualBorrow** | **optional.Bool**|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**InlineResponse200**](inline_response_200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateAsset**
> InlineResponse201 UpdateAsset(ctx, body, id)
Update asset by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateAssetReq**](UpdateAssetReq.md)|  | 
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse201**](inline_response_201.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUser**
> CreateOrUpdateResponse UpdateUser(ctx, body, id)
Update user by ID (admin only)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserRequest**](UpdateUserRequest.md)|  | 
  **id** | [**string**](.md)|  | 

### Return type

[**CreateOrUpdateResponse**](CreateOrUpdateResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

