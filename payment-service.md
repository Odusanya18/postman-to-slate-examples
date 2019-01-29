---
title: API Reference
language_tabs:
  - shell
  - php
  - java
  - python
toc_footers:
includes:
    - errors
search: true
---
# Introduction

```
We have language bindings in php, java, python! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.
```

### Version
Version: 2.0

# Get ewallet payment instrument with user access token


Get ewallet Payment Instrument with user access token additional description here

## null
```shell
curl "/api/v1/ewallet/instruments" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetEwalletPaymentInstrumentWithUserAccessTokenApi();
api.get_api_v1_ewallet_instruments(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetEwalletPaymentInstrumentWithUserAccessTokenApi;

ApiClient apiClient = new ApiClient();

GetEwalletPaymentInstrumentWithUserAccessTokenApi api = new GetEwalletPaymentInstrumentWithUserAccessTokenApi(apiClient);
api.getApiV1EwalletInstruments(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetEwalletPaymentInstrumentWithUserAccessTokenApi($api_client);
$api->getApiV1EwalletInstruments($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`GET /api/v1/ewallet/instruments`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Paying with user access token and payment identifier


Paying with user access token and payment identifier additional description here

## null
```shell
curl "/api/v1/ewallet/purchases" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PayingWithUserAccessTokenAndPaymentIdentifierApi();
api.post_api_v1_ewallet_purchases(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PayingWithUserAccessTokenAndPaymentIdentifierApi;

ApiClient apiClient = new ApiClient();

PayingWithUserAccessTokenAndPaymentIdentifierApi api = new PayingWithUserAccessTokenAndPaymentIdentifierApi(apiClient);
api.postApiV1EwalletPurchases(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PayingWithUserAccessTokenAndPaymentIdentifierApi($api_client);
$api->postApiV1EwalletPurchases($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v1/ewallet/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Ewallet service status


Ewallet Service Status additional description here

## null
```shell
curl "/api/v1/ewallet/status" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.EwalletServiceStatusApi();
api.get_api_v1_ewallet_status(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.EwalletServiceStatusApi;

ApiClient apiClient = new ApiClient();

EwalletServiceStatusApi api = new EwalletServiceStatusApi(apiClient);
api.getApiV1EwalletStatus(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\EwalletServiceStatusApi($api_client);
$api->getApiV1EwalletStatus($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`GET /api/v1/ewallet/status`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Generate processor access token


Generate Processor Access Token additional description here

## null
```shell
curl "/passport/oauth/token" -X POST
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GenerateProcessorAccessTokenApi();
api.post_passport_oauth_token(authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GenerateProcessorAccessTokenApi;

ApiClient apiClient = new ApiClient();

GenerateProcessorAccessTokenApi api = new GenerateProcessorAccessTokenApi(apiClient);
api.postPassportOauthToken(authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GenerateProcessorAccessTokenApi($api_client);
$api->postPassportOauthToken($authorization);




```

### HTTP Request
`POST /passport/oauth/token`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Purchase service status


Purchase Service Status additional description here

## null
```shell
curl "/api/v1/purchases/status" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PurchaseServiceStatusApi();
api.get_api_v1_purchases_status(content_type, signature, signature_method, timestamp, nonce, authorization, body, transaction_ref);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PurchaseServiceStatusApi;

ApiClient apiClient = new ApiClient();

PurchaseServiceStatusApi api = new PurchaseServiceStatusApi(apiClient);
api.getApiV1PurchasesStatus(contentType, signature, signatureMethod, timestamp, nonce, authorization, body, transactionRef);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PurchaseServiceStatusApi($api_client);
$api->getApiV1PurchasesStatus($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body, $transaction_ref);




```

### HTTP Request
`GET /api/v1/purchases/status`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||
|transactionRef|false|string||


### Responses for status codes
|default|
|----|
||


# Get user access token


Get User Access Token additional description here

## null
```shell
curl "/api/v1/ewallet/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetUserAccessTokenApi();
api.post_api_v1_ewallet_auths(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetUserAccessTokenApi;

ApiClient apiClient = new ApiClient();

GetUserAccessTokenApi api = new GetUserAccessTokenApi(apiClient);
api.postApiV1EwalletAuths(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetUserAccessTokenApi($api_client);
$api->postApiV1EwalletAuths($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v1/ewallet/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Processor payment 


Processor Payment  additional description here

## null
```shell
curl "/api/v1/purchases" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ProcessorPaymentApi();
api.post_api_v1_purchases(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ProcessorPaymentApi;

ApiClient apiClient = new ApiClient();

ProcessorPaymentApi api = new ProcessorPaymentApi(apiClient);
api.postApiV1Purchases(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ProcessorPaymentApi($api_client);
$api->postApiV1Purchases($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v1/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Get transaction status


Get transaction status additional description here

## null
```shell
curl "/api/v1/purchases" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetTransactionStatusApi();
api.get_api_v1_purchases(content_type, signature, signature_method, timestamp, nonce, authorization, amount, transaction_ref, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetTransactionStatusApi;

ApiClient apiClient = new ApiClient();

GetTransactionStatusApi api = new GetTransactionStatusApi(apiClient);
api.getApiV1Purchases(contentType, signature, signatureMethod, timestamp, nonce, authorization, amount, transactionRef, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetTransactionStatusApi($api_client);
$api->getApiV1Purchases($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $amount, $transaction_ref, $body);




```

### HTTP Request
`GET /api/v1/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||
|amount|true|string||
|transactionRef|true|string||


### Responses for status codes
|default|
|----|
||


# Processor otp complete transaction


Processor OTP complete transaction additional description here

## null
```shell
curl "/api/v1/purchases/otps/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ProcessorOTPCompleteTransactionApi();
api.post_api_v1_purchases_otps_auths(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ProcessorOTPCompleteTransactionApi;

ApiClient apiClient = new ApiClient();

ProcessorOTPCompleteTransactionApi api = new ProcessorOTPCompleteTransactionApi(apiClient);
api.postApiV1PurchasesOtpsAuths(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ProcessorOTPCompleteTransactionApi($api_client);
$api->postApiV1PurchasesOtpsAuths($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v1/purchases/otps/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Processor validate card


Processor validate card additional description here

## null
```shell
curl "/api/v1/purchases/validations" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ProcessorValidateCardApi();
api.post_api_v1_purchases_validations(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ProcessorValidateCardApi;

ApiClient apiClient = new ApiClient();

ProcessorValidateCardApi api = new ProcessorValidateCardApi(apiClient);
api.postApiV1PurchasesValidations(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ProcessorValidateCardApi($api_client);
$api->postApiV1PurchasesValidations($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v1/purchases/validations`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Gateway payment without otp


Gateway Payment without OTP additional description here

## null
```shell
curl "/api/v1/payment/gateway/purchase" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GatewayPaymentWithoutOTPApi();
api.post_api_v1_payment_gateway_purchase(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GatewayPaymentWithoutOTPApi;

ApiClient apiClient = new ApiClient();

GatewayPaymentWithoutOTPApi api = new GatewayPaymentWithoutOTPApi(apiClient);
api.postApiV1PaymentGatewayPurchase(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GatewayPaymentWithoutOTPApi($api_client);
$api->postApiV1PaymentGatewayPurchase($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v1/payment/gateway/purchase`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Webpay


Webpay additional description here

## null
```shell
curl "/webpay/api/v2/pay.json" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.WebpayApi();
api.post_webpay_api_v2_pay_json(content_type, authorization, terminal_id, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.WebpayApi;

ApiClient apiClient = new ApiClient();

WebpayApi api = new WebpayApi(apiClient);
api.postWebpayApiV2PayJson(contentType, authorization, terminalId, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\WebpayApi($api_client);
$api->postWebpayApiV2PayJson($content_type, $authorization, $terminal_id, $body);




```

### HTTP Request
`POST /webpay/api/v2/pay.json`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Authorization|true|string||
|TerminalId|true|string||


### Responses for status codes
|default|
|----|
||


# Payment v2


Payment V2 additional description here

## null
```shell
curl "/api/v2/purchases" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PaymentVApi();
api.post_api_v2_purchases(signature, signature_method, timestamp, nonce, authorization, content_type, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PaymentVApi;

ApiClient apiClient = new ApiClient();

PaymentVApi api = new PaymentVApi(apiClient);
api.postApiV2Purchases(signature, signatureMethod, timestamp, nonce, authorization, contentType, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PaymentVApi($api_client);
$api->postApiV2Purchases($signature, $signature_method, $timestamp, $nonce, $authorization, $content_type, $body);




```

### HTTP Request
`POST /api/v2/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||
|Content-Type|true|string||


### Responses for status codes
|default|
|----|
||


# Payment otp v2


Payment OTP V2 additional description here

## null
```shell
curl "/api/v2/purchases/otps/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PaymentOTPVApi();
api.post_api_v2_purchases_otps_auths(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PaymentOTPVApi;

ApiClient apiClient = new ApiClient();

PaymentOTPVApi api = new PaymentOTPVApi(apiClient);
api.postApiV2PurchasesOtpsAuths(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PaymentOTPVApi($api_client);
$api->postApiV2PurchasesOtpsAuths($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v2/purchases/otps/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Validation v2


Validation V2 additional description here

## null
```shell
curl "/api/v2/purchases/validations" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidationVApi();
api.post_api_v2_purchases_validations(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidationVApi;

ApiClient apiClient = new ApiClient();

ValidationVApi api = new ValidationVApi(apiClient);
api.postApiV2PurchasesValidations(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidationVApi($api_client);
$api->postApiV2PurchasesValidations($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v2/purchases/validations`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Validation otp v2


Validation OTP V2 additional description here

## null
```shell
curl "/api/v2/purchases/validations/otps/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidationOTPVApi();
api.post_api_v2_purchases_validations_otps_auths(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidationOTPVApi;

ApiClient apiClient = new ApiClient();

ValidationOTPVApi api = new ValidationOTPVApi(apiClient);
api.postApiV2PurchasesValidationsOtpsAuths(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidationOTPVApi($api_client);
$api->postApiV2PurchasesValidationsOtpsAuths($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v2/purchases/validations/otps/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Payment otp auto enroll


Payment OTP Auto Enroll additional description here

## null
```shell
curl "/api/v2/purchases/otps/enrollments" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PaymentOTPAutoEnrollApi();
api.post_api_v2_purchases_otps_enrollments(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PaymentOTPAutoEnrollApi;

ApiClient apiClient = new ApiClient();

PaymentOTPAutoEnrollApi api = new PaymentOTPAutoEnrollApi(apiClient);
api.postApiV2PurchasesOtpsEnrollments(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PaymentOTPAutoEnrollApi($api_client);
$api->postApiV2PurchasesOtpsEnrollments($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v2/purchases/otps/enrollments`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Payment v2 status new


Payment V2 Status New additional description here

## null
```shell
curl "/api/v2/purchases" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PaymentVStatusNewApi();
api.get_api_v2_purchases(content_type, signature, signature_method, timestamp, nonce, authorization, transaction_ref, amount, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PaymentVStatusNewApi;

ApiClient apiClient = new ApiClient();

PaymentVStatusNewApi api = new PaymentVStatusNewApi(apiClient);
api.getApiV2Purchases(contentType, signature, signatureMethod, timestamp, nonce, authorization, transactionRef, amount, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PaymentVStatusNewApi($api_client);
$api->getApiV2Purchases($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $transaction_ref, $amount, $body);




```

### HTTP Request
`GET /api/v2/purchases`
### Query Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|transactionRef|true|string||
|amount|true|string||


### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Validaiton otp auto enroll


Validaiton OTP Auto Enroll additional description here

## null
```shell
curl "/api/v2/purchases/validations/otps/enrollments" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidaitonOTPAutoEnrollApi();
api.post_api_v2_purchases_validations_otps_enrollments(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidaitonOTPAutoEnrollApi;

ApiClient apiClient = new ApiClient();

ValidaitonOTPAutoEnrollApi api = new ValidaitonOTPAutoEnrollApi(apiClient);
api.postApiV2PurchasesValidationsOtpsEnrollments(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidaitonOTPAutoEnrollApi($api_client);
$api->postApiV2PurchasesValidationsOtpsEnrollments($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v2/purchases/validations/otps/enrollments`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||


# Validation recurrent


Validation Recurrent additional description here

## null
```shell
curl "/api/v2/purchases/validations/recurrents" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidationRecurrentApi();
api.post_api_v2_purchases_validations_recurrents(content_type, signature, signature_method, timestamp, nonce, authorization, body);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidationRecurrentApi;

ApiClient apiClient = new ApiClient();

ValidationRecurrentApi api = new ValidationRecurrentApi(apiClient);
api.postApiV2PurchasesValidationsRecurrents(contentType, signature, signatureMethod, timestamp, nonce, authorization, body);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidationRecurrentApi($api_client);
$api->postApiV2PurchasesValidationsRecurrents($content_type, $signature, $signature_method, $timestamp, $nonce, $authorization, $body);




```

### HTTP Request
`POST /api/v2/purchases/validations/recurrents`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Content-Type|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Authorization|true|string||


### Responses for status codes
|default|
|----|
||




