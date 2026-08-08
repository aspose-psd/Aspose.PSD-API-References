---
title: "SmartObjectProvider"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define el proveedor de objetos inteligentes que permite obtener / establecer fuentes de datos de los recursos de enlace global del archivo PSD y su contenido."
type: docs
weight: 17
url: /es/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Define el proveedor de objetos inteligentes que permite obtener / establecer fuentes de datos de los recursos de enlace global del archivo PSD y su contenido.
## Métodos

| Método | Descripción |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Convierte capas en un objeto inteligente incrustado. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Convierte capas en un objeto inteligente incrustado. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Inicializa una nueva instancia de la clase [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider). |
| [embedAllLinked()](#embedAllLinked--) | Incrusta todos los objetos inteligentes vinculados en la imagen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Obtiene el tipo del contenido de la capa de objeto inteligente. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Obtiene el contenido del archivo incrustado o vinculado. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Obtiene la fuente de datos del enlace por ID único. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Carga el contenido. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Crea una nueva capa de objeto inteligente copiando la original. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Elimina fuentes de datos de recursos incrustados y externos que no están presentes en la lista proporcionada de GUID válidos. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Reemplaza la fuente de datos en los recursos globales con el contenido proporcionado para incrustar. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Reemplaza la fuente de datos en un recurso global LinkResource con la fuente de datos recién creada a partir de un archivo externo. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Establece el contenido del archivo incrustado o externo. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Establece (reemplaza o agrega) la fuente de datos del enlace en el recurso de enlace global. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Actualiza el contenido de todos los objetos inteligentes modificados en la imagen. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Actualiza todas las capas de objetos inteligentes dentro del contenedor cuyo  UniqueId  coincide con  oldGuid . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Convierte capas en un objeto inteligente incrustado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Las capas. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Convierte capas en un objeto inteligente incrustado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layerNumbers | int[] | Los números de capa. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Inicializa una nueva instancia de la clase [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | El contenedor. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Incrusta todos los objetos inteligentes vinculados en la imagen.

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
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


Obtiene el tipo del contenido de la capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | El identificador único. |

**Returns:**
int - El tipo de contenido de la capa de objeto inteligente.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Obtiene el contenido del archivo incrustado o vinculado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | El identificador único de la fuente de datos del enlace. |

**Returns:**
byte[] - El contenido de  byte[] .
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Obtiene la fuente de datos del enlace por ID único.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | El identificador único. |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


Carga el contenido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | El identificador único. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | Las opciones de carga. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Crea una nueva capa de objeto inteligente copiando la original.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | La capa fuente. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources) {#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--}
```
public final void removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)
```


Elimina fuentes de datos de recursos incrustados y externos que no están presentes en la lista proporcionada de GUID válidos. Este método limpia fuentes de datos huérfanas comparándolas con los identificadores de fuentes de datos válidos actuales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | La lista de GUIDs de fuentes de datos válidos a conservar. Las fuentes de datos que no estén en esta lista serán eliminadas. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Reemplaza la fuente de datos en los recursos globales con el contenido proporcionado para incrustar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | El identificador único de la fuente de datos existente. |
| contents | byte[] | Los datos para una nueva fuente de datos. |

**Returns:**
com.aspose.ms.System.Guid - El identificador único de la fuente de datos incrustada creada.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Reemplaza la fuente de datos en un recurso global LinkResource con la fuente de datos recién creada a partir de un archivo externo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | El recurso colocado. |
| linkedPath | java.lang.String | La ruta absoluta al archivo enlazado. |
| isReplaceOnlyThis | boolean | Si es verdadero, no elimine la fuente de datos en los recursos globales. |

**Returns:**
com.aspose.ms.System.Guid - El GUID identificador único de la fuente de datos enlazada creada. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Establece el contenido del archivo incrustado o externo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | El identificador único de la fuente de datos del enlace. |
| data | byte[] | Los datos. |
| fileType | java.lang.String | El tipo de archivo de datos. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Establece (reemplaza o agrega) la fuente de datos del enlace en el recurso de enlace global.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | El origen de datos del enlace. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


Actualiza el contenido de todos los objetos inteligentes modificados en la imagen.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Actualiza todas las capas de objeto inteligente dentro del contenedor cuyo  UniqueId  coincide con  oldGuid . Los UniqueId de las capas coincidentes se reasignan a  newGuid  y su contenido se actualiza.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | El identificador único del origen de datos del objeto inteligente original que será reemplazado. |
| newGuid | com.aspose.ms.System.Guid | El identificador único del nuevo origen de datos del objeto inteligente que se asignará. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Los ajustes de resolución que se aplicarán al actualizar el contenido. Si  null , se usa la resolución de la imagen. |

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

