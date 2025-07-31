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
[**GetCandleData**](DefaultApi.md#GetCandleData) | **Get** /v1/charts/{orderbook}/candle | Get candlestick data for an orderbook
[**GetCouponPaymentsByAssetId**](DefaultApi.md#GetCouponPaymentsByAssetId) | **Get** /v1/assets/{id}/coupon_payments | Get coupon payments for a bond asset
[**GetL1Depth**](DefaultApi.md#GetL1Depth) | **Get** /v1/orderbooks/{order_book_id}/L1 | Get the top price levels for a specific orderbook (L1 market depth)
[**GetL2Depth**](DefaultApi.md#GetL2Depth) | **Get** /v1/orderbooks/{order_book_id}/L2 | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetL3Depth**](DefaultApi.md#GetL3Depth) | **Get** /v1/orderbooks/{order_book_id}/L3 | Get all open orders for a specific orderbook (L3 market depth)
[**GetLedgerBalancesSelf**](DefaultApi.md#GetLedgerBalancesSelf) | **Get** /v1/ledger/balances/self | Get your own available, locked, and borrowed assets
[**GetLedgerInterestSelf**](DefaultApi.md#GetLedgerInterestSelf) | **Get** /v1/ledger/interest/self | Get your own interest
[**GetLedgerModule**](DefaultApi.md#GetLedgerModule) | **Get** /v1/ledger/module | Get the entire module object, including unborrowed leverage assets and total leverage trackers
[**GetLedgerModuleByAsset**](DefaultApi.md#GetLedgerModuleByAsset) | **Get** /v1/ledger/module/{asset_id} | Get the module object for a single asset ID
[**GetLedgerPositionsSelf**](DefaultApi.md#GetLedgerPositionsSelf) | **Get** /v1/ledger/positions/self | Get your own positions
[**GetLedgerValueSelf**](DefaultApi.md#GetLedgerValueSelf) | **Get** /v1/ledger/value/self | Get your own available, locked, and borrowed USD value; and realized and unrealized PnL
[**GetOrderById**](DefaultApi.md#GetOrderById) | **Get** /v1/orders/{order_id} | Get order by ID
[**GetOrderbookById**](DefaultApi.md#GetOrderbookById) | **Get** /v1/orderbooks/{order_book_id} | Get orderbook by ID
[**GetOrderbookDepth**](DefaultApi.md#GetOrderbookDepth) | **Get** /v1/orderbooks/{order_book_id}/depth | Get the aggregated price levels for a specific orderbook (L2 market depth)
[**GetOrderbookOrders**](DefaultApi.md#GetOrderbookOrders) | **Get** /v1/orderbooks/{order_book_id}/orders | Get all open orders for a specific orderbook (L3 market depth)
[**GetOrderbookSummary**](DefaultApi.md#GetOrderbookSummary) | **Get** /v1/orderbooks/{order_book_id}/summary | Get summary of an orderbook
[**GetOrderbookTop**](DefaultApi.md#GetOrderbookTop) | **Get** /v1/orderbooks/{order_book_id}/top | Get the top price levels for a specific orderbook (L1 market depth)
[**GetPoolPrice**](DefaultApi.md#GetPoolPrice) | **Get** /v1/price/pool/{pool_id} | Get the current price of a pool
[**GetTradeById**](DefaultApi.md#GetTradeById) | **Get** /v1/trade/{trade_id} | Get a trade by ID
[**GetTrades**](DefaultApi.md#GetTrades) | **Get** /v1/trade | Get a filtered, paginated list of trades
[**GetTransactionById**](DefaultApi.md#GetTransactionById) | **Get** /v1/transactions/{id} | Get a transaction by ID
[**GetTransactions**](DefaultApi.md#GetTransactions) | **Get** /v1/transactions | Get a filtered, paginated list of transactions
[**GetUserById**](DefaultApi.md#GetUserById) | **Get** /v1/user/{user_id} | Get user by ID (admin only)
[**GetUserLedgerStream**](DefaultApi.md#GetUserLedgerStream) | **Get** /v1/user/{user_id}/ledger/stream | Get a snapshot of user&#x27;s ledger updates since a specific time, and opens a stream for further updates
[**GetUserOrdersStream**](DefaultApi.md#GetUserOrdersStream) | **Get** /v1/user/{user_id}/orders/{order_book_id}/stream | Get a snapshot of user&#x27;s order updates for the given order book since a specific time, and opens a stream for further updates
[**GetUserOrdersStreamAll**](DefaultApi.md#GetUserOrdersStreamAll) | **Get** /v1/user/{user_id}/orders/all/stream | Get a snapshot of user&#x27;s order updates across all order books since a specific time, and opens a stream for further updates
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
[**StreamCandleData**](DefaultApi.md#StreamCandleData) | **Get** /v1/charts/{orderbook}/candle/stream | Get a snapshot of candlestick data from date provided, and open a stream for real-time updates
[**StreamOrderBookBalances**](DefaultApi.md#StreamOrderBookBalances) | **Get** /v1/orderbooks/{order_book_id}/stream/balances | Get a snapshot of base and quote balances for an order book and open a stream for real-time updates
[**StreamOrderbookOpenOrders**](DefaultApi.md#StreamOrderbookOpenOrders) | **Get** /v1/orderbooks/{order_book_id}/stream/open | Get a snapshot of open orders in an order book and open a stream for real-time updates
[**StreamTrades**](DefaultApi.md#StreamTrades) | **Get** /v1/trade/{order_book_id}/stream | Get a snapshot of trades executed on the given order book from a specific date and open a stream for real-time updates
[**UpdateUserConfig**](DefaultApi.md#UpdateUserConfig) | **Put** /v1/user/{user_id}/config | Update user configuration by ID
[**UpdateUserConfigSelf**](DefaultApi.md#UpdateUserConfigSelf) | **Put** /v1/user/config/self | Update user configuration for the authenticated user
[**VerifyUser**](DefaultApi.md#VerifyUser) | **Put** /v1/user/{user_id}/verify | Verify a user by ID

# **CancelAllOpenOrders**
> CancelOrdersResponse CancelAllOpenOrders(ctx, )
Cancel all open orders

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**CancelOrdersResponse**](CancelOrdersResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **CancelOrderById**
> OrderCancelledResponse CancelOrderById(ctx, orderId)
Cancel an order by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderId** | [**string**](.md)|  | 

### Return type

[**OrderCancelledResponse**](OrderCancelledResponse.md)

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
> UserDeletedResponse DeleteUser(ctx, userId)
Delete user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

### Return type

[**UserDeletedResponse**](UserDeletedResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetAllAssetPrices**
> ListAssetPriceResponse GetAllAssetPrices(ctx, )
Get the current price of all assets

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**ListAssetPriceResponse**](ListAssetPriceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetAssetById**
> GetAssetByIdResponse GetAssetById(ctx, id)
Get asset by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**GetAssetByIdResponse**](GetAssetByIDResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetAssetPrice**
> GetAssetPriceResponse GetAssetPrice(ctx, assetId)
Get the current price of an asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **assetId** | [**string**](.md)|  | 

### Return type

[**GetAssetPriceResponse**](GetAssetPriceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetCandleData**
> ListCandlesResponse GetCandleData(ctx, orderbook, optional)
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
 **resolution** | [**optional.Interface of CandleResolution**](.md)|  | 

### Return type

[**ListCandlesResponse**](ListCandlesResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetCouponPaymentsByAssetId**
> ListCouponPaymentsResponse GetCouponPaymentsByAssetId(ctx, id)
Get coupon payments for a bond asset

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**ListCouponPaymentsResponse**](ListCouponPaymentsResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetL1Depth**
> GetTopOfBookResponse GetL1Depth(ctx, orderBookId)
Get the top price levels for a specific orderbook (L1 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 

### Return type

[**GetTopOfBookResponse**](GetTopOfBookResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetL2Depth**
> ListOrderBookDepthResponse GetL2Depth(ctx, orderBookId)
Get the aggregated price levels for a specific orderbook (L2 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 

### Return type

[**ListOrderBookDepthResponse**](ListOrderBookDepthResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetL3Depth**
> ListOrdersResponse GetL3Depth(ctx, orderBookId)
Get all open orders for a specific orderbook (L3 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 

### Return type

[**ListOrdersResponse**](ListOrdersResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerBalancesSelf**
> UserBalanceResponse GetLedgerBalancesSelf(ctx, )
Get your own available, locked, and borrowed assets

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**UserBalanceResponse**](UserBalanceResponse.md)

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
> LedgerModuleResponse GetLedgerModule(ctx, )
Get the entire module object, including unborrowed leverage assets and total leverage trackers

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**LedgerModuleResponse**](LedgerModuleResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerModuleByAsset**
> LedgerModuleByAssetResponse GetLedgerModuleByAsset(ctx, assetId)
Get the module object for a single asset ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **assetId** | [**string**](.md)|  | 

### Return type

[**LedgerModuleByAssetResponse**](LedgerModuleByAssetResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerPositionsSelf**
> UserPositionResponse GetLedgerPositionsSelf(ctx, )
Get your own positions

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**UserPositionResponse**](UserPositionResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetLedgerValueSelf**
> UserValueResponse GetLedgerValueSelf(ctx, )
Get your own available, locked, and borrowed USD value; and realized and unrealized PnL

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

# **GetOrderById**
> GetOrderResponse GetOrderById(ctx, orderId)
Get order by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderId** | [**string**](.md)|  | 

### Return type

[**GetOrderResponse**](GetOrderResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookById**
> GetOrderBookResponse GetOrderbookById(ctx, orderBookId)
Get orderbook by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 

### Return type

[**GetOrderBookResponse**](GetOrderBookResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookDepth**
> ListOrderBookDepthResponse GetOrderbookDepth(ctx, orderBookId)
Get the aggregated price levels for a specific orderbook (L2 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 

### Return type

[**ListOrderBookDepthResponse**](ListOrderBookDepthResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookOrders**
> ListOrdersResponse GetOrderbookOrders(ctx, orderBookId)
Get all open orders for a specific orderbook (L3 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 

### Return type

[**ListOrdersResponse**](ListOrdersResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookSummary**
> GetOrderBookSummaryResponse GetOrderbookSummary(ctx, orderBookId)
Get summary of an orderbook

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 

### Return type

[**GetOrderBookSummaryResponse**](GetOrderBookSummaryResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrderbookTop**
> GetTopOfBookResponse GetOrderbookTop(ctx, orderBookId)
Get the top price levels for a specific orderbook (L1 market depth)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 

### Return type

[**GetTopOfBookResponse**](GetTopOfBookResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetPoolPrice**
> GetPoolPriceResponse GetPoolPrice(ctx, poolId)
Get the current price of a pool

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **poolId** | [**string**](.md)|  | 

### Return type

[**GetPoolPriceResponse**](GetPoolPriceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTradeById**
> TradeResponse GetTradeById(ctx, tradeId)
Get a trade by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **tradeId** | [**string**](.md)|  | 

### Return type

[**TradeResponse**](TradeResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTrades**
> ListTradeResponse GetTrades(ctx, optional)
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

[**ListTradeResponse**](ListTradeResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTransactionById**
> GetTransactionResponse GetTransactionById(ctx, id)
Get a transaction by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | [**string**](.md)|  | 

### Return type

[**GetTransactionResponse**](GetTransactionResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTransactions**
> ListTransactionsResponse GetTransactions(ctx, optional)
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
 **txKinds** | [**optional.Interface of []TransactionKind**](TransactionKind.md)|  | 
 **start** | **optional.Time**|  | 
 **end** | **optional.Time**|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**ListTransactionsResponse**](ListTransactionsResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserById**
> GetUserResponse GetUserById(ctx, userId)
Get user by ID (admin only)

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

### Return type

[**GetUserResponse**](GetUserResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserLedgerStream**
> ListPositionsResponse GetUserLedgerStream(ctx, userId, optional)
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

[**ListPositionsResponse**](ListPositionsResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserOrdersStream**
> ListOrdersResponse GetUserOrdersStream(ctx, userId, orderBookId, optional)
Get a snapshot of user's order updates for the given order book since a specific time, and opens a stream for further updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 
  **orderBookId** | [**string**](.md)|  | 
 **optional** | ***DefaultApiGetUserOrdersStreamOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUserOrdersStreamOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **since** | **optional.Time**|  | 

### Return type

[**ListOrdersResponse**](ListOrdersResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserOrdersStreamAll**
> ListOrdersResponse GetUserOrdersStreamAll(ctx, userId, orderBookId, optional)
Get a snapshot of user's order updates across all order books since a specific time, and opens a stream for further updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 
  **orderBookId** | [**string**](.md)|  | 
 **optional** | ***DefaultApiGetUserOrdersStreamAllOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiGetUserOrdersStreamAllOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **since** | **optional.Time**|  | 

### Return type

[**ListOrdersResponse**](ListOrdersResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserSelf**
> GetUserResponse GetUserSelf(ctx, )
Get user details for the authenticated user

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**GetUserResponse**](GetUserResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserTransactionsStream**
> ListTransactionsResponse GetUserTransactionsStream(ctx, userId, optional)
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

[**ListTransactionsResponse**](ListTransactionsResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LedgerDeposit**
> FundUserResponse LedgerDeposit(ctx, body)
Deposit assets into your account from the outside world

TODO: finish this when implementation has been completed

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

TODO: Finish this when implementation has been completed

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
> BorrowResponse LeverageBorrow(ctx, body)
Directly borrow assets

TODO: Finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**BorrowRequest**](BorrowRequest.md)|  | 

### Return type

[**BorrowResponse**](BorrowResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageCollateralize**
> CollateralizeResponse LeverageCollateralize(ctx, body)
Move supplied and available to supplied_collateral and collateral, for a specified position

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**CollateralizeRequest**](CollateralizeRequest.md)|  | 

### Return type

[**CollateralizeResponse**](CollateralizeResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageDeCollateralize**
> DeCollateralizeResponse LeverageDeCollateralize(ctx, body)
Move collateral and supplied_collateral to available and supplied, for a specified position.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**DeCollateralizeRequest**](DeCollateralizeRequest.md)|  | 

### Return type

[**DeCollateralizeResponse**](DeCollateralizeResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageIsolateCollateral**
> IsolateCollateralResponse LeverageIsolateCollateral(ctx, body)
Create an isolated position by transferring collateral to the position from the user's global collateral

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**IsolateCollateralRequest**](IsolateCollateralRequest.md)|  | 

### Return type

[**IsolateCollateralResponse**](IsolateCollateralResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageIsolatePosition**
> IsolatePositionResponse LeverageIsolatePosition(ctx, body)
Create an isolated position using all collateral, supplied_collateral, and borrows from the user's global position

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**IsolatePositionRequest**](IsolatePositionRequest.md)|  | 

### Return type

[**IsolatePositionResponse**](IsolatePositionResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **LeverageRepay**
> RepayResponse LeverageRepay(ctx, body)
Repay borrowed assets

TODO: Finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**RepayRequest**](RepayRequest.md)|  | 

### Return type

[**RepayResponse**](RepayResponse.md)

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

# **LeverageUnite**
> UnitePositionResponse LeverageUnite(ctx, body)
Combines all isolated positions into a single global position

TODO: Finish this when implementation has been completed

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UnitePositionRequest**](UnitePositionRequest.md)|  | 

### Return type

[**UnitePositionResponse**](UnitePositionResponse.md)

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
> ListAssetsResponse ListAssets(ctx, optional)
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
 **assetKind** | [**optional.Interface of AssetKind**](.md)| Asset kind (BOND, CURRENCY, INTEREST, POOL_SHARE) | 
 **canAddLiquidity** | **optional.Bool**|  | 
 **canDirectBorrow** | **optional.Bool**|  | 
 **canOnboard** | **optional.Bool**|  | 
 **canTrade** | **optional.Bool**|  | 
 **canVirtualBorrow** | **optional.Bool**|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**ListAssetsResponse**](ListAssetsResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ListOrderBooks**
> ListOrderBooksResponse ListOrderBooks(ctx, optional)
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
 **status** | [**optional.Interface of OrderBookStatus**](.md)|  | 
 **baseAssetId** | [**optional.Interface of string**](.md)|  | 
 **quoteAssetId** | [**optional.Interface of string**](.md)|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**ListOrderBooksResponse**](ListOrderBooksResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ListOrders**
> ListOrdersResponse ListOrders(ctx, optional)
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
 **orderBookId** | [**optional.Interface of []string**](string.md)|  | 
 **kind** | [**optional.Interface of OrderKind**](.md)|  | 
 **status** | [**optional.Interface of OrderStatus**](.md)|  | 
 **side** | [**optional.Interface of Side**](.md)|  | 
 **from** | **optional.Time**|  | 
 **to** | **optional.Time**|  | 
 **page** | **optional.Int32**|  | [default to 1]
 **limit** | **optional.Int32**|  | [default to 100]

### Return type

[**ListOrdersResponse**](ListOrdersResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamAssetPrices**
> ListAssetPriceResponse StreamAssetPrices(ctx, optional)
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

[**ListAssetPriceResponse**](ListAssetPriceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamCandleData**
> ListCandlesResponse StreamCandleData(ctx, orderbook, optional)
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
 **resolution** | [**optional.Interface of CandleResolution**](.md)|  | 

### Return type

[**ListCandlesResponse**](ListCandlesResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamOrderBookBalances**
> OrderBookBalanceResponse StreamOrderBookBalances(ctx, orderBookId, optional)
Get a snapshot of base and quote balances for an order book and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 
 **optional** | ***DefaultApiStreamOrderBookBalancesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamOrderBookBalancesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **optional.Time**|  | 

### Return type

[**OrderBookBalanceResponse**](OrderBookBalanceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamOrderbookOpenOrders**
> ListOrdersResponse StreamOrderbookOpenOrders(ctx, orderBookId, optional)
Get a snapshot of open orders in an order book and open a stream for real-time updates

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orderBookId** | [**string**](.md)|  | 
 **optional** | ***DefaultApiStreamOrderbookOpenOrdersOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a DefaultApiStreamOrderbookOpenOrdersOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **since** | **optional.Time**|  | 

### Return type

[**ListOrdersResponse**](ListOrdersResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **StreamTrades**
> ListTradeResponse StreamTrades(ctx, orderbookId, optional)
Get a snapshot of trades executed on the given order book from a specific date and open a stream for real-time updates

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

[**ListTradeResponse**](ListTradeResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUserConfig**
> UserUpdatedResponse UpdateUserConfig(ctx, body, userId)
Update user configuration by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserConfigRequest**](UpdateUserConfigRequest.md)|  | 
  **userId** | [**string**](.md)|  | 

### Return type

[**UserUpdatedResponse**](UserUpdatedResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UpdateUserConfigSelf**
> UserUpdatedResponse UpdateUserConfigSelf(ctx, body)
Update user configuration for the authenticated user

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**UpdateUserConfigRequest**](UpdateUserConfigRequest.md)|  | 

### Return type

[**UserUpdatedResponse**](UserUpdatedResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **VerifyUser**
> UserUpdatedResponse VerifyUser(ctx, userId)
Verify a user by ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | [**string**](.md)|  | 

### Return type

[**UserUpdatedResponse**](UserUpdatedResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

