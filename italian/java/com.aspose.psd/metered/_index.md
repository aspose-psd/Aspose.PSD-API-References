---
title: "Tariffato"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Fornisce metodi a consumo per l'integrazione"
type: docs
weight: 71
url: /it/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Fornisce metodi a consumo per l'integrazione

In questo esempio, verrà tentato di impostare la chiave pubblica e privata tariffata

// il file jar del componente: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey");
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Metered()](#Metered--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'Object specificato è uguale a questa istanza. |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ottiene il credito di consumo |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ottiene la dimensione del file di consumo |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Imposta la chiave pubblica e privata tariffata |
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


Determina se l'Object specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare con questa istanza. |

**Returns:**
boolean -  true  se l'oggetto specificato è uguale a questa istanza; altrimenti,  false .
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


Ottiene il credito di consumo

**Returns:**
java.math.BigDecimal - quantità di consumo
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ottiene la dimensione del file di consumo

**Returns:**
java.math.BigDecimal - dimensione del file di consumo
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


Imposta la chiave pubblica e privata tariffata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| publicKey | java.lang.String | chiave pubblica |
| privateKey | java.lang.String | chiave privata |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

