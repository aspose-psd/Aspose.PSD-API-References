---
title: "TiffDataType"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le type de données tiff."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Le type de données tiff.
## Méthodes

| Méthode | Description |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet. |
| [deepClone()](#deepClone--) | Effectue un clonage profond de cette instance. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Obtient la taille des données supplémentaires en octets (au cas où les 12 octets ne seraient pas suffisants pour contenir les données de l'étiquette). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtient le nombre d'éléments. |
| [getDataSize()](#getDataSize--) | Obtient la taille des données supplémentaires en octets (au cas où les 12 octets ne seraient pas suffisants pour contenir les données de l'étiquette). |
| [getId()](#getId--) | Obtient la représentation entière de l'identifiant de l'étiquette. |
| [getTagId()](#getTagId--) | Obtient l'identifiant de l'étiquette. |
| [getTagType()](#getTagType--) | Obtient le type de l'étiquette. |
| [getValue()](#getValue--) | Obtient la valeur que ce type de données contient. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Obtient une valeur indiquant si l'étiquette est privée. |
| [isValid()](#isValid--) | Obtient une valeur indiquant si les données de l'étiquette sont valides. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Lit les données de l'étiquette. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Définit la valeur que ce type de données contient. |
| [toString()](#toString--) | Retourne une  System.String  qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données supplémentaires de l'étiquette. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Écrit les données de l'étiquette. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Un objet à comparer avec cette instance. |

**Returns:**
int - Un entier signé de 32 bits qui indique l'ordre relatif des objets comparés. La valeur de retour a ces significations : Valeur signification Moins que zéro : cette instance est inférieure à obj. Zéro : cette instance est égale à obj. Plus que zéro : cette instance est supérieure à obj.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Effectue un clonage profond de cette instance.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
booléen
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Obtient la taille des données supplémentaires en octets (au cas où les 12 octets ne seraient pas suffisants pour contenir les données de l'étiquette).

**Returns:**
long - La taille des données supplémentaires en octets.

Il s'agit du nombre d'octets de données aligné à la frontière d'un mot.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


Obtient le nombre d'éléments.

**Returns:**
long - Le nombre d'éléments.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Obtient la taille des données supplémentaires en octets (au cas où les 12 octets ne seraient pas suffisants pour contenir les données de l'étiquette).

**Returns:**
long - La taille des données supplémentaires en octets.

Il s'agit du nombre exact d'octets.
### getId() {#getId--}
```
public int getId()
```


Obtient la représentation entière de l'identifiant de l'étiquette.

**Returns:**
int - La représentation entière de l'identifiant de l'étiquette
### getTagId() {#getTagId--}
```
public int getTagId()
```


Obtient l'identifiant de l'étiquette.

**Returns:**
int - L'identifiant de l'étiquette.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Obtient le type de l'étiquette.

**Returns:**
int - Le type de l'étiquette.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Obtient la valeur que ce type de données contient.

**Returns:**
java.lang.Object - La valeur.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


Obtient une valeur indiquant si l'étiquette est privée. Les étiquettes TIFF privées sont des étiquettes dont l'identifiant dépasse 32768.

**Returns:**
boolean -  true  si les données de l'étiquette sont valides ; sinon,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Obtient une valeur indiquant si les données de l'étiquette sont valides. L'étiquette valide contient des données qui peuvent être conservées. L'étiquette invalide ne peut pas être stockée.

**Returns:**
boolean -  true  si les données de l'étiquette sont valides ; sinon,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Lit les données de l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | Le flux de données. |
| position | long | La position de l'étiquette. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Définit la valeur que ce type de données contient.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | La valeur. |

### toString() {#toString--}
```
public String toString()
```


Retourne une  System.String  qui représente cette instance.

**Returns:**
java.lang.String - Une System.String qui représente cette instance.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Écrit les données supplémentaires de l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Le flux de données. |

**Returns:**
long - Le nombre réel d'octets écrits.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Écrit les données de l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Le flux de données. |
| additionalDataOffset | long | Le décalage où écrire les données supplémentaires. |

