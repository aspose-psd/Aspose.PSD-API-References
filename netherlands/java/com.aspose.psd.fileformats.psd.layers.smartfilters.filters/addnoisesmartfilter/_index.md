---
title: "AddNoiseSmartFilter"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De AddNoise smart filter."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

De AddNoise smart filter.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | Initialiseert een nieuw exemplaar van de [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [FilterType](#FilterType) | De identifier van de huidige smart filter. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Past het huidige filter toe op de invoer  RasterImage  afbeelding. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Past het huidige filter toe op de invoer [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) maskergegevens. |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Maakt de lid‑voor‑lid kloon van de huidige instantie van het type. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | Haalt op of stelt de hoeveelheid ruiswaarde in. |
| [getBlendMode()](#getBlendMode--) | Haalt op of stelt de mengmodus in. |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | Haalt op of stelt de distributie van de ruisfilter in. |
| [getFilterId()](#getFilterId--) | Haalt de smart filter‑type‑identifier op. |
| [getName()](#getName--) | Haalt de smart filter‑naam op. |
| [getOpacity()](#getOpacity--) | Haalt op of stelt de opaciteitswaarde van de smart filter in. |
| [getSourceDescriptor()](#getSourceDescriptor--) | De bron‑descriptorstructuur met smart filter‑gegevens. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Haalt op of stelt de is‑ingeschakeld‑status van de smart filter in. |
| [isMonochromatic()](#isMonochromatic--) | Haalt op of stelt de waarde van monochromatisch in. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | Haalt op of stelt de hoeveelheid ruiswaarde in. |
| [setBlendMode(long value)](#setBlendMode-long-) | Haalt op of stelt de mengmodus in. |
| [setDistribution(int value)](#setDistribution-int-) | Haalt op of stelt de distributie van de ruisfilter in. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Haalt op of stelt de is‑ingeschakeld‑status van de smart filter in. |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | Haalt op of stelt de waarde van monochromatisch in. |
| [setOpacity(double value)](#setOpacity-double-) | Haalt op of stelt de opaciteitswaarde van de smart filter in. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Slaat de smart filter‑informatie op in de [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) gegevens en retourneert. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


Initialiseert een nieuw exemplaar van de [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) klasse.

### FilterType {#FilterType}
```
public static final int FilterType
```


De identifier van de huidige smart filter.

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

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
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
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


Haalt op of stelt de hoeveelheid ruiswaarde in.

**Returns:**
double
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
### getDistribution() {#getDistribution--}
```
public final int getDistribution()
```


Haalt op of stelt de distributie van de ruisfilter in.

**Returns:**
int
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


Haalt de smart filter‑type‑identifier op.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
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
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


Haalt op of stelt de waarde van monochromatisch in.

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


Haalt op of stelt de hoeveelheid ruiswaarde in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Haalt op of stelt de mengmodus in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


Haalt op of stelt de distributie van de ruisfilter in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Haalt op of stelt de is‑ingeschakeld‑status van de smart filter in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


Haalt op of stelt de waarde van monochromatisch in.

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

