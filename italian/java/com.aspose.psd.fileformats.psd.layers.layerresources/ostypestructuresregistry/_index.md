---
title: "OSTypeStructuresRegistry"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta il registro delle risorse."
type: docs
weight: 65
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Inheritance:**
java.lang.Object
```
public final class OSTypeStructuresRegistry
```

Rappresenta il registro delle risorse [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OSTypeStructuresRegistry()](#OSTypeStructuresRegistry--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) | Ottiene il primo descrittore di apertura supportato. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Ottiene il primo descrittore supportato per nome tipo. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Ottiene i descrittori registrati. |
| [hashCode()](#hashCode--) |  |
| [isOSTypeStructreExist_internalized(int structureKey)](#isOSTypeStructreExist-internalized-int-) | Rileva se è presente qualche discendente di OSTypeStructure con la chiave di struttura fornita. |
| [loadDescriptorData_internalized(StreamContainer streamContainer)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-) | Carica le strutture dati del descrittore dal contenitore di flusso. |
| [loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---) | Carica le strutture dati del descrittore con nome classe e ID classe dal contenitore di flusso. |
| [loadResourceByFirstSupportedDescriptor(InputStream stream)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-) | Carica [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) utilizzando il primo apritore trovato adatto per il flusso specificato. |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerOpener(IOSTypeStructureLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Registra l'opener. |
| [toString()](#toString--) |  |
| [unregisterOpener(IOSTypeStructureLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Annulla la registrazione dell'opener. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OSTypeStructuresRegistry() {#OSTypeStructuresRegistry--}
```
public OSTypeStructuresRegistry()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFirstSupportedDescriptor(InputStream stream) {#getFirstSupportedDescriptor-java.io.InputStream-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptor(InputStream stream)
```


Ottiene il primo descrittore di apertura supportato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.InputStream | Il flusso. |

--------------------

Il primo loader sarà in realtà l'ultimo registrato. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Ottiene il primo descrittore supportato per nome tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Il nome del tipo di descrittore. |

--------------------

Il primo descrittore di apertura sarà in realtà l'ultimo registrato. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IOSTypeStructureLoader[] getRegisteredDescriptors()
```


Ottiene i descrittori registrati.

Valore: I descrittori registrati.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOSTypeStructreExist_internalized(int structureKey) {#isOSTypeStructreExist-internalized-int-}
```
public static boolean isOSTypeStructreExist_internalized(int structureKey)
```


Rileva se è presente qualche discendente di OSTypeStructure con la chiave di struttura fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| structureKey | int | StructureKey di OSTypeStructure. |

**Returns:**
boolean -
### loadDescriptorData_internalized(StreamContainer streamContainer) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer)
```


Carica le strutture dati del descrittore dal contenitore di flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il flusso da leggere. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Le strutture dati del descrittore.
### loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)
```


Carica le strutture dati del descrittore con nome classe e ID classe dal contenitore di flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il flusso da leggere. |
| className | java.lang.String[] | Il nome della classe letta. |
| classId | [ClassID\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | L'ID della classe letta. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Le strutture dati del descrittore con nome classe e ID classe.
### loadResourceByFirstSupportedDescriptor(InputStream stream) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor(InputStream stream)
```


Carica [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) utilizzando il primo apritore trovato adatto per il flusso specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.InputStream | Il flusso. |

--------------------

Il primo apritore sarà in realtà l'ultimo registrato. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerOpener(IOSTypeStructureLoader openerDescriptor) {#registerOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-}
```
public static void registerOpener(IOSTypeStructureLoader openerDescriptor)
```


Registra l'opener.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Il descrittore di apertura da registrare. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterOpener(IOSTypeStructureLoader openerDescriptor) {#unregisterOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-}
```
public static void unregisterOpener(IOSTypeStructureLoader openerDescriptor)
```


Annulla la registrazione dell'opener.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Il descrittore di apertura da deregistrare. |

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

