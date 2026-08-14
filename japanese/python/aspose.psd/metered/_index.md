---
title: "Metered クラス"
type: docs
weight: 3030
url: /ja/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Metered()](#Metered__1) | Metered クラスの新しいインスタンスを初期化します |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | 消費クレジットを取得します |
| [get_consumption_quantity()](#get_consumption_quantity__2) | 消費ファイルサイズを取得します |
| [get_product_name()](#get_product_name__3) | 製品の名前を取得します。 |
| [is_metered_licensed()](#is_metered_licensed__4) | Metered がライセンスされているか確認します |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Metered の公開鍵と秘密鍵を設定します。<br/>            メーターライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常、これだけで十分です。 <br/>            ただし、消費データのアップロードに常に失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。 <br/>            このような事態を回避するために、ライセンスステータスを定期的に確認し、評価ステータスであれば再度この API を呼び出してください。 |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Metered クラスの新しいインスタンスを初期化します

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

消費クレジットを取得します

**Returns**

| タイプ | 説明 |
| :- | :- |
| 小数 | 消費量 |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

消費ファイルサイズを取得します

**Returns**

| タイプ | 説明 |
| :- | :- |
| 小数 | 消費量 |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

製品の名前を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | ライセンス製品の名前 |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Metered がライセンスされているか確認します

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 真偽 |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Metered の公開鍵と秘密鍵を設定します。<br/>            メーターライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常、これだけで十分です。 <br/>            ただし、消費データのアップロードに常に失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。 <br/>            このような事態を回避するために、ライセンスステータスを定期的に確認し、評価ステータスであれば再度この API を呼び出してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| public_key | string | 公開鍵 |
| private_key | string | 秘密鍵 |

