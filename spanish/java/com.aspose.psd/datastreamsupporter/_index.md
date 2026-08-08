---
title: "DataStreamSupporter"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El contenedor del flujo de datos."
type: docs
weight: 38
url: /es/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

El contenedor del flujo de datos.
## Campos

| Campo | Descripción |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Ocurre cuando la imagen se cargó o guardó |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Ocurre cuando se utilizó el crédito |
## Métodos

| Método | Descripción |
| --- | --- |
| [cacheData()](#cacheData--) | Almacena en caché los datos y asegura que no se realizará carga adicional de datos desde el subyacente DataStreamSupporter.DataStreamContainer. |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Obtiene el flujo de datos del objeto. |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Obtiene la ruta del archivo de la imagen fuente si existe. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Obtiene un valor que indica si el objeto usa la estrategia de optimización de memoria |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos del objeto están en caché actualmente y no se requiere lectura de datos. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Guarda los datos del objeto en el actual  DataStreamSupporter . |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Guarda los datos del objeto en el flujo especificado. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Guarda los datos del objeto en el flujo especificado. |
| [save(String filePath)](#save-java.lang.String-) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Establece el flujo de datos del objeto. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Establece un valor que indica si [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Ocurre cuando la imagen se cargó o guardó

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Ocurre cuando se utilizó el crédito

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Almacena en caché los datos y asegura que no se realizará carga adicional de datos desde el subyacente DataStreamSupporter.DataStreamContainer.

### close() {#close--}
```
public void close()
```


Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. Este método simplemente llama al método dispose.

### dispose() {#dispose--}
```
public final void dispose()
```


Descarta la instancia actual.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Obtiene el flujo de datos del objeto.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Obtiene la ruta del archivo de la imagen fuente si existe. Devuelve una cadena vacía si no se puede encontrar la ruta fuente.

**Returns:**
java.lang.String - La ruta del archivo de la imagen fuente.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Obtiene un valor que indica si el objeto usa la estrategia de optimización de memoria

Valor:  true  si el objeto usa la estrategia de optimización de memoria; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si el objeto usa la estrategia de optimización de memoria
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Obtiene un valor que indica si los datos del objeto están en caché actualmente y no se requiere lectura de datos.

**Returns:**
boolean - un valor que indica si los datos del objeto están en caché actualmente y no se requiere lectura de datos.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


Guarda los datos del objeto en el actual  DataStreamSupporter .

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Guarda los datos del objeto en el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | El flujo donde guardar los datos del objeto. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Guarda los datos del objeto en el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivo | java.io.RandomAccessFile | El flujo donde guardar los datos del objeto. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del objeto. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del objeto. |
| overWrite | boolean | Si se establece en true sobrescribirá el contenido del archivo, de lo contrario se producirá una anexión. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Establece el flujo de datos del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | El flujo de datos del objeto. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Establece un valor que indica si [ignore after save].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true si [ignore after save]; de lo contrario, false. |

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

