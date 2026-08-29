---
title: "AddNoiseSmartFilter"
second_title: "Aspose.PSD för Java API-referens"
description: "Det smarta filtret AddNoise."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

Det smarta filtret AddNoise.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | Initialiserar en ny instans av klassen [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [FilterType](#FilterType) | Identifieraren för det aktuella smartfiltret. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Tillämpar det aktuella filtret på indata RasterImage bild. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Tillämpar det aktuella filtret på indata [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) maskdata. |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Skapar en medlemsvis klon av den aktuella instansen av typen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | Hämtar eller anger brusvärdet. |
| [getBlendMode()](#getBlendMode--) | Hämtar eller anger blandningsläget. |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | Hämtar eller anger fördelningen för brusfiltret. |
| [getFilterId()](#getFilterId--) | Hämtar identifieraren för smartfiltertypen. |
| [getName()](#getName--) | Hämtar smartfilternamnet. |
| [getOpacity()](#getOpacity--) | Hämtar eller anger opacitetsvärdet för smartfilter. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Källbeskrivarstrukturen med smartfilterdata. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Hämtar eller anger om smartfilter är aktiverat. |
| [isMonochromatic()](#isMonochromatic--) | Hämtar eller anger värdet för monochromatic. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | Hämtar eller anger brusvärdet. |
| [setBlendMode(long value)](#setBlendMode-long-) | Hämtar eller anger blandningsläget. |
| [setDistribution(int value)](#setDistribution-int-) | Hämtar eller anger fördelningen för brusfiltret. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Hämtar eller anger om smartfilter är aktiverat. |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | Hämtar eller anger värdet för monochromatic. |
| [setOpacity(double value)](#setOpacity-double-) | Hämtar eller anger opacitetsvärdet för smartfilter. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Sparar smartfilterinformationen till [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) data och returnerar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


Initialiserar en ny instans av klassen [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter).

### FilterType {#FilterType}
```
public static final int FilterType
```


Identifieraren för det aktuella smartfiltret.

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
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
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
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


Hämtar eller anger brusvärdet.

**Returns:**
double
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
### getDistribution() {#getDistribution--}
```
public final int getDistribution()
```


Hämtar eller anger fördelningen för brusfiltret.

**Returns:**
int
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
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


Hämtar eller anger värdet för monochromatic.

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




### setAmountNoise(double value) {#setAmountNoise-double-}
```
public final void setAmountNoise(double value)
```


Hämtar eller anger brusvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Hämtar eller anger blandningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


Hämtar eller anger fördelningen för brusfiltret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Hämtar eller anger om smartfilter är aktiverat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


Hämtar eller anger värdet för monochromatic.

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

