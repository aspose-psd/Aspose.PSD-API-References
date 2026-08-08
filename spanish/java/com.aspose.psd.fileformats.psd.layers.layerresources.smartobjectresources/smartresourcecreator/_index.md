---
title: "SmartResourceCreator"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define la clase SmartResourceCreator que puede crear recursos PlLd SoLd y SoLe."
type: docs
weight: 14
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator/
---

**Inheritance:**
java.lang.Object
```
public class SmartResourceCreator
```

Define la clase SmartResourceCreator que puede crear recursos PlLd, SoLd y SoLe. Se utiliza para soportar capas de objetos inteligentes en las imágenes Adobe\ufffd Photoshop\ufffd.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SmartResourceCreator()](#SmartResourceCreator--) | Inicializa una nueva instancia de la clase [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator). |
| [SmartResourceCreator(boolean isCustom, boolean hasCompInfo)](#SmartResourceCreator-boolean-boolean-) | Inicializa una nueva instancia de la clase [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator). |
| [SmartResourceCreator(PlacedResource template)](#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Inicializa una nueva instancia de la clase [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) con la plantilla proporcionada. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generatePlacedResource()](#generatePlacedResource--) | Genera el recurso colocado. |
| [generateSmartEmbeddedResource()](#generateSmartEmbeddedResource--) | Genera el recurso de objeto inteligente incrustado. |
| [generateSmartExternalResource()](#generateSmartExternalResource--) | Genera el recurso externo de objeto inteligente. |
| [getClass()](#getClass--) |  |
| [getTemplate_internalized()](#getTemplate-internalized--) | Obtiene o establece la plantilla de recurso de objeto inteligente. |
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


Inicializa una nueva instancia de la clase [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator).

### SmartResourceCreator(boolean isCustom, boolean hasCompInfo) {#SmartResourceCreator-boolean-boolean-}
```
public SmartResourceCreator(boolean isCustom, boolean hasCompInfo)
```


Inicializa una nueva instancia de la clase [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isCustom | boolean | si se establece a  true  [es personalizado]. |
| hasCompInfo | boolean | si se establece a  true  [tiene información de composición]. |

### SmartResourceCreator(PlacedResource template) {#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public SmartResourceCreator(PlacedResource template)
```


Inicializa una nueva instancia de la clase [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) con la plantilla proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| template | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La plantilla de recurso de objeto inteligente. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generatePlacedResource() {#generatePlacedResource--}
```
public final PlLdResource generatePlacedResource()
```


Genera el recurso colocado.

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) - The generated [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) instance.
### generateSmartEmbeddedResource() {#generateSmartEmbeddedResource--}
```
public final SoLdResource generateSmartEmbeddedResource()
```


Genera el recurso de objeto inteligente incrustado.

**Returns:**
[SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) - The generated [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) instance.
### generateSmartExternalResource() {#generateSmartExternalResource--}
```
public final SoLeResource generateSmartExternalResource()
```


Genera el recurso externo de objeto inteligente.

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


Obtiene o establece la plantilla de recurso de objeto inteligente.

Valor: La plantilla de recurso de objeto inteligente.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

