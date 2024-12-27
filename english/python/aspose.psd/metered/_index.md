---
title: Metered Class
type: docs
weight: 3030
url: /python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Metered()](#Metered__1) | Initializes a new instance of the Metered class |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Gets consumption credit |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Gets consumption file size |
| [get_product_name()](#get_product_name__3) | Gets the name of the product. |
| [is_metered_licensed()](#is_metered_licensed__4) | Check whether metered is licensed |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Sets metered public and private key.<br/>            If you purchase metered license, when start application, this API should be called, normally, this is enough. <br/>            However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, <br/>            to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Initializes a new instance of the Metered class

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Gets consumption credit

**Returns**

| Type | Description |
| :- | :- |
| decimal | consumption quantity |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Gets consumption file size

**Returns**

| Type | Description |
| :- | :- |
| decimal | consumption quantity |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Gets the name of the product.

**Returns**

| Type | Description |
| :- | :- |
| string | Name of Licensed product |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Check whether metered is licensed

**Returns**

| Type | Description |
| :- | :- |
| bool | True or false |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Sets metered public and private key.<br/>            If you purchase metered license, when start application, this API should be called, normally, this is enough. <br/>            However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, <br/>            to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| public_key | string | public key |
| private_key | string | private key |

