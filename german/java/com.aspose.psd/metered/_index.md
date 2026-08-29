---
title: "Metered"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt abgerechnete Methoden für die Integration bereit."
type: docs
weight: 71
url: /de/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Stellt abgerechnete Methoden für die Integration bereit.

In diesem Beispiel wird versucht, den metered öffentlichen und privaten Schlüssel festzulegen

// die Komponenten‑Jar‑Datei: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey");
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Metered()](#Metered--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt diesem Exemplar gleich ist. |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ermittelt Verbrauchsguthaben |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ermittelt Verbrauchsdateigröße |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Setzt metered öffentlichen und privaten Schlüssel |
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


Bestimmt, ob das angegebene Objekt diesem Exemplar gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  true  wenn das angegebene Objekt dieser Instanz gleich ist; andernfalls  false .
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


Ermittelt Verbrauchsguthaben

**Returns:**
java.math.BigDecimal – Verbrauchsmenge
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ermittelt Verbrauchsdateigröße

**Returns:**
java.math.BigDecimal - Verbrauchsdateigröße
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


Setzt metered öffentlichen und privaten Schlüssel

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | java.lang.String | öffentlicher Schlüssel |
| privateKey | java.lang.String | privater Schlüssel |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

