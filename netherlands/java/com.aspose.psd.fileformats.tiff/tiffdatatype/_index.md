---
title: "TiffDataType"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Het TIFF-datatype."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Het TIFF-datatype.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Vergelijkt de huidige instantie met een ander object van hetzelfde type en retourneert een integer die aangeeft of de huidige instantie voorafgaat, volgt of zich op dezelfde positie in de sorteervolgorde bevindt als het andere object. |
| [deepClone()](#deepClone--) | Maakt een diepe kloon van deze instantie. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Haalt de extra gegevensgrootte op in bytes (voor het geval de 12 bytes niet voldoende zijn om de taggegevens te bevatten). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Haalt het aantal elementen op. |
| [getDataSize()](#getDataSize--) | Haalt de extra gegevensgrootte op in bytes (voor het geval de 12 bytes niet voldoende zijn om de taggegevens te bevatten). |
| [getId()](#getId--) | Haalt de integerrepresentatie van de tag-id op. |
| [getTagId()](#getTagId--) | Haalt de tag-id op. |
| [getTagType()](#getTagType--) | Haalt het tagtype op. |
| [getValue()](#getValue--) | Haalt de waarde op die dit gegevenstype bevat. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Haalt een waarde op die aangeeft of de tag privé is. |
| [isValid()](#isValid--) | Haalt een waarde op die aangeeft of de taggegevens geldig zijn. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Leest de taggegevens. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Stelt de waarde in die dit gegevenstype bevat. |
| [toString()](#toString--) | Retourneert een  System.String  die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Schrijft de extra taggegevens. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Schrijft de taggegevens. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Vergelijkt de huidige instantie met een ander object van hetzelfde type en retourneert een integer die aangeeft of de huidige instantie voorafgaat, volgt of zich op dezelfde positie in de sorteervolgorde bevindt als het andere object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Een object om te vergelijken met deze instantie. |

**Returns:**
int - Een 32-bits ondertekend geheel getal dat de relatieve volgorde van de te vergelijken objecten aangeeft. De retourwaarde heeft de volgende betekenissen: Waarde Betekenis Minder dan nul Deze instantie is kleiner dan obj. Nul Deze instantie is gelijk aan obj. Groter dan nul Deze instantie is groter dan obj.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Maakt een diepe kloon van deze instantie.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Haalt de extra gegevensgrootte op in bytes (voor het geval de 12 bytes niet voldoende zijn om de taggegevens te bevatten).

**Returns:**
long - De extra gegevensgrootte in bytes.

Dit is het aantal gegevensbytes uitgelijnd op een woordgrens.
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


Haalt het aantal elementen op.

**Returns:**
long - Het aantal elementen.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Haalt de extra gegevensgrootte op in bytes (voor het geval de 12 bytes niet voldoende zijn om de taggegevens te bevatten).

**Returns:**
long - De extra gegevensgrootte in bytes.

Dit is het exacte aantal bytes.
### getId() {#getId--}
```
public int getId()
```


Haalt de integerrepresentatie van de tag-id op.

**Returns:**
int - De integerrepresentatie van de tag-id
### getTagId() {#getTagId--}
```
public int getTagId()
```


Haalt de tag-id op.

**Returns:**
int - De tag-id.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Haalt het tagtype op.

**Returns:**
int - Het tagtype.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Haalt de waarde op die dit gegevenstype bevat.

**Returns:**
java.lang.Object - De waarde.
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


Haalt een waarde op die aangeeft of de tag privé is. Privé tiff-tags zijn tags met een tag-id groter dan 32768.

**Returns:**
boolean -  true  als taggegevens geldig zijn; anders,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Haalt een waarde op die aangeeft of taggegevens geldig zijn. Een geldige tag bevat gegevens die bewaard kunnen blijven. Een ongeldige tag kan niet worden opgeslagen.

**Returns:**
boolean -  true  als taggegevens geldig zijn; anders,  false .
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


Leest de taggegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | De datastream. |
| position | long | De tagpositie. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Stelt de waarde in die dit gegevenstype bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object | De waarde. |

### toString() {#toString--}
```
public String toString()
```


Retourneert een  System.String  die deze instantie vertegenwoordigt.

**Returns:**
java.lang.String - Een  System.String  die deze instantie vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Schrijft de extra taggegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | De datastream. |

**Returns:**
long - Het werkelijke aantal geschreven bytes.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Schrijft de taggegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | De datastream. |
| additionalDataOffset | long | De offset om extra gegevens naar te schrijven. |

