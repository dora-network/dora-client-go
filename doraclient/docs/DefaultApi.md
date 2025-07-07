# {{classname}}

All URIs are relative to *https://localhost:8080/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelAllOpenOrders**](DefaultApi.md#CancelAllOpenOrders) | **Delete** /orders | Cancel all open orders
[**CancelOrderById**](DefaultApi.md#CancelOrderById) | **Delete** /orders/{order_id} | Cancel an order by ID
[**CreateOrder**](DefaultApi.md#CreateOrder) | **Post** /orders | Create a new order
[**DeleteUser**](DefaultApi.md#DeleteUser) | **Delete** /user/{id} | Delete user by ID
[**GetAllAssetPrices**](DefaultApi.md#GetAllAssetPrices) | **Get** /price | Get the current price of all assets
[**GetAssetById**](DefaultApi.md#GetAssetById) | **Get** /assets/{id} | Get asset by ID
[**GetAssetPrice**](DefaultApi.md#GetAssetPrice) | **Get** /price/asset/{asset_id} | Get the current price of an asset
[**GetCandleData**](DefaultApi.md#GetCandleData) | **Get** /charts/candle/{orderbook} | Get candlestick data for an orderbook
[**GetCouponsByAssetId**](DefaultApi.md#GetCouponsByAssetId) | **Get** /assets/{id}/coupons | Get coupons for a bond asset
[**GetL3Depth**](DefaultApi.md#GetL3Depth) | **Get** /orderbooks/{id}/orders | Get all open orders for a specific orderbook (L3 market depth)
[**GetL3Depth_0**](DefaultApi.md#GetL3Depth_0) | **Get** /orderbooks/{id}/L3 | Get all open orders for a specific orderbook (L3 market depth)
[**GetLedgerBalancesSelf**](DefaultApi.md#GetLedgerBalancesSelf) | **Get** /ledger/balances/self | Get your own available, locked, and borrowed assets
[**GetLedgerInterestSelf**](DefaultApi.md#GetLedgerInterestSelf) | **Get** /ledger/interest/self | Get your own interest
[**GetLedgerModule**](DefaultApi.md#GetLedgerModule) | **Get** /ledger/module | Get the entire module object, including unborrowed leverage assets and total leverage trackers
[**GetLedgerModuleByAsset**](DefaultApi.md#GetLedgerModuleByAsset) | **Get** /ledger/module/{asset_id} | Get the module object for a single asset ID
[**GetLedgerPositionsSelf**](DefaultApi.md#GetLedgerPositionsSelf) | **Get** /ledger/positions/self | Get your own positions
[**GetLedgerValueSelf**](DefaultApi.md#GetLedgerValueSelf) | **Get** /ledger/value/self | Get your own available, locked, and borrowed USD value; and realized and unrealized PnL
[**GetOrderById**](DefaultApi.md#GetOrderById) | **Get** /orders/{order_id} | Get order by ID
[**GetOrderbookById**](DefaultApi.md#GetOrderbookById) | **Get** /orderbooks/{id} | Get orderbook by ID
[**GetOrderbookDepth**](DefaultApi.md#GetOrderbookDepth) | **Get** /orderbooks/{id}/depth | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetOrderbookDepth_0**](DefaultApi.md#GetOrderbookDepth_0) | **Get** /orderbooks/{id}/L2 | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetOrderbookSummary**](DefaultApi.md#GetOrderbookSummary) | **Get** /orderbooks/{id}/summary | Get summary of an orderbook
[**GetOrderbookTop**](DefaultApi.md#GetOrderbookTop) | **Get** /orderbooks/{id}/top | Get the top price levels for a specific orderbook (L1 market depth)
[**GetOrderbookTop_0**](DefaultApi.md#GetOrderbookTop_0) | **Get** /orderbooks/{id}/L1 | Get the top price levels for a specific orderbook (L1 market depth)
[**GetPoolPrice**](DefaultApi.md#GetPoolPrice) | **Get** /price/pool/{pool_id} | Get the current price of a pool
[**GetTradeById**](DefaultApi.md#GetTradeById) | **Get** /trade/{id} | Get a trade by ID
[**GetTrades**](DefaultApi.md#GetTrades) | **Get** /trade | Get a filtered, paginated list of trades
[**GetTransactionById**](DefaultApi.md#GetTransactionById) | **Get** /transactions/{id} | Get a transaction by ID
[**GetTransactions**](DefaultApi.md#GetTransactions) | **Get** /transactions | Get a filtered, paginated list of transactions
[**GetUserById**](DefaultApi.md#GetUserById) | **Get** /user/{id} | Get user by ID
[**GetUserLedgerStream**](DefaultApi.md#GetUserLedgerStream) | **Get** /user/{id}/ledger/stream | Get a snapshot of user&#x27;s ledger updates since a specific time, and opens a stream for further updates
[**GetUserOrdersStream**](DefaultApi.md#GetUserOrdersStream) | **Get** /user/{id}/orders/stream | Get a snapshot of user&#x27;s order updates since a specific time, and opens a stream for further updates
[**GetUserTransactionsStream**](DefaultApi.md#GetUserTransactionsStream) | **Get** /user/{id}/transactions/stream | Get a snapshot of user&#x27;s executed transactions since a specific time, and opens a stream for further updates
[**LedgerDeposit**](DefaultApi.md#LedgerDeposit) | **Post** /ledger/deposit | Deposit assets into your account from the outside world
[**LedgerWithdraw**](DefaultApi.md#LedgerWithdraw) | **Post** /ledger/withdraw | Withdraw assets from your account to the outside world
[**LeverageBorrow**](DefaultApi.md#LeverageBorrow) | **Post** /leverage/borrow | Directly borrow assets
[**LeverageIsolateCollateral**](DefaultApi.md#LeverageIsolateCollateral) | **Post** /leverage/isolate_collateral | Create an isolated position by transferring collateral to the position from the user&#x27;s global collateral
[**LeverageIsolatePosition**](DefaultApi.md#LeverageIsolatePosition) | **Post** /leverage/isolate_position | Create an isolated position using all collateral, supplied_collateral, and borrows from the user&#x27;s global position
[**LeverageRepay**](DefaultApi.md#LeverageRepay) | **Post** /leverage/repay | Repay borrowed assets
[**LeverageSupply**](DefaultApi.md#LeverageSupply) | **Post** /leverage/supply | Supply leverage for a specific asset
[**LeverageUnite**](DefaultApi.md#LeverageUnite) | **Post** /leverage/unite | Combines all isolated positions into a single global position
[**LeverageWithdraw**](DefaultApi.md#LeverageWithdraw) | **Post** /leverage/withdraw | Withdraw leverage for a specific asset
[**LiquidityAdd**](DefaultApi.md#LiquidityAdd) | **Post** /liquidity/pool/{pool_id}/add | Add liquidity to a pool
[**LiquiditySubtract**](DefaultApi.md#LiquiditySubtract) | **Post** /liquidity/pool/{pool_id}/subtract | Subtract liquidity from a pool
[**ListAssets**](DefaultApi.md#ListAssets) | **Get** /assets | List assets
[**ListOrderBooks**](DefaultApi.md#ListOrderBooks) | **Get** /orderbooks | List order books
[**ListOrders**](DefaultApi.md#ListOrders) | **Get** /orders | List all orders
[**StreamAssetPrices**](DefaultApi.md#StreamAssetPrices) | **Get** /price/stream | Get a snapshot of asset prices from a specific date and open a stream for real-time updates
[**StreamCandleData**](DefaultApi.md#StreamCandleData) | **Get** /charts/candle/stream/{orderbook} | Get a snapshot of candlestick data from date provided, and open a stream for real-time updates
[**StreamOrderBookBalances**](DefaultApi.md#StreamOrderBookBalances) | **Get** /orderbooks/{id}/stream/balances | Get a snapshot of base and quote balances for an order book and open a stream for real-time updates
[**StreamOrderbookOpenOrders**](DefaultApi.md#StreamOrderbookOpenOrders) | **Get** /orderbooks/{id}/stream/open | Get a snapshot of open orders in an order book and open a stream for real-time updates
[**StreamTrades**](DefaultApi.md#StreamTrades) | **Get** /trade/stream | Get a snapshot of trades from a specific date and open a stream for real-time updates
[**UpdateUserConfig**](DefaultApi.md#UpdateUserConfig) | **Put** /user/{id}/config | Update user configuration by ID
[**VerifyUser**](DefaultApi.md#VerifyUser) | **Put** /user/{id}/verify | Verify a user by ID

# **CancelAllOpenOrders**
> InlineResponse20015 CancelAllOpenOrders(ctx, )
Cancel all open orders

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponse20015**](inline_response_200_15.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CancelOrderById**
> InlineResponse204 CancelOrderById(ctx, orderId)
Cancel an order by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderId** | [**string**](.md)|  | 

### Return type

[**InlineResponse204**](inline_response_204.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CreateOrder**
> OrderId CreateOrder(ctx, body)
Create a new order

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CreateOrderRequest**](CreateOrderRequest.md)|  | 

### Return type

[**OrderId**](OrderId.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteUser**
> InlineResponse2004 DeleteUser(ctx, id)
Delete user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse2004**](inline_response_200_4.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetAllAssetPrices**
> InlineResponse20028 GetAllAssetPrices(ctx, )
Get the current price of all assets

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponse20028**](inline_response_200_28.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

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

# **GetAssetPrice**
> InlineResponse20029 GetAssetPrice(ctx, assetId)
Get the current price of an asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **assetId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20029**](inline_response_200_29.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetCandleData**
> InlineResponse20017 GetCandleData(ctx, orderbook, optional)
Get candlestick data for an orderbook

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbook** | **string**|  | 
 **optional** | ***DefaultApiGetCandleDataOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetCandleDataOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **start** | **optional.Time**|  | 
 **end** | **optional.Time**|  | 
 **resolution** | **optional.String**|  | 

### Return type

[**InlineResponse20017**](inline_response_200_17.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetCouponsByAssetId**
> InlineResponse2002 GetCouponsByAssetId(ctx, id, optional)
Get coupons for a bond asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 
 **optional** | ***DefaultApiGetCouponsByAssetIdOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetCouponsByAssetIdOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **start** | **optional.Time**|  | 
 **end** | **optional.Time**|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**InlineResponse2002**](inline_response_200_2.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetL3Depth**
> InlineResponse2006 GetL3Depth(ctx, id)
Get all open orders for a specific orderbook (L3 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse2006**](inline_response_200_6.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetL3Depth_0**
> InlineResponse2006 GetL3Depth_0(ctx, id)
Get all open orders for a specific orderbook (L3 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse2006**](inline_response_200_6.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerBalancesSelf**
> InlineResponse20021 GetLedgerBalancesSelf(ctx, )
Get your own available, locked, and borrowed assets

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponse20021**](inline_response_200_21.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerInterestSelf**
> InlineResponse20023 GetLedgerInterestSelf(ctx, )
Get your own interest

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponse20023**](inline_response_200_23.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerModule**
> InlineResponse20018 GetLedgerModule(ctx, )
Get the entire module object, including unborrowed leverage assets and total leverage trackers

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponse20018**](inline_response_200_18.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerModuleByAsset**
> InlineResponse20019 GetLedgerModuleByAsset(ctx, assetId)
Get the module object for a single asset ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **assetId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20019**](inline_response_200_19.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerPositionsSelf**
> InlineResponse20020 GetLedgerPositionsSelf(ctx, )
Get your own positions

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponse20020**](inline_response_200_20.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerValueSelf**
> InlineResponse20022 GetLedgerValueSelf(ctx, )
Get your own available, locked, and borrowed USD value; and realized and unrealized PnL

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponse20022**](inline_response_200_22.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderById**
> InlineResponse20016 GetOrderById(ctx, orderId)
Get order by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20016**](inline_response_200_16.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookById**
> InlineResponse20010 GetOrderbookById(ctx, id)
Get orderbook by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse20010**](inline_response_200_10.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookDepth**
> InlineResponse20011 GetOrderbookDepth(ctx, id)
Get the aggregated price levels for a specific orderbook (L2 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse20011**](inline_response_200_11.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookDepth_0**
> InlineResponse20011 GetOrderbookDepth_0(ctx, id)
Get the aggregated price levels for a specific orderbook (L2 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse20011**](inline_response_200_11.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookSummary**
> InlineResponse20013 GetOrderbookSummary(ctx, id)
Get summary of an orderbook

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse20013**](inline_response_200_13.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookTop**
> InlineResponse20012 GetOrderbookTop(ctx, id)
Get the top price levels for a specific orderbook (L1 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse20012**](inline_response_200_12.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookTop_0**
> InlineResponse20012 GetOrderbookTop_0(ctx, id)
Get the top price levels for a specific orderbook (L1 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse20012**](inline_response_200_12.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetPoolPrice**
> InlineResponse20030 GetPoolPrice(ctx, poolId)
Get the current price of a pool

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **poolId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20030**](inline_response_200_30.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTradeById**
> InlineResponse20027 GetTradeById(ctx, id)
Get a trade by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse20027**](inline_response_200_27.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTrades**
> InlineResponse20026 GetTrades(ctx, optional)
Get a filtered, paginated list of trades

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiGetTradesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetTradesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pools** | [**optional.Interface of []string**](string.md)|  | 
 **userIds** | [**optional.Interface of []string**](string.md)|  | 
 **start** | **optional.Time**|  | 
 **end** | **optional.Time**|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**InlineResponse20026**](inline_response_200_26.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTransactionById**
> InlineResponse20025 GetTransactionById(ctx, id)
Get a transaction by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse20025**](inline_response_200_25.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTransactions**
> InlineResponse2008 GetTransactions(ctx, optional)
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

[**InlineResponse2008**](inline_response_200_8.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserById**
> InlineResponse2003 GetUserById(ctx, id)
Get user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse2003**](inline_response_200_3.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserLedgerStream**
> InlineResponse2007 GetUserLedgerStream(ctx, id, optional)
Get a snapshot of user's ledger updates since a specific time, and opens a stream for further updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 
 **optional** | ***DefaultApiGetUserLedgerStreamOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUserLedgerStreamOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **optional.Time**|  | 

### Return type

[**InlineResponse2007**](inline_response_200_7.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserOrdersStream**
> InlineResponse2006 GetUserOrdersStream(ctx, id, optional)
Get a snapshot of user's order updates since a specific time, and opens a stream for further updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 
 **optional** | ***DefaultApiGetUserOrdersStreamOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUserOrdersStreamOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **optional.Time**|  | 
 **orderbookIds** | [**optional.Interface of []string**](string.md)|  | 

### Return type

[**InlineResponse2006**](inline_response_200_6.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserTransactionsStream**
> InlineResponse2008 GetUserTransactionsStream(ctx, id, optional)
Get a snapshot of user's executed transactions since a specific time, and opens a stream for further updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 
 **optional** | ***DefaultApiGetUserTransactionsStreamOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUserTransactionsStreamOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **optional.Time**|  | 

### Return type

[**InlineResponse2008**](inline_response_200_8.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LedgerDeposit**
> InlineResponse201 LedgerDeposit(ctx, body)
Deposit assets into your account from the outside world

TODO: finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**FundUserRequest**](FundUserRequest.md)|  | 

### Return type

[**InlineResponse201**](inline_response_201.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LedgerWithdraw**
> InlineResponse201 LedgerWithdraw(ctx, body)
Withdraw assets from your account to the outside world

TODO: Finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**FundUserRequest**](FundUserRequest.md)|  | 

### Return type

[**InlineResponse201**](inline_response_201.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageBorrow**
> InlineResponse2013 LeverageBorrow(ctx, body)
Directly borrow assets

TODO: Finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**interface{}**](interface{}.md)|  | 

### Return type

[**InlineResponse2013**](inline_response_201_3.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageIsolateCollateral**
> InlineResponse2014 LeverageIsolateCollateral(ctx, body)
Create an isolated position by transferring collateral to the position from the user's global collateral

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**IsolateCollateralRequest**](IsolateCollateralRequest.md)|  | 

### Return type

[**InlineResponse2014**](inline_response_201_4.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageIsolatePosition**
> InlineResponse2015 LeverageIsolatePosition(ctx, body)
Create an isolated position using all collateral, supplied_collateral, and borrows from the user's global position

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**IsolatePositionRequest**](IsolatePositionRequest.md)|  | 

### Return type

[**InlineResponse2015**](inline_response_201_5.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageRepay**
> InlineResponse2013 LeverageRepay(ctx, body)
Repay borrowed assets

TODO: Finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**interface{}**](interface{}.md)|  | 

### Return type

[**InlineResponse2013**](inline_response_201_3.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageSupply**
> InlineResponse2011 LeverageSupply(ctx, body)
Supply leverage for a specific asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**SupplyRequest**](SupplyRequest.md)|  | 

### Return type

[**InlineResponse2011**](inline_response_201_1.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageUnite**
> InlineResponse20024 LeverageUnite(ctx, body)
Combines all isolated positions into a single global position

TODO: Finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UnitePositionRequest**](UnitePositionRequest.md)|  | 

### Return type

[**InlineResponse20024**](inline_response_200_24.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageWithdraw**
> InlineResponse2012 LeverageWithdraw(ctx, body)
Withdraw leverage for a specific asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**WithdrawRequest**](WithdrawRequest.md)|  | 

### Return type

[**InlineResponse2012**](inline_response_201_2.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LiquidityAdd**
> InlineResponse2016 LiquidityAdd(ctx, body, poolId)
Add liquidity to a pool

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**LiquidityRequest**](LiquidityRequest.md)|  | 
  **poolId** | [**string**](.md)|  | 

### Return type

[**InlineResponse2016**](inline_response_201_6.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LiquiditySubtract**
> InlineResponse2016 LiquiditySubtract(ctx, body, poolId)
Subtract liquidity from a pool

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**LiquidityRequest**](LiquidityRequest.md)|  | 
  **poolId** | [**string**](.md)|  | 

### Return type

[**InlineResponse2016**](inline_response_201_6.md)

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
 **assetKind** | **optional.String**| Asset kind (BOND, CURRENCY, INTEREST, POOL_SHARE) | 
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

# **ListOrderBooks**
> InlineResponse2009 ListOrderBooks(ctx, optional)
List order books

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiListOrderBooksOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiListOrderBooksOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createdAfter** | **optional.Time**|  | 
 **createdBefore** | **optional.Time**|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**InlineResponse2009**](inline_response_200_9.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ListOrders**
> InlineResponse2006 ListOrders(ctx, optional)
List all orders

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiListOrdersOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiListOrdersOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orderbookId** | [**optional.Interface of []string**](string.md)|  | 
 **kind** | **optional.String**|  | 
 **status** | **optional.String**|  | 
 **side** | **optional.String**|  | 
 **from** | **optional.Time**|  | 
 **to** | **optional.Time**|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**InlineResponse2006**](inline_response_200_6.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamAssetPrices**
> InlineResponse20028 StreamAssetPrices(ctx, optional)
Get a snapshot of asset prices from a specific date and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiStreamAssetPricesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamAssetPricesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **since** | **optional.Time**|  | 

### Return type

[**InlineResponse20028**](inline_response_200_28.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamCandleData**
> InlineResponse20017 StreamCandleData(ctx, optional)
Get a snapshot of candlestick data from date provided, and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiStreamCandleDataOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamCandleDataOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **since** | **optional.Time**|  | 
 **resolution** | **optional.String**|  | 

### Return type

[**InlineResponse20017**](inline_response_200_17.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamOrderBookBalances**
> InlineResponse20014 StreamOrderBookBalances(ctx, id, optional)
Get a snapshot of base and quote balances for an order book and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 
 **optional** | ***DefaultApiStreamOrderBookBalancesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamOrderBookBalancesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **optional.Time**|  | 

### Return type

[**InlineResponse20014**](inline_response_200_14.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamOrderbookOpenOrders**
> InlineResponse2006 StreamOrderbookOpenOrders(ctx, id, optional)
Get a snapshot of open orders in an order book and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 
 **optional** | ***DefaultApiStreamOrderbookOpenOrdersOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamOrderbookOpenOrdersOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **optional.Time**|  | 

### Return type

[**InlineResponse2006**](inline_response_200_6.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamTrades**
> TradeResponse StreamTrades(ctx, optional)
Get a snapshot of trades from a specific date and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***DefaultApiStreamTradesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamTradesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **since** | **optional.Time**|  | 
 **orderbookIds** | [**optional.Interface of []string**](string.md)|  | 

### Return type

[**TradeResponse**](TradeResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUserConfig**
> InlineResponse2005 UpdateUserConfig(ctx, body, id)
Update user configuration by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserConfigRequest**](UpdateUserConfigRequest.md)|  | 
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse2005**](inline_response_200_5.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **VerifyUser**
> InlineResponse2005 VerifyUser(ctx, id)
Verify a user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**InlineResponse2005**](inline_response_200_5.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

