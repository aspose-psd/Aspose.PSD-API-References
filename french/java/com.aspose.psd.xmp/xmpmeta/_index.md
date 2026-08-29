---
title: "XmpMeta"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente xmpmeta."
type: docs
weight: 17
url: /fr/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Représente xmpmeta. Optionnel. Le but de cet élément est d'identifier les métadonnées XMP dans un texte XML général qui pourrait contenir d'autres utilisations non XMP de RDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Initialise une nouvelle instance de la classe XmpMeta. |
| [XmpMeta()](#XmpMeta--) | Initialise une nouvelle instance de la classe XmpMeta. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Ajoute l'attribut. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Attribue l'élément XMP spécifié à celui actuel. |
| [clearAttributes()](#clearAttributes--) | Supprime tous les attributs. |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [equals(Object other)](#equals-java.lang.Object-) | Détermine si le  System.Object  spécifié , est égal à cette instance. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Obtient ou définit la version de la boîte à outils Adobe Xmp. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Obtient l'attribut. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur XMP en représentation XML. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Indique si l'objet actuel est égal à un autre objet du même type. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | Indique si l'objet actuel est égal à un autre objet du même type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Obtient ou définit la version de la boîte à outils Adobe Xmp. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Initialise une nouvelle instance de la classe XmpMeta.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Version de la boîte à outils Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Initialise une nouvelle instance de la classe XmpMeta.

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Ajoute l'attribut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| attribute | java.lang.String | L'attribut. |
| valeur | java.lang.String | La valeur. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Attribue l'élément XMP spécifié à celui actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | L'élément XMP. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Supprime tous les attributs.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Clone cette instance.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Détermine si le  System.Object  spécifié , est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | Le  System.Object  à comparer avec cette instance. |

**Returns:**
booléen -  true  si le  System.Object  spécifié est égal à cette instance ; sinon,  false .
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Obtient ou définit la version de la boîte à outils Adobe Xmp.

**Returns:**
java.lang.String
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Obtient l'attribut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| attribute | java.lang.String | L'attribut. |

**Returns:**
java.lang.String - Retourne l'attribut pour le nom d'attribut spécifié.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur XMP en représentation XML.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en représentation XML.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Indique si l'objet actuel est égal à un autre objet du même type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Un objet à comparer avec cet objet. |

**Returns:**
booléen - true si l'objet actuel est égal au paramètre  other ; sinon, false.
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Indique si l'objet actuel est égal à un autre objet du même type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Un objet à comparer avec cet objet. |

**Returns:**
booléen - true si l'objet actuel est égal au paramètre  other ; sinon, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Obtient ou définit la version de la boîte à outils Adobe Xmp.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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

