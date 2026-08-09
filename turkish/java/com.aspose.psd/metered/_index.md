---
title: "Metered"
second_title: "Java için Aspose.PSD API Referansı"
description: "Entegrasyon için ölçülen yöntemler sağlar"
type: docs
weight: 71
url: /tr/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Entegrasyon için ölçülen yöntemler sağlar

Bu örnekte, ölçümlü public ve private anahtar ayarlamaya çalışılacak.

// bileşen jar dosyası: Metered matered = new Metered(); matered.setMeteredKey(\"PublicKey\", \"PrivateKey\");
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Metered()](#Metered--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen Nesnenin bu örnekle eşit olup olmadığını belirler. |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | Tüketim kredisini alır |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Tüketim dosya boyutunu alır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ölçümlü public ve private anahtarı ayarlar |
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


Belirtilen Nesnenin bu örnekle eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak Object. |

**Returns:**
boolean -  true  eğer belirtilen Object bu örnek ile eşitse; aksi takdirde,  false .
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


Tüketim kredisini alır

**Returns:**
java.math.BigDecimal - tüketim miktarı
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Tüketim dosya boyutunu alır

**Returns:**
java.math.BigDecimal - tüketim dosya boyutu
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


Ölçümlü public ve private anahtarı ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| publicKey | java.lang.String | public anahtar |
| privateKey | java.lang.String | private anahtar |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

