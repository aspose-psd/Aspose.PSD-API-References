---
title: Metered
second_title: Aspose.PSD for Java API Reference
description: Provides metered methods for integration
type: docs
weight: 71
url: /java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides metered methods for integration

In this example, an attempt will be made to set metered public and private key

 // the component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); 
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Fields

| Field | Description |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object, is equal to this instance. |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | Gets consumption credit |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Gets consumption file size |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Sets metered public and private key |
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


Determines whether the specified Object, is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with this instance. |

**Returns:**
boolean -  true  if the specified Object is equal to this instance; otherwise,  false .
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


Gets consumption credit

**Returns:**
java.math.BigDecimal - consumption quantity
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Gets consumption file size

**Returns:**
java.math.BigDecimal - consumption file size
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


Sets metered public and private key

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | public key |
| privateKey | java.lang.String | private key |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

