---
title: "Metered"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "統合のための計測付きメソッドを提供します"
type: docs
weight: 71
url: /ja/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

統合のための計測付きメソッドを提供します

この例では、メーター付きの公開キーと秘密キーを設定しようとします。

// コンポーネントの JAR ファイル: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey");
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Metered()](#Metered--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判定します。 |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | 消費クレジットを取得します |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 消費ファイルサイズを取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | メーター付きの公開キーと秘密キーを設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Metered() {#Metered--}
```
public Metered()
```


### FlushTimeout_internalized {#FlushTimeout-internalized}
```
public static int FlushTimeout_internalized
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトがこのインスタンスと等しいかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するオブジェクトです。 |

**Returns:**
boolean -  指定された Object がこのインスタンスと等しい場合は true、そうでない場合は false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


消費クレジットを取得します

**Returns:**
java.math.BigDecimal - 消費数量
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


消費ファイルサイズを取得します

**Returns:**
java.math.BigDecimal - 消費ファイルサイズ
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


メーター付きの公開キーと秘密キーを設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| publicKey | java.lang.String | 公開鍵 |
| privateKey | java.lang.String | 秘密鍵 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

