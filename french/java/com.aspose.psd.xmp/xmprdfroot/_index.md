---
title: "XmpRdfRoot"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente l'élément rdfRDF."
type: docs
weight: 21
url: /fr/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Représente l'élément rdf:RDF. Un seul paquet XMP doit être sérialisé en utilisant un seul élément XML rdf:RDF. Le contenu de l'élément rdf:RDF doit se composer de zéro ou plusieurs éléments rdf:Description.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Initialise une nouvelle instance de la classe  XmpRdfRoot . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Ajoute l'attribut. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Attribue l'élément XMP spécifié à celui actuel. |
| [clearAttributes()](#clearAttributes--) | Supprime tous les attributs. |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet spécifié  Object , est égal à cette instance. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Obtient l'attribut. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Obtient l'URI de l'espace de noms par préfixe spécifique. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur xmp en représentation xml. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Indique si l'objet actuel est égal à un autre objet du même type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Ajoute l'URI de l'espace de noms par préfixe. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Initialise une nouvelle instance de la classe  XmpRdfRoot .

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'objet spécifié  Object , est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L' Object à comparer avec cette instance. |

**Returns:**
booléen -  true  si l' Object spécifié est égal à cette instance; sinon,  false .
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
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Obtient l'URI de l'espace de noms par préfixe spécifique. Le préfixe peut commencer sans xmlns.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| préfixe | java.lang.String | Le préfixe. |

**Returns:**
java.lang.String - Retourne l'URI du schéma du paquet.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur xmp en représentation xml.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en chaîne XML.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Ajoute l'URI de l'espace de noms par préfixe. Le préfixe peut commencer sans xmlns.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| préfixe | java.lang.String | Le préfixe. |
| namespaceUri | java.lang.String | URI du schéma du package. |

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

