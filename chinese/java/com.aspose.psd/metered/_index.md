---
title: "计量的"
second_title: "Aspose.PSD 的 Java API 参考"
description: "提供用于集成的计量方法"
type: docs
weight: 71
url: /zh/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

提供用于集成的计量方法

在此示例中，将尝试设置计量的公钥和私钥。

// 组件 jar 文件：Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey");
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于此实例。 |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | 获取消耗积分 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 获取消耗文件大小 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 设置计量的公钥和私钥 |
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


确定指定的 Object 是否等于此实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的对象。 |

**Returns:**
布尔值 -  true  如果指定的对象等于此实例；否则为  false .
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


获取消耗积分

**Returns:**
java.math.BigDecimal - 消耗数量
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


获取消耗文件大小

**Returns:**
java.math.BigDecimal - 消耗文件大小
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


设置计量的公钥和私钥

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| publicKey | java.lang.String | 公钥 |
| privateKey | java.lang.String | 私钥 |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

