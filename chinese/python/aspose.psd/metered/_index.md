---
title: "计量类"
type: docs
weight: 3030
url: /zh/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Metered()](#Metered__1) | 初始化 Metered 类的新实例 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | 获取消耗信用 |
| [get_consumption_quantity()](#get_consumption_quantity__2) | 获取消耗文件大小 |
| [get_product_name()](#get_product_name__3) | 获取产品的名称。 |
| [is_metered_licensed()](#is_metered_licensed__4) | 检查 metered 是否已授权 |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | 设置 metered 的公钥和私钥。<br/>            如果您购买了 metered 许可证，在启动应用程序时应调用此 API，通常这就足够。 <br/>            但是，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态， <br/>            为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

初始化 Metered 类的新实例

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

获取消耗信用

**Returns**

| 类型 | 描述 |
| :- | :- |
| 十进制 | 消耗数量 |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

获取消耗文件大小

**Returns**

| 类型 | 描述 |
| :- | :- |
| 十进制 | 消耗数量 |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

获取产品的名称。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 已授权产品的名称 |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

检查 metered 是否已授权

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 真或假 |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

设置 metered 的公钥和私钥。<br/>            如果您购买了 metered 许可证，在启动应用程序时应调用此 API，通常这就足够。 <br/>            但是，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态， <br/>            为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| public_key | 字符串 | 公钥 |
| private_key | 字符串 | 私钥 |

