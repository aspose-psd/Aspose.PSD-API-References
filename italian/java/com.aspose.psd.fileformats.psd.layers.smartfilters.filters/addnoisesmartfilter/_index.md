---
title: "AddNoiseSmartFilter"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il filtro intelligente AddNoise."
type: docs
weight: 10
url: /it/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

Il filtro intelligente AddNoise.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | Inizializza una nuova istanza della classe [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [FilterType](#FilterType) | L'identificatore del filtro intelligente corrente. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Applica il filtro corrente all'immagine RasterImage di input. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Applica il filtro corrente ai dati maschera del [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) di input. |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Crea il clone membro per membro dell'istanza corrente del tipo. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | Ottiene o imposta la quantità del valore del rumore. |
| [getBlendMode()](#getBlendMode--) | Ottiene o imposta la modalità di fusione. |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | Ottiene o imposta la distribuzione del filtro di rumore. |
| [getFilterId()](#getFilterId--) | Ottiene l'identificatore del tipo di smart filter. |
| [getName()](#getName--) | Ottiene il nome del smart filter. |
| [getOpacity()](#getOpacity--) | Ottiene o imposta il valore di opacità del smart filter. |
| [getSourceDescriptor()](#getSourceDescriptor--) | La struttura descrittore sorgente con i dati del smart filter. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Ottiene o imposta lo stato abilitato del smart filter. |
| [isMonochromatic()](#isMonochromatic--) | Ottiene o imposta il valore del monocromatico. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | Ottiene o imposta la quantità del valore del rumore. |
| [setBlendMode(long value)](#setBlendMode-long-) | Ottiene o imposta la modalità di fusione. |
| [setDistribution(int value)](#setDistribution-int-) | Ottiene o imposta la distribuzione del filtro di rumore. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Ottiene o imposta lo stato abilitato del smart filter. |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | Ottiene o imposta il valore del monocromatico. |
| [setOpacity(double value)](#setOpacity-double-) | Ottiene o imposta il valore di opacità del smart filter. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Salva le informazioni del smart filter in dati [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) e restituisce. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


Inizializza una nuova istanza della classe [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter).

### FilterType {#FilterType}
```
public static final int FilterType
```


L'identificatore del filtro intelligente corrente.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Applica il filtro corrente all'immagine RasterImage di input.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | L'immagine raster. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Applica il filtro corrente ai dati maschera del [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) di input.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Il layer con dati maschera. |

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Crea il clone membro per membro dell'istanza corrente del tipo.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


Ottiene o imposta la quantità del valore del rumore.

**Returns:**
double
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Ottiene o imposta la modalità di fusione.

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


Ottiene o imposta la distribuzione del filtro di rumore.

**Returns:**
int
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


Ottiene l'identificatore del tipo di smart filter.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome del smart filter.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Ottiene o imposta il valore di opacità del smart filter.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


La struttura descrittore sorgente con i dati del smart filter.

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


Ottiene o imposta lo stato abilitato del smart filter.

**Returns:**
boolean
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


Ottiene o imposta il valore del monocromatico.

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


Ottiene o imposta la quantità del valore del rumore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Ottiene o imposta la modalità di fusione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


Ottiene o imposta la distribuzione del filtro di rumore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Ottiene o imposta lo stato abilitato del smart filter.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


Ottiene o imposta il valore del monocromatico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Ottiene o imposta il valore di opacità del smart filter.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Salva le informazioni del smart filter in dati [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) e restituisce.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

