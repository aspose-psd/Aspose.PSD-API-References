---
title: "许可证"
second_title: "Aspose.PSD 的 Java API 参考"
description: "提供对组件授权的方法。"
type: docs
weight: 65
url: /zh/java/com.aspose.psd/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

提供对组件授权的方法。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License--) | 初始化此类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrorCodeMessages()](#getErrorCodeMessages--) | 获取错误代码消息。 |
| [getRenewSubscriptionStartMessage()](#getRenewSubscriptionStartMessage--) | 获取续订开始消息。 |
| [hashCode()](#hashCode--) |  |
| [isLicensed_internalized()](#isLicensed-internalized--) | 获取一个值，指示产品是否已授权。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeLicense()](#removeLicense--) |  |
| [setLicense(File licenseFile)](#setLicense-java.io.File-) | 为组件授权。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 为组件授权。 |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 为组件授权。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


初始化此类的新实例。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorCodeMessages() {#getErrorCodeMessages--}
```
public static ByteObjDictionary<String> getErrorCodeMessages()
```


获取错误代码消息。

值：错误代码消息。

**Returns:**
com.aspose.java.optimization.maps.ByteObjDictionary<java.lang.String> - 错误代码消息。
### getRenewSubscriptionStartMessage() {#getRenewSubscriptionStartMessage--}
```
public static String getRenewSubscriptionStartMessage()
```


获取续订开始消息。

值：续订开始消息。

**Returns:**
java.lang.String - 续订开始消息。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLicensed_internalized() {#isLicensed-internalized--}
```
public static boolean isLicensed_internalized()
```


获取一个值，指示产品是否已授权。

**Returns:**
boolean -  true  如果产品已授权；否则，  false 。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeLicense() {#removeLicense--}
```
public static void removeLicense()
```




### setLicense(File licenseFile) {#setLicense-java.io.File-}
```
public void setLicense(File licenseFile)
```


为组件授权。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| licenseFile | java.io.File | 文件路径名的表示 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


为组件授权。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含许可证的流。 |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


为组件授权。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| licenseName | java.lang.String | 可以是完整或简短的文件名。使用空字符串切换到评估模式。 |

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

