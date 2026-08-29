---
title: "GaussianBlurSmartFilter"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der GaussianBlur‑Smartfilter."
type: docs
weight: 11
url: /de/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class GaussianBlurSmartFilter extends SmartFilter
```

Der GaussianBlur‑Smartfilter.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GaussianBlurSmartFilter()](#GaussianBlurSmartFilter--) | Initialisiert eine neue Instanz der [GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [FilterType](#FilterType) | Der Bezeichner des aktuellen SmartFilters. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Wendet den aktuellen Filter auf das Eingabe‑RasterImage‑Bild an. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Wendet den aktuellen Filter auf die Eingabe‑[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)‑Maskendaten an. |
| [crate_internalized(DescriptorStructure sourceDescriptor)](#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Erstellt die Member‑weise Kopie der aktuellen Instanz des Typs. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Liest oder setzt den Mischmodus. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | Liest den Typbezeichner des SmartFilters. |
| [getName()](#getName--) | Liest den Namen des SmartFilters. |
| [getOpacity()](#getOpacity--) | Liest oder setzt den Opazitätswert des SmartFilters. |
| [getRadius()](#getRadius--) | Liest oder setzt den Radius des gaußschen SmartFilters. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Die Quell‑Descriptor‑Struktur mit SmartFilter‑Daten. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Liest oder setzt den Aktivierungsstatus des SmartFilters. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Liest oder setzt den Mischmodus. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Liest oder setzt den Aktivierungsstatus des SmartFilters. |
| [setOpacity(double value)](#setOpacity-double-) | Liest oder setzt den Opazitätswert des SmartFilters. |
| [setRadius(double value)](#setRadius-double-) | Liest oder setzt den Radius des gaußschen SmartFilters. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Speichert die SmartFilter‑Informationen in die [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)‑Daten und gibt sie zurück. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussianBlurSmartFilter() {#GaussianBlurSmartFilter--}
```
public GaussianBlurSmartFilter()
```


Initialisiert eine neue Instanz der [GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) Klasse.

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

### crate_internalized(DescriptorStructure sourceDescriptor) {#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static GaussianBlurSmartFilter crate_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter)
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
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Liest oder setzt den Radius des gaußschen SmartFilters.

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


Liest oder setzt den Mischmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Liest oder setzt den Aktivierungsstatus des SmartFilters.

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

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Liest oder setzt den Radius des gaußschen SmartFilters.

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

