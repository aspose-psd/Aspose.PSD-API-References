---
title: "PhotoshopPackage"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente l'espace de noms Adobe Photoshop."
type: docs
weight: 12
url: /fr/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Représente l'espace de noms Adobe Photoshop.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | Initialise une nouvelle instance de la classe  PhotoshopPackage  . |
## Champs

| Champ | Description |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | Valeur maximale d'urgence. |
| [UrgencyMin](#UrgencyMin) | Valeur minimale d'urgence. |
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
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | Définit la position des auteurs. |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | Définit l'auteur de la légende. |
| [setCategory(String category)](#setCategory-java.lang.String-) | Définit la catégorie. |
| [setCity(String city)](#setCity-java.lang.String-) | Définit la ville. |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | Définit le mode couleur. |
| [setCountry(String country)](#setCountry-java.lang.String-) | Définit le pays. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Définit la date de création. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | Définit le crédit. |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | Définit les ancêtres du document. |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | Définit le titre. |
| [setHistory(String history)](#setHistory-java.lang.String-) | Définit l'historique. |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | Définit le profil icc. |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | Définit les instructions. |
| [setSource(String source)](#setSource-java.lang.String-) | Définit la source. |
| [setState(String state)](#setState-java.lang.String-) | Définit l'état. |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | Définit les catégories supplémentaires. |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | Définit la référence de transmission. |
| [setUrgency(int urgency)](#setUrgency-int-) | Définit l'urgence. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Définit la valeur. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Définit la valeur booléenne XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Définit l'identifiant unique XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Définit la valeur de type XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Définit le  Object  avec la clé spécifiée. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


Initialise une nouvelle instance de la classe  PhotoshopPackage  .

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


Valeur maximale d'urgence.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


Valeur minimale d'urgence.

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
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


Définit la position des auteurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| authorsPosition | java.lang.String | La position des auteurs. |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


Définit l'auteur de la légende.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| captionWriter | java.lang.String | Le rédacteur de légende. |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


Définit la catégorie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| category | java.lang.String | La catégorie. |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


Définit la ville.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| city | java.lang.String | Le nom de la ville. |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


Définit le mode couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorMode | byte | Le mode couleur. |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


Définit le pays.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| country | java.lang.String | Le pays. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Définit la date de création.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createdDate | java.util.Date | La date de création. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


Définit le crédit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| crédit | java.lang.String | Le crédit. |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


Définit les ancêtres du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ancêtres | java.lang.String[] | Les ancêtres. |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


Définit le titre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| titre | java.lang.String | Le titre. |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


Définit l'historique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| historique | java.lang.String | L'historique. |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


Définit le profil icc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| iccProfile | java.lang.String | Le profil icc. |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


Définit les instructions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| instructions | java.lang.String | Les instructions. |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


Définit la source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | java.lang.String | La source. |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


Définit l'état.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| état | java.lang.String | L'état. |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


Définit les catégories supplémentaires.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| supplementalCategories | java.lang.String[] | Les catégories supplémentaires. |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


Définit la référence de transmission.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transmissionReference | java.lang.String | La référence de transmission. |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


Définit l'urgence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | urgence | int | L'urgence. |

L'urgence doit être dans la plage de 1 à 8. |

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

