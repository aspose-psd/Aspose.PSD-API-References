---
title: "OSTypeStructuresRegistry"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar resursernas register."
type: docs
weight: 65
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Inheritance:**
java.lang.Object
```
public final class OSTypeStructuresRegistry
```

Representerar [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resursernas register.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OSTypeStructuresRegistry()](#OSTypeStructuresRegistry--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) | Hämtar den första stödda öppnarebeskrivningen. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Hämtar den första stödda beskrivningen efter dess typnamn. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Hämtar de registrerade beskrivningarna. |
| [hashCode()](#hashCode--) |  |
| [isOSTypeStructreExist_internalized(int structureKey)](#isOSTypeStructreExist-internalized-int-) | Detekterar om någon av OSTypeStructure:s ättlingar är närvarande med angivet structureKey. |
| [loadDescriptorData_internalized(StreamContainer streamContainer)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-) | Laddar beskrivardatastrukturer från strömbehållaren. |
| [loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---) | Laddar beskrivardatastrukturer med klassnamn och klass-ID från strömbehållaren. |
| [loadResourceByFirstSupportedDescriptor(InputStream stream)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-) | Laddar [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) med den först hittade öppnaren som är lämplig för den specificerade strömmen. |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerOpener(IOSTypeStructureLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Registrerar öppnaren. |
| [toString()](#toString--) |  |
| [unregisterOpener(IOSTypeStructureLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Avregistrerar öppnaren. |
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
| Parameter | Typ | Beskrivning |
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


Hämtar den första stödda öppnarebeskrivningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Strömmen. |

--------------------

Den första laddaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Hämtar den första stödda beskrivningen efter dess typnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Deskriptortypens namn. |

--------------------

Den första öppnardeskriptorn kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IOSTypeStructureLoader[] getRegisteredDescriptors()
```


Hämtar de registrerade beskrivningarna.

Värde: De registrerade deskriptörerna.

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


Detekterar om någon av OSTypeStructure:s ättlingar är närvarande med angivet structureKey.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| structureKey | int | StructureKey för OSTypeStructure. |

**Returns:**
boolean -
### loadDescriptorData_internalized(StreamContainer streamContainer) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer)
```


Laddar beskrivardatastrukturer från strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömmen att läsa från. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Beskrivardatastrukturerna.
### loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)
```


Laddar beskrivardatastrukturer med klassnamn och klass-ID från strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömmen att läsa från. |
| className | java.lang.String[] | Det lästa klassnamnet. |
| classId | [ClassID\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Det lästa klass‑ID:t. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Beskrivardatastrukturerna med klassnamn och klass‑ID.
### loadResourceByFirstSupportedDescriptor(InputStream stream) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor(InputStream stream)
```


Laddar [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) med den först hittade öppnaren som är lämplig för den specificerade strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Strömmen. |

--------------------

Den första öppnaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Registrerar öppnaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Öppnardeskriptorn att registrera. |

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


Avregistrerar öppnaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Öppnardeskriptorn att avregistrera. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

