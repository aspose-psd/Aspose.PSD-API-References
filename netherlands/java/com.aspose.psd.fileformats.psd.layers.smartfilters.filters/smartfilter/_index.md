---
title: "SmartFilter"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De klasse om de basislogica van smart filters te verwerken."
type: docs
weight: 13
url: /nl/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, java.lang.Cloneable
```
public abstract class SmartFilter implements System.ICloneable, Cloneable
```

De klasse om de basislogica van smart filters te verwerken.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SmartFilter()](#SmartFilter--) | Initialiseert een nieuw exemplaar van de [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Past het huidige filter toe op de invoer  RasterImage  afbeelding. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Past het huidige filter toe op de invoer [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) maskergegevens. |
| [deepClone()](#deepClone--) | Maakt de lid‑voor‑lid kloon van de huidige instantie van het type. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Haalt op of stelt de mengmodus in. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | Haalt de smart filter‑type‑identifier op. |
| [getName()](#getName--) | Haalt de smart filter‑naam op. |
| [getOpacity()](#getOpacity--) | Haalt op of stelt de opaciteitswaarde van de smart filter in. |
| [getSourceDescriptor()](#getSourceDescriptor--) | De bron‑descriptorstructuur met smart filter‑gegevens. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Haalt op of stelt de is‑ingeschakeld‑status van de smart filter in. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Haalt op of stelt de mengmodus in. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Haalt op of stelt de is‑ingeschakeld‑status van de smart filter in. |
| [setOpacity(double value)](#setOpacity-double-) | Haalt op of stelt de opaciteitswaarde van de smart filter in. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Slaat de smart filter‑informatie op in de [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) gegevens en retourneert. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartFilter() {#SmartFilter--}
```
public SmartFilter()
```


Initialiseert een nieuw exemplaar van de [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) klasse.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Past het huidige filter toe op de invoer  RasterImage  afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | De rasterafbeelding. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Past het huidige filter toe op de invoer [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) maskergegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De laag met maskergegevens. |

### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Maakt de lid‑voor‑lid kloon van de huidige instantie van het type.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Haalt op of stelt de mengmodus in.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilterId() {#getFilterId--}
```
public abstract int getFilterId()
```


Haalt de smart filter‑type‑identifier op.

**Returns:**
int
### getName() {#getName--}
```
public abstract String getName()
```


Haalt de smart filter‑naam op.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Haalt op of stelt de opaciteitswaarde van de smart filter in.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


De bron‑descriptorstructuur met smart filter‑gegevens.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Haalt op of stelt de is‑ingeschakeld‑status van de smart filter in.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Haalt op of stelt de mengmodus in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Haalt op of stelt de is‑ingeschakeld‑status van de smart filter in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Haalt op of stelt de opaciteitswaarde van de smart filter in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Slaat de smart filter‑informatie op in de [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) gegevens en retourneert.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) - The [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) with saved smart filter information.
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

