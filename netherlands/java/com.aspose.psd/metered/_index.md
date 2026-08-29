---
title: "Gemeten"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Biedt gemeten methoden voor integratie"
type: docs
weight: 71
url: /nl/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Biedt gemeten methoden voor integratie

In dit voorbeeld wordt geprobeerd om een gemeten openbare en privésleutel in te stellen

// het component‑jar‑bestand: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey");
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Metered()](#Metered--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | Haalt verbruikskrediet op |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Haalt bestandsgrootte van verbruik op |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Stelt gemeten openbare en privésleutel in |
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


Bepaalt of het opgegeven Object gelijk is aan deze instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken met deze instantie. |

**Returns:**
boolean - true als het opgegeven Object gelijk is aan deze instantie; anders false.
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


Haalt verbruikskrediet op

**Returns:**
java.math.BigDecimal - verbruikshoeveelheid
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Haalt bestandsgrootte van verbruik op

**Returns:**
java.math.BigDecimal - bestandsgrootte van verbruik
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


Stelt gemeten openbare en privésleutel in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| publicKey | java.lang.String | publieke sleutel |
| privateKey | java.lang.String | privésleutel |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

