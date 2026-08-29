---
title: "DublinCorePackage"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente le schéma Dublin Core."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.xmp.schemas.dublincore/dublincorepackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class DublinCorePackage extends XmpPackage
```

Représente le schéma Dublin Core.

Pour plus d'informations, voir : http://dublincore.org/documents/usageguide/elements.shtml.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DublinCorePackage()](#DublinCorePackage--) | Initialise une nouvelle instance de la classe  DublinCorePackage . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Ajoute l'espace de noms du type complexe. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Ajoute la propriété chaîne. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Attribue le package XMP spécifié à celui actuel. |
| [clear()](#clear--) | Efface cette instance. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Combine le package. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Détermine si la clé spécifiée contient la clé. |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Obtient les clés du package XMP. |
| [getNamespaceUri()](#getNamespaceUri--) | Obtient l'URI de l'espace de noms. |
| [getPrefix()](#getPrefix--) | Obtient le préfixe. |
| [getXmlNamespace()](#getXmlNamespace--) | Obtient l'espace de noms XML. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur XMP en représentation XML. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Obtient ou définit l'  Object  avec la clé spécifiée. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Supprime la valeur avec la clé spécifiée. |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Ajoute l'auteur. |
| [setAuthor(String[] author)](#setAuthor-java.lang.String---) | Ajoute l'auteur. |
| [setDescription(LangAlt desc)](#setDescription-com.aspose.psd.xmp.LangAlt-) | Ajoute la description. |
| [setDescription(String desc)](#setDescription-java.lang.String-) | Ajoute la description. |
| [setPublisher(String publisher)](#setPublisher-java.lang.String-) | Ajoute l'éditeur. |
| [setPublisher(String[] publisher)](#setPublisher-java.lang.String---) | Ajoute l'éditeur. |
| [setSubject(String subject)](#setSubject-java.lang.String-) | Ajoute le sujet. |
| [setSubject(String[] subject)](#setSubject-java.lang.String---) | Ajoute le sujet. |
| [setTitle(LangAlt title)](#setTitle-com.aspose.psd.xmp.LangAlt-) | Ajoute le titre Dublin Core pour différentes langues. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Ajoute le titre Dublin Core. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Définit la valeur. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Définit la valeur booléenne XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Définit l'identifiant unique XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Définit la valeur de type XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Définit le  Object  avec la clé spécifiée. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DublinCorePackage() {#DublinCorePackage--}
```
public DublinCorePackage()
```


Initialise une nouvelle instance de la classe  DublinCorePackage .

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Ajoute l'espace de noms du type complexe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typePrefix | java.lang.String | Le préfixe de type. |
| typeNamespaceUri | java.lang.String | L'URI de l'espace de noms de type. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Ajoute la propriété chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| valeur | java.lang.String | La valeur de chaîne. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Attribue le package XMP spécifié à celui actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Le package XMP. |

### clear() {#clear--}
```
public void clear()
```


Efface cette instance.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Combine le package.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | L'autre package à combiner. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Détermine si la clé spécifiée contient la clé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé à vérifier. |

**Returns:**
boolean - Renvoie vrai si la clé spécifiée contient la clé.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Clone cette instance.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
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
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Obtient les clés du package XMP.

Valeur: Les clés dans le package XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Obtient l'URI de l'espace de noms.

Valeur: L'URI de l'espace de noms.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtient le préfixe.

Valeur: Le préfixe.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Obtient l'espace de noms XML.

Valeur: L'espace de noms XML.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur XMP en représentation XML.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en représentation XML.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Obtient ou définit l'  Object  avec la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé qui identifie la valeur. |

**Returns:**
java.lang.Object - Retourne l'  Object  avec la clé spécifiée.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Un  T:System.Collections.Generic.IEnumerator1  qui peut être utilisé pour parcourir la collection.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Supprime la valeur avec la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur supprimée. |

**Returns:**
boolean - Retourne vrai si la valeur avec la clé spécifiée a été supprimée.
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Ajoute l'auteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| auteur | java.lang.String | L'auteur. |

### setAuthor(String[] author) {#setAuthor-java.lang.String---}
```
public void setAuthor(String[] author)
```


Ajoute l'auteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| auteur | java.lang.String[] | L'auteur. |

### setDescription(LangAlt desc) {#setDescription-com.aspose.psd.xmp.LangAlt-}
```
public void setDescription(LangAlt desc)
```


Ajoute la description.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| desc | [LangAlt](../../com.aspose.psd.xmp/langalt) | La description. |

### setDescription(String desc) {#setDescription-java.lang.String-}
```
public void setDescription(String desc)
```


Ajoute la description.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| desc | java.lang.String | La description. |

### setPublisher(String publisher) {#setPublisher-java.lang.String-}
```
public void setPublisher(String publisher)
```


Ajoute l'éditeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| éditeur | java.lang.String | L'éditeur. |

### setPublisher(String[] publisher) {#setPublisher-java.lang.String---}
```
public void setPublisher(String[] publisher)
```


Ajoute l'éditeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| éditeur | java.lang.String[] | L'éditeur. |

### setSubject(String subject) {#setSubject-java.lang.String-}
```
public void setSubject(String subject)
```


Ajoute le sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sujet | java.lang.String | Le sujet. |

### setSubject(String[] subject) {#setSubject-java.lang.String---}
```
public void setSubject(String[] subject)
```


Ajoute le sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sujet | java.lang.String[] | Le sujet. |

### setTitle(LangAlt title) {#setTitle-com.aspose.psd.xmp.LangAlt-}
```
public void setTitle(LangAlt title)
```


Ajoute le titre Dublin Core pour différentes langues.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| title | [LangAlt](../../com.aspose.psd.xmp/langalt) | Instance de  LangAlt . |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Ajoute le titre Dublin Core.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| titre | java.lang.String | Le titre. |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Définit la valeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | La valeur à ajouter à. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


Définit la valeur booléenne XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| boolValue | java.lang.String | La valeur booléenne. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


Définit l'identifiant unique XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur GUID définie. |
| guid | java.lang.String | L'identifiant unique. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Définit la valeur de type XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | La valeur à définir. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Définit le  Object  avec la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé qui identifie la valeur. |
| valeur | java.lang.Object | La valeur de l'Object. |

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

