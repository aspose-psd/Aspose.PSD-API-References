---
title: "SmartResourceCreator"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce la classe SmartResourceCreator che può creare risorse PlLd SoLd e SoLe."
type: docs
weight: 14
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator/
---

**Inheritance:**
java.lang.Object
```
public class SmartResourceCreator
```

Definisce la classe SmartResourceCreator che può creare risorse PlLd, SoLd e SoLe. È utilizzata per supportare i livelli di oggetti intelligenti nelle immagini Adobe\ufffd Photoshop\ufffd.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SmartResourceCreator()](#SmartResourceCreator--) | Inizializza una nuova istanza della classe [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator). |
| [SmartResourceCreator(boolean isCustom, boolean hasCompInfo)](#SmartResourceCreator-boolean-boolean-) | Inizializza una nuova istanza della classe [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator). |
| [SmartResourceCreator(PlacedResource template)](#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Inizializza una nuova istanza della classe [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) con il modello fornito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generatePlacedResource()](#generatePlacedResource--) | Genera la risorsa posizionata. |
| [generateSmartEmbeddedResource()](#generateSmartEmbeddedResource--) | Genera la risorsa oggetto intelligente incorporata. |
| [generateSmartExternalResource()](#generateSmartExternalResource--) | Genera la risorsa dell'oggetto intelligente esterno. |
| [getClass()](#getClass--) |  |
| [getTemplate_internalized()](#getTemplate-internalized--) | Ottiene o imposta il modello di risorsa dell'oggetto intelligente. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartResourceCreator() {#SmartResourceCreator--}
```
public SmartResourceCreator()
```


Inizializza una nuova istanza della classe [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator).

### SmartResourceCreator(boolean isCustom, boolean hasCompInfo) {#SmartResourceCreator-boolean-boolean-}
```
public SmartResourceCreator(boolean isCustom, boolean hasCompInfo)
```


Inizializza una nuova istanza della classe [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isCustom | boolean | se impostato su  true  [è personalizzato]. |
| hasCompInfo | boolean | se impostato su  true  [ha informazioni di composizione]. |

### SmartResourceCreator(PlacedResource template) {#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public SmartResourceCreator(PlacedResource template)
```


Inizializza una nuova istanza della classe [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) con il modello fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| template | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Il modello di risorsa dell'oggetto intelligente. |

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
### generatePlacedResource() {#generatePlacedResource--}
```
public final PlLdResource generatePlacedResource()
```


Genera la risorsa posizionata.

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) - The generated [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) instance.
### generateSmartEmbeddedResource() {#generateSmartEmbeddedResource--}
```
public final SoLdResource generateSmartEmbeddedResource()
```


Genera la risorsa oggetto intelligente incorporata.

**Returns:**
[SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) - The generated [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) instance.
### generateSmartExternalResource() {#generateSmartExternalResource--}
```
public final SoLeResource generateSmartExternalResource()
```


Genera la risorsa dell'oggetto intelligente esterno.

**Returns:**
[SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) - The generated [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) instance.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getTemplate_internalized() {#getTemplate-internalized--}
```
public final SmartObjectResource getTemplate_internalized()
```


Ottiene o imposta il modello di risorsa dell'oggetto intelligente.

Valore: Il modello di risorsa dell'oggetto intelligente.

**Returns:**
[SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)
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

