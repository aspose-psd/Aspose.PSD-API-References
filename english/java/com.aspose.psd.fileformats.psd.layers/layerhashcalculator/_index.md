---
title: LayerHashCalculator
second_title: Aspose.PSD for Java API Reference
description: Hash Calculator for PSD Layers.
type: docs
weight: 18
url: /java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files
## Constructors

| Constructor | Description |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | Initializes a new instance of the [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | Gets the blending hash. |
| [getChannelsHash()](#getChannelsHash--) | Gets the channels hash. |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | Gets the content hash. |
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


Initializes a new instance of the [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The layer. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


Gets the blending hash.

**Returns:**
int - Unique hash for Layer Blending Options
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


Gets the channels hash.

**Returns:**
int - Hash of all layer channels
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


Gets the content hash.

**Returns:**
int - The hash of the significant parameters of layers. This hash is different for all types of layers
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

