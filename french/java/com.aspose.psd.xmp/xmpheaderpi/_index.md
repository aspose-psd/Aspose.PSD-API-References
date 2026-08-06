---
title: "XmpHeaderPi"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente l'instruction de traitement de l'en-tête XMP."
type: docs
weight: 16
url: /fr/java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Représente l'instruction de traitement de l'en-tête XMP.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Initialise une nouvelle instance de la classe XmpHeaderPi. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Initialise une nouvelle instance de la classe XmpHeaderPi. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Clone cette instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le  System.Object  spécifié , est égal à cette instance. |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | Représente le GUID d'en-tête. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur XMP en représentation XML. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | Indique si l'objet actuel est égal à un autre objet du même type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | Représente le GUID d'en-tête. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Initialise une nouvelle instance de la classe XmpHeaderPi.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Initialise une nouvelle instance de la classe XmpHeaderPi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| guid | java.lang.String | L'identifiant unique. |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


Clone cette instance.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si le  System.Object  spécifié , est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le  System.Object  à comparer avec cette instance. |

**Returns:**
booléen -  true  si le  System.Object  spécifié est égal à cette instance ; sinon,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGuid() {#getGuid--}
```
public String getGuid()
```


Représente le GUID d'en-tête.

Le texte de l'en-tête PI contient un GUID, ce qui le rend peu susceptible d'apparaître accidentellement dans le flux de données.

**Returns:**
java.lang.String
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
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Indique si l'objet actuel est égal à un autre objet du même type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Un objet à comparer avec cet objet. |

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




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Représente le GUID d'en-tête.

Le texte de l'en-tête PI contient un GUID, ce qui le rend peu susceptible d'apparaître accidentellement dans le flux de données.

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

