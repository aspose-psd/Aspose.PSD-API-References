---
title: "SmartFilter"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe per elaborare la logica di base dei filtri intelligenti."
type: docs
weight: 13
url: /it/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, java.lang.Cloneable
```
public abstract class SmartFilter implements System.ICloneable, Cloneable
```

La classe per elaborare la logica di base dei filtri intelligenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SmartFilter()](#SmartFilter--) | Inizializza una nuova istanza della classe [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Applica il filtro corrente all'immagine RasterImage di input. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Applica il filtro corrente ai dati maschera del [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) di input. |
| [deepClone()](#deepClone--) | Crea il clone membro per membro dell'istanza corrente del tipo. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Ottiene o imposta la modalità di fusione. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | Ottiene l'identificatore del tipo di smart filter. |
| [getName()](#getName--) | Ottiene il nome del smart filter. |
| [getOpacity()](#getOpacity--) | Ottiene o imposta il valore di opacità del smart filter. |
| [getSourceDescriptor()](#getSourceDescriptor--) | La struttura descrittore sorgente con i dati del smart filter. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Ottiene o imposta lo stato abilitato del smart filter. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Ottiene o imposta la modalità di fusione. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Ottiene o imposta lo stato abilitato del smart filter. |
| [setOpacity(double value)](#setOpacity-double-) | Ottiene o imposta il valore di opacità del smart filter. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Salva le informazioni del smart filter in dati [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) e restituisce. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartFilter() {#SmartFilter--}
```
public SmartFilter()
```


Inizializza una nuova istanza della classe [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter).

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
### getFilterId() {#getFilterId--}
```
public abstract int getFilterId()
```


Ottiene l'identificatore del tipo di smart filter.

**Returns:**
int
### getName() {#getName--}
```
public abstract String getName()
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


Ottiene o imposta la modalità di fusione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Ottiene o imposta lo stato abilitato del smart filter.

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

