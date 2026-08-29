---
title: "AddNoiseSmartFilter"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le filtre intelligent AddNoise."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

Le filtre intelligent AddNoise.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | Initialise une nouvelle instance de la classe [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter). |
## Champs

| Champ | Description |
| --- | --- |
| [FilterType](#FilterType) | L'identifiant du filtre intelligent actuel. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Applique le filtre actuel à l'image d'entrée RasterImage. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Applique le filtre actuel aux données de masque d'entrée [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Effectue le clonage membre à membre de l'instance actuelle du type. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | Obtient ou définit la valeur du bruit. |
| [getBlendMode()](#getBlendMode--) | Obtient ou définit le mode de fusion. |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | Obtient ou définit la distribution du filtre de bruit. |
| [getFilterId()](#getFilterId--) | Obtient l'identifiant du type de filtre intelligent. |
| [getName()](#getName--) | Obtient le nom du filtre intelligent. |
| [getOpacity()](#getOpacity--) | Obtient ou définit la valeur d'opacité du filtre intelligent. |
| [getSourceDescriptor()](#getSourceDescriptor--) | La structure de descripteur source contenant les données du filtre intelligent. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Obtient ou définit l'état d'activation du filtre intelligent. |
| [isMonochromatic()](#isMonochromatic--) | Obtient ou définit la valeur de monochromatic. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | Obtient ou définit la valeur du bruit. |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtient ou définit le mode de fusion. |
| [setDistribution(int value)](#setDistribution-int-) | Obtient ou définit la distribution du filtre de bruit. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Obtient ou définit l'état d'activation du filtre intelligent. |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | Obtient ou définit la valeur de monochromatic. |
| [setOpacity(double value)](#setOpacity-double-) | Obtient ou définit la valeur d'opacité du filtre intelligent. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Enregistre les informations du filtre intelligent dans les données [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) et renvoie. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


Initialise une nouvelle instance de la classe [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter).

### FilterType {#FilterType}
```
public static final int FilterType
```


L'identifiant du filtre intelligent actuel.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Applique le filtre actuel à l'image d'entrée RasterImage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | L'image raster. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Applique le filtre actuel aux données de masque d'entrée [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Le calque avec les données de masque. |

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Effectue le clonage membre à membre de l'instance actuelle du type.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


Obtient ou définit la valeur du bruit.

**Returns:**
double
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Obtient ou définit le mode de fusion.

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


Obtient ou définit la distribution du filtre de bruit.

**Returns:**
int
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


Obtient l'identifiant du type de filtre intelligent.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Obtient le nom du filtre intelligent.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Obtient ou définit la valeur d'opacité du filtre intelligent.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


La structure de descripteur source contenant les données du filtre intelligent.

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


Obtient ou définit l'état d'activation du filtre intelligent.

**Returns:**
booléen
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


Obtient ou définit la valeur de monochromatic.

**Returns:**
booléen
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


Obtient ou définit la valeur du bruit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Obtient ou définit le mode de fusion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


Obtient ou définit la distribution du filtre de bruit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Obtient ou définit l'état d'activation du filtre intelligent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


Obtient ou définit la valeur de monochromatic.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Obtient ou définit la valeur d'opacité du filtre intelligent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Enregistre les informations du filtre intelligent dans les données [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) et renvoie.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

