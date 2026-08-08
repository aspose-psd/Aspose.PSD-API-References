---
title: "LayerResourcesRegistry"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa el registro de recursos de capa."
type: docs
weight: 26
url: /es/java/com.aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Inheritance:**
java.lang.Object
```
public final class LayerResourcesRegistry
```

Representa el registro de recursos de capa.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LayerResourcesRegistry()](#LayerResourcesRegistry--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, int psdVersion)](#getFirstSupportedDescriptor-java.io.InputStream-int-) | Obtiene el primer descriptor de apertura compatible. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Obtiene el primer descriptor compatible por su nombre de tipo. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Obtiene los descriptores registrados. |
| [hashCode()](#hashCode--) |  |
| [loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-) | Carga [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) usando el primer abridor encontrado adecuado para el flujo especificado. |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerDefaultPsdOptions_internalized()](#registerDefaultPsdOptions-internalized--) | Registra las opciones PSD predeterminadas. |
| [registerOpener(ILayerResourceLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | Registra el abridor. |
| [registerPsdLoadOptions_internalized(PsdLoadOptions load)](#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-) | Registra las opciones de carga PSD. |
| [toString()](#toString--) |  |
| [unregisterOpener(ILayerResourceLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | Anula el registro del abridor. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerResourcesRegistry() {#LayerResourcesRegistry--}
```
public LayerResourcesRegistry()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFirstSupportedDescriptor(InputStream stream, int psdVersion) {#getFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


Obtiene el primer descriptor de apertura compatible.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo. |
|  | psdVersion | int | La versión PSD. |

--------------------

El primer cargador será en realidad el último registrado. |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static ILayerResourceLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Obtiene el primer descriptor compatible por su nombre de tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | El nombre del tipo de descriptor. |

--------------------

El primer descriptor de apertura será en realidad el último registrado. |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static ILayerResourceLoader[] getRegisteredDescriptors()
```


Obtiene los descriptores registrados.

Valor: Los descriptores registrados.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


Carga [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) usando el primer abridor encontrado adecuado para el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo. |
|  | psdVersion | int | La versión PSD. |

--------------------

El primer abridor será en realidad el último registrado. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerDefaultPsdOptions_internalized() {#registerDefaultPsdOptions-internalized--}
```
public static void registerDefaultPsdOptions_internalized()
```


Registra las opciones PSD predeterminadas.

### registerOpener(ILayerResourceLoader openerDescriptor) {#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void registerOpener(ILayerResourceLoader openerDescriptor)
```


Registra el abridor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | El descriptor de apertura para registrar. |

### registerPsdLoadOptions_internalized(PsdLoadOptions load) {#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-}
```
public static void registerPsdLoadOptions_internalized(PsdLoadOptions load)
```


Registra las opciones de carga PSD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| load | [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) | La carga. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterOpener(ILayerResourceLoader openerDescriptor) {#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void unregisterOpener(ILayerResourceLoader openerDescriptor)
```


Anula el registro del abridor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | El descriptor de apertura para anular el registro. |

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

