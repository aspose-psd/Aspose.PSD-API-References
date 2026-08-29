---
title: "LinkDataSource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define la clase LinkDataSource que contiene información sobre un archivo enlazado o un recurso en el archivo PSD."
type: docs
weight: 12
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource/
---

**Inheritance:**
java.lang.Object
```
public abstract class LinkDataSource
```

Define la clase LinkDataSource que contiene información sobre un archivo enlazado o un recurso en el archivo PSD.
## Campos

| Campo | Descripción |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | La versión del descriptor. |
| [LatestVersion_internalized](#LatestVersion-internalized) | La última versión disponible del origen de datos vinculado |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | El valor inesperado del tipo de origen de datos vinculado |
| [ZeroChar_internalized](#ZeroChar-internalized) | El carácter cero |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | Obtiene o establece un valor que indica si el recurso PSD está bloqueado. |
| [getAssetModTime()](#getAssetModTime--) | Obtiene o establece la hora de modificación del recurso, para los recursos de Bibliotecas Adobe® Photoshop® \\u0421\\u0421. |
| [getChildDocId()](#getChildDocId--) | Obtiene o establece el identificador del documento hijo en el origen de datos liFE o liFD del recurso Lnk2 / LnkE de Adobe® Photoshop®. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Obtiene o establece el id de la clase de recurso. |
| [getClassName_internalized()](#getClassName-internalized--) | Obtiene o establece el nombre de la clase de recurso. |
| [getCompId()](#getCompId--) | Obtiene o establece el ID del comp seleccionado actualmente para el documento hijo, que será -1 si no se selecciona ninguno. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Obtiene o establece la propiedad ContentID. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Obtiene la longitud de los datos adicionales. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Obtiene la longitud de los datos de origen del enlace. |
| [getFileCreator()](#getFileCreator--) | Obtiene o establece el creador del archivo en el recurso de formato PSD LnkE / Lnk2. |
| [getFileType()](#getFileType--) | Obtiene o establece el tipo del archivo incrustado o externo que el recurso Adobe® Photoshop® Lnk2 / LnkE contiene o enlaza. |
| [getItems_internalized()](#getItems-internalized--) | Obtiene o establece la matriz OSTypeStructure que define las propiedades del recurso. |
| [getLength()](#getLength--) | Obtiene la longitud de la fuente de datos del enlace en bytes. |
| [getOriginalCompId()](#getOriginalCompId--) | Obtiene el ID original del Comp seleccionado actualmente para el documento hijo, que será -1 si no se selecciona ninguno. |
| [getOriginalFileName()](#getOriginalFileName--) | Obtiene el nombre de archivo original de la fuente de datos en el recurso de enlace global de Adobe® Photoshop®. |
| [getType()](#getType--) | Obtiene el tipo de fuente de datos de enlace global de Adobe® Photoshop® que puede ser uno de los siguientes o ninguno: el archivo enlazado incrustado liFD que corresponde al recurso PSD Lnk2Resource, el archivo enlazado externo liFE que corresponde al recurso PSD LnkeResource, el alias de archivo enlazado liFA. |
| [getUniqueId()](#getUniqueId--) | Obtiene el identificador único global de la fuente de datos en el recurso de enlace PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Obtiene o establece los datos desconocidos que aparecen antes de las propiedades Items OSTypeStructures. |
| [getVersion()](#getVersion--) | Obtiene la versión de la fuente de datos en el recurso PSD LnkE / Lnk2. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Obtiene o establece un valor que indica si esta fuente de datos de enlace tiene el descriptor de archivo abierto: CompId y OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Obtiene un valor que indica si esta fuente de datos de enlace PSD enlaza al elemento de la Biblioteca Adobe® Photoshop® \\u0421\\u0421. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Guarda los datos del bloque de la fuente de datos del enlace. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Obtiene o establece un valor que indica si el recurso PSD está bloqueado. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Obtiene o establece la hora de modificación del recurso, para los recursos de Bibliotecas Adobe® Photoshop® \\u0421\\u0421. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Obtiene o establece el identificador del documento hijo en el origen de datos liFE o liFD del recurso Lnk2 / LnkE de Adobe® Photoshop®. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtiene o establece el id de la clase de recurso. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Obtiene o establece el nombre de la clase de recurso. |
| [setCompId(int value)](#setCompId-int-) | Obtiene o establece el ID del comp seleccionado actualmente para el documento hijo, que será -1 si no se selecciona ninguno. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Obtiene o establece la propiedad ContentID. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Obtiene o establece el creador del archivo en el recurso de formato PSD LnkE / Lnk2. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Obtiene o establece un valor que indica si esta fuente de datos de enlace tiene el descriptor de archivo abierto: CompId y OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Obtiene o establece el tipo del archivo incrustado o externo que el recurso Adobe® Photoshop® Lnk2 / LnkE contiene o enlaza. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtiene o establece la matriz OSTypeStructure que define las propiedades del recurso. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Obtiene un valor que indica si esta fuente de datos de enlace PSD enlaza al elemento de la Biblioteca Adobe® Photoshop® \\u0421\\u0421. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Obtiene el ID original del Comp seleccionado actualmente para el documento hijo, que será -1 si no se selecciona ninguno. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Obtiene el nombre de archivo original de la fuente de datos en el recurso de enlace global de Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Establece el valor de la propiedad por estructura de tipo. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Obtiene el identificador único global de la fuente de datos en el recurso de enlace PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Obtiene o establece los datos desconocidos que aparecen antes de las propiedades Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


La versión del descriptor.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


La última versión disponible del origen de datos vinculado

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


El valor inesperado del tipo de origen de datos vinculado

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


El carácter cero

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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Obtiene o establece un valor que indica si el recurso PSD está bloqueado. El estado de bloqueo del recurso, para los recursos de Adobe® Photoshop® \u0421\u0421 Libraries.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Obtiene o establece la hora de modificación del recurso, para los recursos de Bibliotecas Adobe® Photoshop® \\u0421\\u0421.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Obtiene o establece el identificador del documento hijo en el origen de datos liFE o liFD del recurso Lnk2 / LnkE de Adobe® Photoshop®.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Obtiene o establece el id de la clase de recurso.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Obtiene o establece el nombre de la clase de recurso.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Obtiene o establece el ID del comp seleccionado actualmente para el documento hijo, que será -1 si no hay ninguno seleccionado. Los comps son composiciones de un diseño de página que los diseñadores pueden crear. Usando comps de capa, puedes crear, gestionar y ver múltiples versiones de un diseño en un solo archivo de Adobe® Photoshop®. Un comp de capa es una captura de un estado del panel Capas. Los comps de capa guardan tres tipos de opciones de capa pero esta propiedad obtiene el identificador de selección del Comp de capa para objetos inteligentes.  Comps de capa en objetos inteligentes

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


Obtiene o establece la propiedad ContentID. El valor de esta propiedad se lee y guarda solo cuando la Versión es >= 8.

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Obtiene la longitud de los datos adicionales.

Valor: La longitud de los datos.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Obtiene la longitud de los datos de origen del enlace.

**Returns:**
long - La longitud de los datos de origen.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Obtiene o establece el creador del archivo en el recurso de formato PSD LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Obtiene o establece el tipo del archivo incrustado o externo que el recurso Adobe® Photoshop® Lnk2 / LnkE contiene o enlaza.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Obtiene o establece la matriz OSTypeStructure que define las propiedades del recurso.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Obtiene la longitud de la fuente de datos del enlace en bytes.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Obtiene el ID original del Comp seleccionado actualmente para el documento hijo, que será -1 si no hay ninguno seleccionado. Esta propiedad obtiene el identificador de selección del Comp de capa original para objetos inteligentes.  Comps de capa en objetos inteligentes

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Obtiene el nombre de archivo original de la fuente de datos en el recurso de enlace global de Adobe® Photoshop®.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Obtiene el tipo de fuente de datos de enlace global de Adobe® Photoshop® que puede ser uno de los siguientes o ninguno: el archivo enlazado incrustado liFD que corresponde al recurso PSD Lnk2Resource, el archivo enlazado externo liFE que corresponde al recurso PSD LnkeResource, el alias de archivo enlazado liFA.

Valor: El tipo de origen de datos del enlace PSD.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Obtiene el identificador único global de la fuente de datos en el recurso de enlace PSD.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Obtiene o establece los datos desconocidos que aparecen antes de las propiedades Items OSTypeStructures.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtiene la versión de la fuente de datos en el recurso PSD LnkE / Lnk2.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Obtiene o establece un valor que indica si esta fuente de datos de enlace tiene el descriptor de archivo abierto: CompId y OriginalCompId.

Valor:  true  si esta instancia tiene descriptor de archivo abierto; de lo contrario,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


Obtiene un valor que indica si esta fuente de datos de enlace PSD enlaza al elemento de la Biblioteca Adobe® Photoshop® \\u0421\\u0421.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Guarda los datos del bloque de la fuente de datos del enlace.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Obtiene o establece un valor que indica si el recurso PSD está bloqueado. El estado de bloqueo del recurso, para los recursos de Adobe® Photoshop® \u0421\u0421 Libraries.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Obtiene o establece la hora de modificación del recurso, para los recursos de Bibliotecas Adobe® Photoshop® \\u0421\\u0421.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Obtiene o establece el identificador del documento hijo en el origen de datos liFE o liFD del recurso Lnk2 / LnkE de Adobe® Photoshop®.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Obtiene o establece el id de la clase de recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Obtiene o establece el nombre de la clase de recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Obtiene o establece el ID del comp seleccionado actualmente para el documento hijo, que será -1 si no hay ninguno seleccionado. Los comps son composiciones de un diseño de página que los diseñadores pueden crear. Usando comps de capa, puedes crear, gestionar y ver múltiples versiones de un diseño en un solo archivo de Adobe® Photoshop®. Un comp de capa es una captura de un estado del panel Capas. Los comps de capa guardan tres tipos de opciones de capa pero esta propiedad obtiene el identificador de selección del Comp de capa para objetos inteligentes.  Comps de capa en objetos inteligentes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Obtiene o establece la propiedad ContentID. El valor de esta propiedad se lee y guarda solo cuando la Versión es >= 8.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Obtiene o establece el creador del archivo en el recurso de formato PSD LnkE / Lnk2.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Obtiene o establece un valor que indica si esta fuente de datos de enlace tiene el descriptor de archivo abierto: CompId y OriginalCompId.

Valor:  true  si esta instancia tiene descriptor de archivo abierto; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Obtiene o establece el tipo del archivo incrustado o externo que el recurso Adobe® Photoshop® Lnk2 / LnkE contiene o enlaza.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Obtiene o establece la matriz OSTypeStructure que define las propiedades del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Obtiene un valor que indica si esta fuente de datos de enlace PSD enlaza al elemento de la Biblioteca Adobe® Photoshop® \\u0421\\u0421.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Obtiene el ID original del Comp seleccionado actualmente para el documento hijo, que será -1 si no hay ninguno seleccionado. Esta propiedad obtiene el identificador de selección del Comp de capa original para objetos inteligentes.  Comps de capa en objetos inteligentes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Obtiene el nombre de archivo original de la fuente de datos en el recurso de enlace global de Adobe® Photoshop®.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Establece el valor de la propiedad por estructura de tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La estructura. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Obtiene el identificador único global de la fuente de datos en el recurso de enlace PSD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Obtiene o establece los datos desconocidos que aparecen antes de las propiedades Items OSTypeStructures.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

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

