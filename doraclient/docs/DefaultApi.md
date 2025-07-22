# {{classname}}

All URIs are relative to *https://localhost:8084*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelAllOpenOrders**](DefaultApi.md#CancelAllOpenOrders) | **Delete** /v1/orders | Cancel all open orders
[**CancelOrderById**](DefaultApi.md#CancelOrderById) | **Delete** /v1/orders/{order_id} | Cancel an order by ID
[**CreateOrder**](DefaultApi.md#CreateOrder) | **Post** /v1/orders | Create a new order
[**DeleteUser**](DefaultApi.md#DeleteUser) | **Delete** /v1/user/{user_id} | Delete user by ID
[**GetAllAssetPrices**](DefaultApi.md#GetAllAssetPrices) | **Get** /v1/price | Get the current price of all assets
[**GetAssetById**](DefaultApi.md#GetAssetById) | **Get** /v1/assets/{id} | Get asset by ID
[**GetAssetPrice**](DefaultApi.md#GetAssetPrice) | **Get** /v1/price/asset/{asset_id} | Get the current price of an asset
[**GetCandleData**](DefaultApi.md#GetCandleData) | **Get** /v1/charts/candle/{orderbook} | Get candlestick data for an orderbook
[**GetCouponsByAssetId**](DefaultApi.md#GetCouponsByAssetId) | **Get** /v1/assets/{id}/coupons | Get coupons for a bond asset
[**GetL1Depth**](DefaultApi.md#GetL1Depth) | **Get** /v1/orderbooks/{orderbook_id}/L1 | Get the top price levels for a specific orderbook (L1 market depth)
[**GetL2Depth**](DefaultApi.md#GetL2Depth) | **Get** /v1/orderbooks/{orderbook_id}/L2 | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetL3Depth**](DefaultApi.md#GetL3Depth) | **Get** /v1/orderbooks/{orderbook_id}/L3 | Get all open orders for a specific orderbook (L3 market depth)
[**GetLedgerBalancesSelf**](DefaultApi.md#GetLedgerBalancesSelf) | **Get** /v1/ledger/balances/self | Get your own available, locked, and borrowed assets
[**GetLedgerInterestSelf**](DefaultApi.md#GetLedgerInterestSelf) | **Get** /v1/ledger/interest/self | Get your own interest
[**GetLedgerModule**](DefaultApi.md#GetLedgerModule) | **Get** /v1/ledger/module | Get the entire module object, including unborrowed leverage assets and total leverage trackers
[**GetLedgerModuleByAsset**](DefaultApi.md#GetLedgerModuleByAsset) | **Get** /v1/ledger/module/{asset_id} | Get the module object for a single asset ID
[**GetLedgerPositionsSelf**](DefaultApi.md#GetLedgerPositionsSelf) | **Get** /v1/ledger/positions/self | Get your own positions
[**GetLedgerValueSelf**](DefaultApi.md#GetLedgerValueSelf) | **Get** /v1/ledger/value/self | Get your own available, locked, and borrowed USD value; and realized and unrealized PnL
[**GetOrderById**](DefaultApi.md#GetOrderById) | **Get** /v1/orders/{order_id} | Get order by ID
[**GetOrderbookBBO**](DefaultApi.md#GetOrderbookBBO) | **Get** /v1/orderbooks/{orderbook_id}/bbo | Get the top price levels for a specific orderbook (L1 market depth)
[**GetOrderbookById**](DefaultApi.md#GetOrderbookById) | **Get** /v1/orderbooks/{orderbook_id} | Get orderbook by ID
[**GetOrderbookDepth**](DefaultApi.md#GetOrderbookDepth) | **Get** /v1/orderbooks/{orderbook_id}/depth | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetOrderbookOrders**](DefaultApi.md#GetOrderbookOrders) | **Get** /v1/orderbooks/{orderbook_id}/orders | Get all open orders for a specific orderbook (L3 market depth)
[**GetOrderbookSummary**](DefaultApi.md#GetOrderbookSummary) | **Get** /v1/orderbooks/{orderbook_id}/summary | Get summary of an orderbook
[**GetOrderbookTop**](DefaultApi.md#GetOrderbookTop) | **Get** /v1/orderbooks/{orderbook_id}/top | Get the top price levels for a specific orderbook (L1 market depth)
[**GetPoolPrice**](DefaultApi.md#GetPoolPrice) | **Get** /v1/price/pool/{pool_id} | Get the current price of a pool
[**GetTradeById**](DefaultApi.md#GetTradeById) | **Get** /v1/trade/{trade_id} | Get a trade by ID
[**GetTrades**](DefaultApi.md#GetTrades) | **Get** /v1/trade | Get a filtered, paginated list of trades
[**GetTransactionById**](DefaultApi.md#GetTransactionById) | **Get** /v1/transactions/{id} | Get a transaction by ID
[**GetTransactions**](DefaultApi.md#GetTransactions) | **Get** /v1/transactions | Get a filtered, paginated list of transactions
[**GetUserById**](DefaultApi.md#GetUserById) | **Get** /v1/user/{user_id} | Get user by ID
[**GetUserLedgerStream**](DefaultApi.md#GetUserLedgerStream) | **Get** /v1/user/{user_id}/ledger/stream | Get a snapshot of user&#x27;s ledger updates since a specific time, and opens a stream for further updates
[**GetUserOrdersStream**](DefaultApi.md#GetUserOrdersStream) | **Get** /v1/user/{user_id}/orders/{orderbook_id}/stream | Get a snapshot of user&#x27;s order updates for the given order book since a specific time, and opens a stream for further updates
[**GetUserOrdersStreamAll**](DefaultApi.md#GetUserOrdersStreamAll) | **Get** /v1/user/{user_id}/orders/all/stream | Get a snapshot of user&#x27;s order updates since a specific time, and opens a stream for further updates
[**GetUserSelf**](DefaultApi.md#GetUserSelf) | **Get** /v1/user/self | Get user details for the authenticated user
[**GetUserTransactionsStream**](DefaultApi.md#GetUserTransactionsStream) | **Get** /v1/user/{user_id}/transactions/stream | Get a snapshot of user&#x27;s executed transactions since a specific time, and opens a stream for further updates
[**LedgerDeposit**](DefaultApi.md#LedgerDeposit) | **Post** /v1/ledger/deposit | Deposit assets into your account from the outside world
[**LedgerWithdraw**](DefaultApi.md#LedgerWithdraw) | **Post** /v1/ledger/withdraw | Withdraw assets from your account to the outside world
[**LeverageBorrow**](DefaultApi.md#LeverageBorrow) | **Post** /v1/leverage/borrow | Directly borrow assets
[**LeverageCollateralize**](DefaultApi.md#LeverageCollateralize) | **Post** /v1/leverage/collateralize | Move supplied and available to supplied_collateral and collateral, for a specified position
[**LeverageDeCollateralize**](DefaultApi.md#LeverageDeCollateralize) | **Post** /v1/leverage/de-collateralize | Move collateral and supplied_collateral to available and supplied, for a specified position.
[**LeverageIsolateCollateral**](DefaultApi.md#LeverageIsolateCollateral) | **Post** /v1/leverage/isolate_collateral | Create an isolated position by transferring collateral to the position from the user&#x27;s global collateral
[**LeverageIsolatePosition**](DefaultApi.md#LeverageIsolatePosition) | **Post** /v1/leverage/isolate_position | Create an isolated position using all collateral, supplied_collateral, and borrows from the user&#x27;s global position
[**LeverageRepay**](DefaultApi.md#LeverageRepay) | **Post** /v1/leverage/repay | Repay borrowed assets
[**LeverageSupply**](DefaultApi.md#LeverageSupply) | **Post** /v1/leverage/supply | Supply leverage for a specific asset
[**LeverageUnite**](DefaultApi.md#LeverageUnite) | **Post** /v1/leverage/unite | Combines all isolated positions into a single global position
[**LeverageWithdraw**](DefaultApi.md#LeverageWithdraw) | **Post** /v1/leverage/withdraw | Withdraw leverage for a specific asset
[**LiquidityAdd**](DefaultApi.md#LiquidityAdd) | **Post** /v1/liquidity/pool/{pool_id}/add | Add liquidity to a pool
[**LiquiditySubtract**](DefaultApi.md#LiquiditySubtract) | **Post** /v1/liquidity/pool/{pool_id}/subtract | Subtract liquidity from a pool
[**ListAssets**](DefaultApi.md#ListAssets) | **Get** /v1/assets | List assets
[**ListOrderBooks**](DefaultApi.md#ListOrderBooks) | **Get** /v1/orderbooks | List order books
[**ListOrders**](DefaultApi.md#ListOrders) | **Get** /v1/orders | List all orders
[**StreamAssetPrices**](DefaultApi.md#StreamAssetPrices) | **Get** /v1/price/stream | Get a snapshot of asset prices from a specific date and open a stream for real-time updates
[**StreamCandleData**](DefaultApi.md#StreamCandleData) | **Get** /v1/charts/candle/stream/{orderbook} | Get a snapshot of candlestick data from date provided, and open a stream for real-time updates
[**StreamOrderBookBalances**](DefaultApi.md#StreamOrderBookBalances) | **Get** /v1/orderbooks/{orderbook_id}/stream/balances | Get a snapshot of base and quote balances for an order book and open a stream for real-time updates
[**StreamOrderbookOpenOrders**](DefaultApi.md#StreamOrderbookOpenOrders) | **Get** /v1/orderbooks/{orderbook_id}/stream/open | Get a snapshot of open orders in an order book and open a stream for real-time updates
[**StreamTrades**](DefaultApi.md#StreamTrades) | **Get** /v1/trade/{orderbook_id}/stream | Get a snapshot of trades from a specific date and open a stream for real-time updates
[**UpdateUserConfig**](DefaultApi.md#UpdateUserConfig) | **Put** /v1/user/{user_id}/config | Update user configuration by ID
[**UpdateUserConfigSelf**](DefaultApi.md#UpdateUserConfigSelf) | **Put** /v1/user/config/self | Update user configuration for the authenticated user
[**VerifyUser**](DefaultApi.md#VerifyUser) | **Put** /v1/user/{user_id}/verify | Verify a user by ID

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
> InlineResponse2004 DeleteUser(ctx, userId)
Delete user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

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

# **GetL1Depth**
> InlineResponse20012 GetL1Depth(ctx, orderbookId)
Get the top price levels for a specific orderbook (L1 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20012**](inline_response_200_12.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetL2Depth**
> InlineResponse20011 GetL2Depth(ctx, orderbookId)
Get the aggregated price levels for a specific orderbook (L2 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20011**](inline_response_200_11.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetL3Depth**
> InlineResponse2006 GetL3Depth(ctx, orderbookId)
Get all open orders for a specific orderbook (L3 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 

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

# **GetOrderbookBBO**
> InlineResponse20012 GetOrderbookBBO(ctx, orderbookId)
Get the top price levels for a specific orderbook (L1 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20012**](inline_response_200_12.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookById**
> InlineResponse20010 GetOrderbookById(ctx, orderbookId)
Get orderbook by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20010**](inline_response_200_10.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookDepth**
> InlineResponse20011 GetOrderbookDepth(ctx, orderbookId)
Get the aggregated price levels for a specific orderbook (L2 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20011**](inline_response_200_11.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookOrders**
> InlineResponse2006 GetOrderbookOrders(ctx, orderbookId)
Get all open orders for a specific orderbook (L3 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 

### Return type

[**InlineResponse2006**](inline_response_200_6.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookSummary**
> InlineResponse20013 GetOrderbookSummary(ctx, orderbookId)
Get summary of an orderbook

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 

### Return type

[**InlineResponse20013**](inline_response_200_13.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookTop**
> InlineResponse20012 GetOrderbookTop(ctx, orderbookId)
Get the top price levels for a specific orderbook (L1 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 

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
> InlineResponse20027 GetTradeById(ctx, tradeId)
Get a trade by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **tradeId** | [**string**](.md)|  | 

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
> InlineResponse2003 GetUserById(ctx, userId)
Get user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

### Return type

[**InlineResponse2003**](inline_response_200_3.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserLedgerStream**
> InlineResponse2007 GetUserLedgerStream(ctx, userId, optional)
Get a snapshot of user's ledger updates since a specific time, and opens a stream for further updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 
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
> InlineResponse2006 GetUserOrdersStream(ctx, userId, orderbookId, optional)
Get a snapshot of user's order updates for the given order book since a specific time, and opens a stream for further updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 
  **orderbookId** | [**string**](.md)|  | 
 **optional** | ***DefaultApiGetUserOrdersStreamOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUserOrdersStreamOpts struct
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

# **GetUserOrdersStreamAll**
> InlineResponse2006 GetUserOrdersStreamAll(ctx, userId, optional)
Get a snapshot of user's order updates since a specific time, and opens a stream for further updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 
 **optional** | ***DefaultApiGetUserOrdersStreamAllOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUserOrdersStreamAllOpts struct
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

# **GetUserSelf**
> InlineResponse2003 GetUserSelf(ctx, )
Get user details for the authenticated user

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**InlineResponse2003**](inline_response_200_3.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserTransactionsStream**
> InlineResponse2008 GetUserTransactionsStream(ctx, userId, optional)
Get a snapshot of user's executed transactions since a specific time, and opens a stream for further updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 
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
> InlineResponse2015 LeverageBorrow(ctx, body)
Directly borrow assets

TODO: Finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**interface{}**](interface{}.md)|  | 

### Return type

[**InlineResponse2015**](inline_response_201_5.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageCollateralize**
> InlineResponse2011 LeverageCollateralize(ctx, body)
Move supplied and available to supplied_collateral and collateral, for a specified position

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CollateralizeRequest**](CollateralizeRequest.md)|  | 

### Return type

[**InlineResponse2011**](inline_response_201_1.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageDeCollateralize**
> InlineResponse2012 LeverageDeCollateralize(ctx, body)
Move collateral and supplied_collateral to available and supplied, for a specified position.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**DeCollateralizeRequest**](DeCollateralizeRequest.md)|  | 

### Return type

[**InlineResponse2012**](inline_response_201_2.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageIsolateCollateral**
> InlineResponse2016 LeverageIsolateCollateral(ctx, body)
Create an isolated position by transferring collateral to the position from the user's global collateral

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**IsolateCollateralRequest**](IsolateCollateralRequest.md)|  | 

### Return type

[**InlineResponse2016**](inline_response_201_6.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageIsolatePosition**
> InlineResponse2017 LeverageIsolatePosition(ctx, body)
Create an isolated position using all collateral, supplied_collateral, and borrows from the user's global position

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**IsolatePositionRequest**](IsolatePositionRequest.md)|  | 

### Return type

[**InlineResponse2017**](inline_response_201_7.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageRepay**
> InlineResponse2015 LeverageRepay(ctx, body)
Repay borrowed assets

TODO: Finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**interface{}**](interface{}.md)|  | 

### Return type

[**InlineResponse2015**](inline_response_201_5.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageSupply**
> InlineResponse2013 LeverageSupply(ctx, body)
Supply leverage for a specific asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**SupplyRequest**](SupplyRequest.md)|  | 

### Return type

[**InlineResponse2013**](inline_response_201_3.md)

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
> InlineResponse2014 LeverageWithdraw(ctx, body)
Withdraw leverage for a specific asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**WithdrawRequest**](WithdrawRequest.md)|  | 

### Return type

[**InlineResponse2014**](inline_response_201_4.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LiquidityAdd**
> InlineResponse2018 LiquidityAdd(ctx, body, poolId)
Add liquidity to a pool

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**LiquidityRequest**](LiquidityRequest.md)|  | 
  **poolId** | [**string**](.md)|  | 

### Return type

[**InlineResponse2018**](inline_response_201_8.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LiquiditySubtract**
> InlineResponse2018 LiquiditySubtract(ctx, body, poolId)
Subtract liquidity from a pool

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**LiquidityRequest**](LiquidityRequest.md)|  | 
  **poolId** | [**string**](.md)|  | 

### Return type

[**InlineResponse2018**](inline_response_201_8.md)

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
 **status** | **optional.String**|  | 
 **baseAssetId** | [**optional.Interface of string**](.md)|  | 
 **quoteAssetId** | [**optional.Interface of string**](.md)|  | 
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
> InlineResponse20017 StreamCandleData(ctx, orderbook, optional)
Get a snapshot of candlestick data from date provided, and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbook** | **string**|  | 
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
> InlineResponse20014 StreamOrderBookBalances(ctx, orderbookId, optional)
Get a snapshot of base and quote balances for an order book and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 
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
> InlineResponse2006 StreamOrderbookOpenOrders(ctx, orderbookId, optional)
Get a snapshot of open orders in an order book and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 
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
> TradeResponse StreamTrades(ctx, orderbookId, optional)
Get a snapshot of trades from a specific date and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderbookId** | [**string**](.md)|  | 
 **optional** | ***DefaultApiStreamTradesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamTradesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **optional.Time**|  | 

### Return type

[**TradeResponse**](TradeResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUserConfig**
> InlineResponse2005 UpdateUserConfig(ctx, body, userId)
Update user configuration by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserConfigRequest**](UpdateUserConfigRequest.md)|  | 
  **userId** | [**string**](.md)|  | 

### Return type

[**InlineResponse2005**](inline_response_200_5.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUserConfigSelf**
> InlineResponse2005 UpdateUserConfigSelf(ctx, body)
Update user configuration for the authenticated user

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserConfigRequest**](UpdateUserConfigRequest.md)|  | 

### Return type

[**InlineResponse2005**](inline_response_200_5.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **VerifyUser**
> InlineResponse2005 VerifyUser(ctx, userId)
Verify a user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

### Return type

[**InlineResponse2005**](inline_response_200_5.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

