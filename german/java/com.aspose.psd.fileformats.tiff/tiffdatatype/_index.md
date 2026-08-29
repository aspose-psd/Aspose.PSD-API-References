---
title: "TiffDataType"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der TIFF-Datentyp."
type: docs
weight: 10
url: /de/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Der TIFF-Datentyp.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt eine Ganzzahl zurück, die angibt, ob die aktuelle Instanz dem anderen Objekt vorausgeht, folgt oder an derselben Position in der Sortierreihenfolge liegt. |
| [deepClone()](#deepClone--) | Führt eine tiefe Kopie dieser Instanz aus. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Liefert die zusätzliche Datenmenge in Bytes (falls die 12 Bytes nicht ausreichen, um die Tag-Daten zu speichern). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Liefert die Anzahl der Elemente. |
| [getDataSize()](#getDataSize--) | Liefert die zusätzliche Datenmenge in Bytes (falls die 12 Bytes nicht ausreichen, um die Tag-Daten zu speichern). |
| [getId()](#getId--) | Liefert die ganzzahlige Darstellung der Tag-ID. |
| [getTagId()](#getTagId--) | Liefert die Tag-ID. |
| [getTagType()](#getTagType--) | Liefert den Tag-Typ. |
| [getValue()](#getValue--) | Liefert den Wert, den dieser Datentyp enthält. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Liefert einen Wert, der angibt, ob das Tag privat ist. |
| [isValid()](#isValid--) | Liefert einen Wert, der angibt, ob die Tag-Daten gültig sind. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Liest die Tag-Daten. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Setzt den Wert, den dieser Datentyp enthält. |
| [toString()](#toString--) | Gibt einen  System.String  zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schreibt die zusätzlichen Tag-Daten. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Schreibt die Tag-Daten. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt eine Ganzzahl zurück, die angibt, ob die aktuelle Instanz dem anderen Objekt vorausgeht, folgt oder an derselben Position in der Sortierreihenfolge liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Ein Objekt zum Vergleich mit dieser Instanz. |

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Integer, der die relative Reihenfolge der zu vergleichenden Objekte angibt. Der Rückgabewert hat folgende Bedeutungen: Wert Bedeutung Kleiner als Null Diese Instanz ist kleiner als obj. Null Diese Instanz ist gleich obj. Größer als Null Diese Instanz ist größer als obj.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Führt eine tiefe Kopie dieser Instanz aus.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Liefert die zusätzliche Datenmenge in Bytes (falls die 12 Bytes nicht ausreichen, um die Tag-Daten zu speichern).

**Returns:**
long - Die zusätzliche Datenmenge in Bytes.

Dies ist die Datenbyteanzahl, ausgerichtet an einer Wortgrenze.
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


Liefert die Anzahl der Elemente.

**Returns:**
long - Die Anzahl der Elemente.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Liefert die zusätzliche Datenmenge in Bytes (falls die 12 Bytes nicht ausreichen, um die Tag-Daten zu speichern).

**Returns:**
long - Die zusätzliche Datenmenge in Bytes.

Dies ist die exakte Byteanzahl.
### getId() {#getId--}
```
public int getId()
```


Liefert die ganzzahlige Darstellung der Tag-ID.

**Returns:**
int - Die ganzzahlige Darstellung der Tag-ID
### getTagId() {#getTagId--}
```
public int getTagId()
```


Liefert die Tag-ID.

**Returns:**
int - Die Tag-ID.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Liefert den Tag-Typ.

**Returns:**
int - Der Tag-Typ.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Liefert den Wert, den dieser Datentyp enthält.

**Returns:**
java.lang.Object - Der Wert.
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


Liefert einen Wert, der angibt, ob das Tag privat ist. Private TIFF-Tags sind Tags mit einer Tag-ID über 32768.

**Returns:**
boolean -  true  wenn Tag-Daten gültig sind; andernfalls,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Gibt einen Wert zurück, der angibt, ob Tag‑Daten gültig sind. Der gültige Tag enthält Daten, die erhalten bleiben können. Der ungültige Tag kann nicht gespeichert werden.

**Returns:**
boolean -  true  wenn Tag-Daten gültig sind; andernfalls,  false .
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


Liest die Tag-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | Der Datenstream. |
| position | long | Die Tag‑Position. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Setzt den Wert, den dieser Datentyp enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object | Der Wert. |

### toString() {#toString--}
```
public String toString()
```


Gibt einen  System.String  zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein  System.String  der diese Instanz darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Schreibt die zusätzlichen Tag-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Der Datenstream. |

**Returns:**
long – Die tatsächlich geschriebenen Bytes.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Schreibt die Tag-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Der Datenstream. |
| additionalDataOffset | long | Der Versatz, zu dem zusätzliche Daten geschrieben werden. |

