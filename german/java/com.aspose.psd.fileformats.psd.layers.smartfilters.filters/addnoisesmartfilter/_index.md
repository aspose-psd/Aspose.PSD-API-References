---
title: "AddNoiseSmartFilter"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der AddNoise‑Smartfilter."
type: docs
weight: 10
url: /de/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

Der AddNoise‑Smartfilter.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | Initialisiert eine neue Instanz der [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [FilterType](#FilterType) | Der Bezeichner des aktuellen SmartFilters. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Wendet den aktuellen Filter auf das Eingabe‑RasterImage‑Bild an. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Wendet den aktuellen Filter auf die Eingabe‑[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)‑Maskendaten an. |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Erstellt die Member‑weise Kopie der aktuellen Instanz des Typs. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | Liest oder setzt den Rauschwertbetrag. |
| [getBlendMode()](#getBlendMode--) | Liest oder setzt den Mischmodus. |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | Liest oder setzt die Verteilung des Rauschfilters. |
| [getFilterId()](#getFilterId--) | Liest den Typbezeichner des SmartFilters. |
| [getName()](#getName--) | Liest den Namen des SmartFilters. |
| [getOpacity()](#getOpacity--) | Liest oder setzt den Opazitätswert des SmartFilters. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Die Quell‑Descriptor‑Struktur mit SmartFilter‑Daten. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Liest oder setzt den Aktivierungsstatus des SmartFilters. |
| [isMonochromatic()](#isMonochromatic--) | Liest oder setzt den Wert von monochromatic. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | Liest oder setzt den Rauschwertbetrag. |
| [setBlendMode(long value)](#setBlendMode-long-) | Liest oder setzt den Mischmodus. |
| [setDistribution(int value)](#setDistribution-int-) | Liest oder setzt die Verteilung des Rauschfilters. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Liest oder setzt den Aktivierungsstatus des SmartFilters. |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | Liest oder setzt den Wert von monochromatic. |
| [setOpacity(double value)](#setOpacity-double-) | Liest oder setzt den Opazitätswert des SmartFilters. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Speichert die SmartFilter‑Informationen in die [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)‑Daten und gibt sie zurück. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


Initialisiert eine neue Instanz der [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) Klasse.

### FilterType {#FilterType}
```
public static final int FilterType
```


Der Bezeichner des aktuellen SmartFilters.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Wendet den aktuellen Filter auf das Eingabe‑RasterImage‑Bild an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Das Rasterbild. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Wendet den aktuellen Filter auf die Eingabe‑[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)‑Maskendaten an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Die Ebene mit Maskendaten. |

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Erstellt die Member‑weise Kopie der aktuellen Instanz des Typs.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
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
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


Liest oder setzt den Rauschwertbetrag.

**Returns:**
double
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Liest oder setzt den Mischmodus.

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


Liest oder setzt die Verteilung des Rauschfilters.

**Returns:**
int
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


Liest den Typbezeichner des SmartFilters.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Liest den Namen des SmartFilters.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Liest oder setzt den Opazitätswert des SmartFilters.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


Die Quell‑Descriptor‑Struktur mit SmartFilter‑Daten.

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


Liest oder setzt den Aktivierungsstatus des SmartFilters.

**Returns:**
boolean
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


Liest oder setzt den Wert von monochromatic.

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


Liest oder setzt den Rauschwertbetrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Liest oder setzt den Mischmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


Liest oder setzt die Verteilung des Rauschfilters.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Liest oder setzt den Aktivierungsstatus des SmartFilters.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


Liest oder setzt den Wert von monochromatic.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Liest oder setzt den Opazitätswert des SmartFilters.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Speichert die SmartFilter‑Informationen in die [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)‑Daten und gibt sie zurück.

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

