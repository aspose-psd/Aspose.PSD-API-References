---
title: "UnknownSmartFilter"
second_title: "Aspose.PSD för Java API-referens"
description: "Klassen för att lagra okända smarta filterdata."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/unknownsmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class UnknownSmartFilter extends SmartFilter
```

Klassen för att lagra okända smarta filterdata.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Tillämpar det aktuella filtret på indata RasterImage bild. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Tillämpar det aktuella filtret på indata [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) maskdata. |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Skapar en medlemsvis klon av den aktuella instansen av typen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Hämtar eller anger blandningsläget. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | Hämtar identifieraren för smartfiltertypen. |
| [getName()](#getName--) | Hämtar smartfilternamnet. |
| [getOpacity()](#getOpacity--) | Hämtar eller anger opacitetsvärdet för smartfilter. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Källbeskrivarstrukturen med smartfilterdata. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Hämtar eller anger om smartfilter är aktiverat. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Hämtar eller anger blandningsläget. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Hämtar eller anger om smartfilter är aktiverat. |
| [setOpacity(double value)](#setOpacity-double-) | Hämtar eller anger opacitetsvärdet för smartfilter. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Sparar smartfilterinformationen till [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) data och returnerar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Tillämpar det aktuella filtret på indata RasterImage bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Rasterbilden. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Tillämpar det aktuella filtret på indata [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) maskdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagret med maskdata. |

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static UnknownSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[UnknownSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/unknownsmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Skapar en medlemsvis klon av den aktuella instansen av typen.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Hämtar eller anger blandningsläget.

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
public int getFilterId()
```


Hämtar identifieraren för smartfiltertypen.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Hämtar smartfilternamnet.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Hämtar eller anger opacitetsvärdet för smartfilter.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


Källbeskrivarstrukturen med smartfilterdata.

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


Hämtar eller anger om smartfilter är aktiverat.

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


Hämtar eller anger blandningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Hämtar eller anger om smartfilter är aktiverat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Hämtar eller anger opacitetsvärdet för smartfilter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Sparar smartfilterinformationen till [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) data och returnerar.

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

