---
title: "XmpBasicPackage"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente l'espace de noms de base XMP."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Représente l'espace de noms de base XMP.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Initialise une nouvelle instance de la classe  XmpBasicPackage  . |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe  XmpBasicPackage  . |
## Champs

| Champ | Description |
| --- | --- |
| [RatingMax](#RatingMax) | Valeur maximale de la note. |
| [RatingMin](#RatingMin) | Valeur minimale de la note. |
| [RatingRejected](#RatingRejected) | Valeur rejetée de la note. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Obtient ou définit l'Object avec la clé spécifiée. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Supprime la valeur avec la clé spécifiée. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Ajoute la date de création de la ressource. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | Ajoute la date de création de la ressource. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Définit l'outil du créateur. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | Définit l'identifiant. |
| [setLabel(String label)](#setLabel-java.lang.String-) | Définit l'étiquette. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Ajoute la date de dernière modification des métadonnées. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | Ajoute la date de dernière modification des métadonnées. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Ajoute la date de dernière modification de la ressource. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | Ajoute la date de dernière modification de la ressource. |
| [setRating(int choise)](#setRating-int-) | Définit la note. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Définit la valeur. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Définit la valeur booléenne XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Définit l'identifiant unique XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Définit la valeur de type XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Obtient ou définit l'Object avec la clé spécifiée. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Initialise une nouvelle instance de la classe  XmpBasicPackage  .

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Initialise une nouvelle instance de la classe  XmpBasicPackage  .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| préfixe | java.lang.String | Le préfixe. |
| namespaceUri | java.lang.String | L'URI de l'espace de noms. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


Valeur maximale de la note.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


Valeur minimale de la note.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


Valeur rejetée de la note.

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


Obtient ou définit l'Object avec la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé qui identifie la valeur. Valeur : L'Object. |

**Returns:**
java.lang.Object - Retourne l'Object avec la clé spécifiée.
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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Ajoute la date de création de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createdDate | java.lang.String | Date de création. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


Ajoute la date de création de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | Date de création. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Définit l'outil du créateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| creatorTool | java.lang.String | Nom de l'outil. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


Définit l'identifiant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idenfifier | java.lang.String[] | L'idenfifier. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Définit l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| label | java.lang.String | L'étiquette. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Ajoute la date de dernière modification des métadonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| metadataDate | java.lang.String | Date des métadonnées. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


Ajoute la date de dernière modification des métadonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | Date des métadonnées. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Ajoute la date de dernière modification de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| modifiedDate | java.lang.String | Date de dernière modification. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


Ajoute la date de dernière modification de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | Date de dernière modification. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


Définit la note.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| choix | int | De -1 à 5 |

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


Obtient ou définit l'Object avec la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé qui identifie la valeur. Valeur : L'Object. |
| valeur | java.lang.Object |  |

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

