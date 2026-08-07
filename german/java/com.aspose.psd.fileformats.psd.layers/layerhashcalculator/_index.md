---
title: "LayerHashCalculator"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Hash-Rechner für PSD-Ebenen."
type: docs
weight: 20
url: /de/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

Hash‑Rechner für PSD‑Ebenen. Er kann verwendet werden, um gleiche oder unterschiedliche Ebenen in verschiedenen PSD‑Dateien zu finden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | Initialisiert eine neue Instanz der [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | Liefert den Misch‑Hash. |
| [getChannelsHash()](#getChannelsHash--) | Liefert den Kanal‑Hash. |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | Liefert den Inhalts‑Hash. |
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


Initialisiert eine neue Instanz der [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Die Ebene. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


Liefert den Misch‑Hash.

**Returns:**
int - Eindeutiger Hash für Ebenen‑Mischoptionen
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


Liefert den Kanal‑Hash.

**Returns:**
int - Hash aller Ebenen‑Kanäle
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


Liefert den Inhalts‑Hash.

**Returns:**
int - Der Hash der signifikanten Parameter von Ebenen. Dieser Hash ist für alle Ebenentypen unterschiedlich.
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

