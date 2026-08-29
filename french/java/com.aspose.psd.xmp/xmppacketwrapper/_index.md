---
title: "XmpPacketWrapper"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Contient le package xmp sérialisé incluant l'en-tête et le pied de page."
type: docs
weight: 20
url: /fr/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Contient le package xmp sérialisé incluant l'en-tête et le pied de page.

Un wrapper composé d'une paire d'instructions de traitement XML (PI) peut être placé autour de l'élément rdf:RDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Initialise une nouvelle instance de la classe XmpPacketWrapper. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initialise une nouvelle instance de la classe XmpPacketWrapper. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Ajoute le package. |
| [clearPackages()](#clearPackages--) | Supprime tous les XmpPackage dans XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Détermine si le package existe dans le wrapper XMP. |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Obtient l'instruction de traitement de l'en-tête. |
| [getMeta()](#getMeta--) | Obtient les métadonnées XMP. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Obtient le package par l'URI de l'espace de noms. |
| [getPackages()](#getPackages--) | Obtient le tableau de XmpPackage dans XMP. |
| [getPackagesCount()](#getPackagesCount--) | Obtient le nombre de packages dans la structure XMP. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Obtient l'élément RDF racine. |
| [getTrailerPi()](#getTrailerPi--) | Obtient l'instruction de traitement du trailer. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Convertit la valeur XMP en représentation XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Supprime le package XMP. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Définit l'instruction de traitement de l'en-tête. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Définit les métadonnées XMP. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Définit l'élément RDF racine. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Définit l'instruction de traitement du trailer. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Initialise une nouvelle instance de la classe XmpPacketWrapper.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | L'en-tête XMP de l'instruction de traitement. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Le trailer XMP de l'instruction de traitement. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Les métadonnées XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initialise une nouvelle instance de la classe XmpPacketWrapper.

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Ajoute le package.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Le package. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Supprime tous les XmpPackage dans XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Détermine si le package existe dans le wrapper XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI du schéma du package. |

**Returns:**
boolean - Retourne true si le package avec l'URI d'espace de noms spécifié existe dans l'enveloppe XMP.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Clone cette instance.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Obtient l'instruction de traitement de l'en-tête.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Obtient les métadonnées XMP. Facultatif.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Obtient le package par l'URI de l'espace de noms.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | L'URI du schéma du package. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Obtient le tableau de XmpPackage dans XMP.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - Le tableau de XmpPackage à l'intérieur de XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Obtient le nombre de packages dans la structure XMP.

**Returns:**
int - Le nombre de packages dans la structure XMP.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Obtient l'élément RDF racine.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Obtient l'instruction de traitement du trailer.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Convertit la valeur XMP en représentation XML.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en XML.
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Supprime le package XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Le package. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Définit l'instruction de traitement de l'en-tête.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | L'instruction de traitement Header. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Définit les métadonnées XMP. Facultatif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Les métadonnées XMP. Facultatif. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Définit l'élément RDF racine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | L'élément racine RDF. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Définit l'instruction de traitement du trailer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Instruction de traitement Trailer. |

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

