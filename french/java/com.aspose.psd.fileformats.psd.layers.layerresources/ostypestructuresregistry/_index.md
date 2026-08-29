---
title: "OSTypeStructuresRegistry"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente le registre des ressources."
type: docs
weight: 65
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Inheritance:**
java.lang.Object
```
public final class OSTypeStructuresRegistry
```

Représente le registre des ressources [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OSTypeStructuresRegistry()](#OSTypeStructuresRegistry--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) | Obtient le premier descripteur d'ouvreurs pris en charge. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Obtient le premier descripteur pris en charge par son nom de type. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Obtient les descripteurs enregistrés. |
| [hashCode()](#hashCode--) |  |
| [isOSTypeStructreExist_internalized(int structureKey)](#isOSTypeStructreExist-internalized-int-) | Détecte si un descendant de OSTypeStructure est présent avec la structureKey fournie. |
| [loadDescriptorData_internalized(StreamContainer streamContainer)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-) | Charge les structures de données du descripteur depuis le conteneur de flux. |
| [loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---) | Charge les structures de données du descripteur avec le nom de classe et l'identifiant de classe depuis le conteneur de flux. |
| [loadResourceByFirstSupportedDescriptor(InputStream stream)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-) | Charge [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) en utilisant le premier ouvreur trouvé adapté au flux spécifié. |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerOpener(IOSTypeStructureLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Enregistre l'ouvreuse. |
| [toString()](#toString--) |  |
| [unregisterOpener(IOSTypeStructureLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Désenregistre l'ouvreuse. |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient le premier descripteur d'ouvreurs pris en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux. |

--------------------

Le premier chargeur sera en fait le dernier enregistré. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Obtient le premier descripteur pris en charge par son nom de type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Le nom du type de descripteur. |

--------------------

Le premier descripteur d'ouvreuse sera en fait le dernier enregistré. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IOSTypeStructureLoader[] getRegisteredDescriptors()
```


Obtient les descripteurs enregistrés.

Valeur: Les descripteurs enregistrés.

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


Détecte si un descendant de OSTypeStructure est présent avec la structureKey fournie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| structureKey | int | StructureKey de OSTypeStructure. |

**Returns:**
boolean -
### loadDescriptorData_internalized(StreamContainer streamContainer) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer)
```


Charge les structures de données du descripteur depuis le conteneur de flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le flux à lire. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Les structures de données du descripteur.
### loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)
```


Charge les structures de données du descripteur avec le nom de classe et l'identifiant de classe depuis le conteneur de flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le flux à lire. |
| className | java.lang.String[] | Le nom de classe lu. |
| classId | [ClassID\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | L'identifiant de classe lu. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Les structures de données du descripteur avec le nom de classe et l'identifiant de classe.
### loadResourceByFirstSupportedDescriptor(InputStream stream) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor(InputStream stream)
```


Charge [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) en utilisant le premier ouvreur trouvé adapté au flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux. |

--------------------

Le premier ouvreur sera en fait le dernier enregistré. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
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


Enregistre l'ouvreuse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Le descripteur d'ouvreuse à enregistrer. |

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


Désenregistre l'ouvreuse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Le descripteur d'ouvreuse à désenregistrer. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

