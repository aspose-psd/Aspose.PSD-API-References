---
title: "LayerHashCalculator"
second_title: "Aspose.PSD för Java API-referens"
description: "Hashkalkylator för PSD-lager."
type: docs
weight: 20
url: /sv/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

Hash‑kalkylator för PSD‑lager. Den kan användas för att hitta lika eller olika lager i olika PSD‑filer.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | Initierar en ny instans av klassen [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | Hämtar blandnings‑hashen. |
| [getChannelsHash()](#getChannelsHash--) | Hämtar kanalers hash. |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | Hämtar innehållshashen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerHashCalculator(Layer layer) {#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public LayerHashCalculator(Layer layer)
```


Initierar en ny instans av klassen [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagret. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


Hämtar blandnings‑hashen.

**Returns:**
int - Unik hash för Layer Blending Options
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


Hämtar kanalers hash.

**Returns:**
int - Hash för alla lagerkanaler
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentHash() {#getContentHash--}
```
public final int getContentHash()
```


Hämtar innehållshashen.

**Returns:**
int - Hashen för de betydande parametrarna för lager. Denna hash är olika för alla typer av lager.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

