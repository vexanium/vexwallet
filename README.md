# vexwallet
the vexanium vexwallet application including desktop, android and ios

## Rest API Registration Account VexWallet

### 1. Get Verification Code

> URL = ```http://vexwallet.com/api/get-sms-verification``` 

Parameter
* phone_number
> Note = input phone number with “OFF” after phonenumber ```Exp = 11515151OFF```


### 2. Regist Account Vexwallet

> URL = ```http://vexwallet.com/api/activate-account``` 

Parameter
* phone_number
* verification_code
* public_key
* account_name
