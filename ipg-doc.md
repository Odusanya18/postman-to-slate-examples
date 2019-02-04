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

# Passport request


Passport Request additional description here

## null
```shell
curl "/passport/oauth/token" -X POST
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PassportRequestApi();
api.post_passport_oauth_token(grant_type, authorization);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PassportRequestApi;

ApiClient apiClient = new ApiClient();

PassportRequestApi api = new PassportRequestApi(apiClient);
api.postPassportOauthToken(grantType, authorization);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PassportRequestApi($api_client);
$api->postPassportOauthToken($grant_type, $authorization);




```

### HTTP Request
`POST /passport/oauth/token`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||


### Query Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|grant_type|true|string||


### Responses for status codes
|default|
|----|
||


# Purchase with card


This illustrates how to make a basic purchase using a card.

Due to regulation from PCI DSS, all card details are encrypted and data is sent in the form of AuthData which is a combination of the following details:

 - PAN
 - PIN
 - Expiry Date
 - CVV

Encryption of these details is done using the BouncyCastle library and all implementations of it must be done in the language of your choice.


You can contact ipg@interswitchgroup.com for details or preferably see an example of its implementation from our Github repositories specified [here](https://github.com/techquest)

## This illustrates how to make a basic purchase using a card.

Due to regulation from PCI DSS, all card details are encrypted and data is sent in the form of AuthData which is a combination of the following details:

 - PAN
 - PIN
 - Expiry Date
 - CVV

Encryption of these details is done using the BouncyCastle library and all implementations of it must be done in the language of your choice.


You can contact ipg@interswitchgroup.com for details or preferably see an example of its implementation from our Github repositories specified [here](https://github.com/techquest)
```shell
curl "/api/v3/purchases" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.PurchaseWithCardApi();
api.post_api_v3_purchases(body, authorization, timestamp, nonce, signature, signature_method, auth_key_version);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.PurchaseWithCardApi;

ApiClient apiClient = new ApiClient();

PurchaseWithCardApi api = new PurchaseWithCardApi(apiClient);
api.postApiV3Purchases(body, authorization, timestamp, nonce, signature, signatureMethod, authKeyVersion);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\PurchaseWithCardApi($api_client);
$api->postApiV3Purchases($body, $authorization, $timestamp, $nonce, $signature, $signature_method, $auth_key_version);




```

### HTTP Request
`POST /api/v3/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|AuthKeyVersion|true|string||


### Body Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|amount|false|string||
|authData|false|string||
|customerId|false|string||
|transactionRef|false|string||
|currency|false|string||


### Responses for status codes
|default|
|----|
||



This illustrates how to make a basic purchase using a card.

Due to regulation from PCI DSS, all card details are encrypted and data is sent in the form of AuthData which is a combination of the following details:

 - PAN
 - PIN
 - Expiry Date
 - CVV

Encryption of these details is done using the BouncyCastle library and all implementations of it must be done in the language of your choice.


You can contact ipg@interswitchgroup.com for details or preferably see an example of its implementation from our Github repositories specified [here](https://github.com/techquest)

# Otp validation request


OTP Validation Request additional description here

## null
```shell
curl "/api/v3/purchases/otps/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.OTPValidationRequestApi();
api.post_api_v3_purchases_otps_auths(body, authorization, timestamp, nonce, signature, signature_method, auth_key_version);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.OTPValidationRequestApi;

ApiClient apiClient = new ApiClient();

OTPValidationRequestApi api = new OTPValidationRequestApi(apiClient);
api.postApiV3PurchasesOtpsAuths(body, authorization, timestamp, nonce, signature, signatureMethod, authKeyVersion);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\OTPValidationRequestApi($api_client);
$api->postApiV3PurchasesOtpsAuths($body, $authorization, $timestamp, $nonce, $signature, $signature_method, $auth_key_version);




```

### HTTP Request
`POST /api/v3/purchases/otps/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|AuthKeyVersion|true|string||


### Body Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|authData|false|string||
|paymentId|false|string||
|otp|false|string||


### Responses for status codes
|default|
|----|
||


# Visa auth page (load page for ipin)


VISA Auth Page (Load Page for iPIN) additional description here

## null
```shell
curl "/V3DSStart" -X POST
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.VISAAuthPageLoadPageForIPINApi();
api.post_v3_ds_start(term_url, pa_req, md, osb, vaa);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.VISAAuthPageLoadPageForIPINApi;

ApiClient apiClient = new ApiClient();

VISAAuthPageLoadPageForIPINApi api = new VISAAuthPageLoadPageForIPINApi(apiClient);
api.postV3DSStart(termUrl, paReq, MD, osb, VAA);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\VISAAuthPageLoadPageForIPINApi($api_client);
$api->postV3DSStart($term_url, $pa_req, $md, $osb, $vaa);




```

### HTTP Request
`POST /V3DSStart`
### Query Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|TermUrl|true|string||
|PaReq|true|string||
|MD|true|string||
|osb|true|string||
|VAA|true|string||


### Responses for status codes
|default|
|----|
||


# Visa  > isw callback


VISA -> ISW CallBack additional description here

## null
```shell
curl "/collections/api/v1/pay/cardinalCallBack" -X POST
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.VISAISWCallBackApi();
api.post_collections_api_v1_pay_cardinal_call_back(accept, accept_encoding, accept_language, content_length, md, pa_res, user_agent);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.VISAISWCallBackApi;

ApiClient apiClient = new ApiClient();

VISAISWCallBackApi api = new VISAISWCallBackApi(apiClient);
api.postCollectionsApiV1PayCardinalCallBack(accept, acceptEncoding, acceptLanguage, contentLength, MD, paRes, userAgent);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\VISAISWCallBackApi($api_client);
$api->postCollectionsApiV1PayCardinalCallBack($accept, $accept_encoding, $accept_language, $content_length, $md, $pa_res, $user_agent);




```

### HTTP Request
`POST /collections/api/v1/pay/cardinalCallBack`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Accept|true|string||
|Accept-Encoding|true|string||
|Accept-Language|true|string||
|Content-Length|true|string||
|User-Agent|true|string||


### Query Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|MD|true|string||
|PaRes|true|string||


### Responses for status codes
|default|
|----|
||


# Enroll card for otp


Enroll card for OTP additional description here

## null
```shell
curl "/api/v3/purchases/otps/enrollments" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.EnrollCardForOTPApi();
api.post_api_v3_purchases_otps_enrollments(body, authorization, timestamp, nonce, signature, signature_method, auth_key_version);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.EnrollCardForOTPApi;

ApiClient apiClient = new ApiClient();

EnrollCardForOTPApi api = new EnrollCardForOTPApi(apiClient);
api.postApiV3PurchasesOtpsEnrollments(body, authorization, timestamp, nonce, signature, signatureMethod, authKeyVersion);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\EnrollCardForOTPApi($api_client);
$api->postApiV3PurchasesOtpsEnrollments($body, $authorization, $timestamp, $nonce, $signature, $signature_method, $auth_key_version);




```

### HTTP Request
`POST /api/v3/purchases/otps/enrollments`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|AuthKeyVersion|true|string||


### Body Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|mobilePhoneNumber|false|string||
|paymentId|false|string||
|transactionRef|false|string||


### Responses for status codes
|default|
|----|
||


# Validation request   otp


Validation Request - OTP additional description here

## null
```shell
curl "/api/v3/purchases/validations/otps/auths" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidationRequestOTPApi();
api.post_api_v3_purchases_validations_otps_auths(body, authorization, timestamp, nonce, signature, signature_method, auth_key_version);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidationRequestOTPApi;

ApiClient apiClient = new ApiClient();

ValidationRequestOTPApi api = new ValidationRequestOTPApi(apiClient);
api.postApiV3PurchasesValidationsOtpsAuths(body, authorization, timestamp, nonce, signature, signatureMethod, authKeyVersion);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidationRequestOTPApi($api_client);
$api->postApiV3PurchasesValidationsOtpsAuths($body, $authorization, $timestamp, $nonce, $signature, $signature_method, $auth_key_version);




```

### HTTP Request
`POST /api/v3/purchases/validations/otps/auths`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|AuthKeyVersion|true|string||


### Body Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|transactionRef|false|string||
|otp|false|string||


### Responses for status codes
|default|
|----|
||


# Validation request


Validation Request additional description here

## null
```shell
curl "/api/v3/purchases/validations" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.ValidationRequestApi();
api.post_api_v3_purchases_validations(body, authorization, timestamp, nonce, signature, signature_method, auth_key_version);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.ValidationRequestApi;

ApiClient apiClient = new ApiClient();

ValidationRequestApi api = new ValidationRequestApi(apiClient);
api.postApiV3PurchasesValidations(body, authorization, timestamp, nonce, signature, signatureMethod, authKeyVersion);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\ValidationRequestApi($api_client);
$api->postApiV3PurchasesValidations($body, $authorization, $timestamp, $nonce, $signature, $signature_method, $auth_key_version);




```

### HTTP Request
`POST /api/v3/purchases/validations`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|AuthKeyVersion|true|string||


### Body Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|authData|false|string||
|transactionRef|false|string||


### Responses for status codes
|default|
|----|
||


# Recurrent purchase


Recurrent Purchase additional description here

## null
```shell
curl "/api/v2/purchases/recurrents" -X POST -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.RecurrentPurchaseApi();
api.post_api_v2_purchases_recurrents(body, authorization, timestamp, nonce, signature, signature_method, auth_key_version);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.RecurrentPurchaseApi;

ApiClient apiClient = new ApiClient();

RecurrentPurchaseApi api = new RecurrentPurchaseApi(apiClient);
api.postApiV2PurchasesRecurrents(body, authorization, timestamp, nonce, signature, signatureMethod, authKeyVersion);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\RecurrentPurchaseApi($api_client);
$api->postApiV2PurchasesRecurrents($body, $authorization, $timestamp, $nonce, $signature, $signature_method, $auth_key_version);




```

### HTTP Request
`POST /api/v2/purchases/recurrents`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|AuthKeyVersion|true|string||


### Body Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|amount|false|string||
|tokenExpiryDate|false|string||
|customerId|false|string||
|transactionRef|false|string||
|currency|false|string||
|token|false|string||


### Responses for status codes
|default|
|----|
||


# Recurrent get token


Recurrent Get Token additional description here

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


api = client.RecurrentGetTokenApi();
api.post_api_v2_purchases_validations_recurrents(body, authorization, timestamp, nonce, signature, signature_method, auth_key_version);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.RecurrentGetTokenApi;

ApiClient apiClient = new ApiClient();

RecurrentGetTokenApi api = new RecurrentGetTokenApi(apiClient);
api.postApiV2PurchasesValidationsRecurrents(body, authorization, timestamp, nonce, signature, signatureMethod, authKeyVersion);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\RecurrentGetTokenApi($api_client);
$api->postApiV2PurchasesValidationsRecurrents($body, $authorization, $timestamp, $nonce, $signature, $signature_method, $auth_key_version);




```

### HTTP Request
`POST /api/v2/purchases/validations/recurrents`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Authorization|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|AuthKeyVersion|true|string||


### Body Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|authData|false|string||
|transactionRef|false|string||


### Responses for status codes
|default|
|----|
||


# Get transaction status   system malfunction


Get Transaction Status - System Malfunction additional description here

## null
```shell
curl "/api/v3/purchases" -X GET -d @- << EOF 
{ }
EOF
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetTransactionStatusSystemMalfunctionApi();
api.get_api_v3_purchases(amount, transaction_ref, , body, authorization, timestamp, nonce, signature, signature_method, auth_key_version);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetTransactionStatusSystemMalfunctionApi;

ApiClient apiClient = new ApiClient();

GetTransactionStatusSystemMalfunctionApi api = new GetTransactionStatusSystemMalfunctionApi(apiClient);
api.getApiV3Purchases(amount, transactionRef, _______________________________________________________________________________________________, body, authorization, timestamp, nonce, signature, signatureMethod, authKeyVersion);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetTransactionStatusSystemMalfunctionApi($api_client);
$api->getApiV3Purchases($amount, $transaction_ref, $_______________________________________________________________________________________________, $body, $authorization, $timestamp, $nonce, $signature, $signature_method, $auth_key_version);




```

### HTTP Request
`GET /api/v3/purchases`
### Header Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|Amount|true|string||
|transactionRef|true|string||
|-----------------------------------------------------------------------------------------------|true|string||
|Authorization|true|string||
|Timestamp|true|string||
|Nonce|true|string||
|Signature|true|string||
|SignatureMethod|true|string||
|AuthKeyVersion|true|string||


### Responses for status codes
|default|
|----|
||


# Get transaction 2.0 


Returns Bank Code and Account Number

## Returns Bank Code and Account Number
```shell
curl "/collections/api/v1/gettransaction.json" -X GET
```

```python



from ..api_client import ApiClient;
from ..configuration import Configuration

apiClient = client.ApiClient("")


api = client.GetTransactionApi();
api.get_collections_api_v1_gettransaction_json(getacquirerdata, transactionreference, amount, merchantcode);



```

```java


import interswitchng.com.ApiClient;
import interswitchng.com.GetTransactionApi;

ApiClient apiClient = new ApiClient();

GetTransactionApi api = new GetTransactionApi(apiClient);
api.getCollectionsApiV1GettransactionJson(getacquirerdata, transactionreference, amount, merchantcode);


```

```php




require_once('/path/to/interswitchng.com');

$api_client = new Swagger\Client\ApiClient('');



$api = new Swagger\Client\GetTransactionApi($api_client);
$api->getCollectionsApiV1GettransactionJson($getacquirerdata, $transactionreference, $amount, $merchantcode);




```

### HTTP Request
`GET /collections/api/v1/gettransaction.json`
### Query Parameters
|Parameter|Required|Type|Description|
|----|----|----|----|
|getacquirerdata|true|string||
|transactionreference|true|string||
|amount|true|string||
|merchantcode|true|string||


### Responses for status codes
|default|
|----|
||



Returns Bank Code and Account Number



