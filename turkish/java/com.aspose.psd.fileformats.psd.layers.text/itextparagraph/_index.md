---
title: "ITextParagraph"
second_title: "Java için Aspose.PSD API Referansı"
description: "Paragraf ile çalışmak için arayüz"
type: docs
weight: 12
url: /tr/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

Paragraf ile çalışmak için arayüz
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Belirtilen paragrafı uygular. |
| [getAutoHyphenate()](#getAutoHyphenate--) | Otomatik tireleme [automatic hyphenate] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getAutoLeading()](#getAutoLeading--) | Otomatik satır aralığını alır veya ayarlar. |
| [getBurasagari()](#getBurasagari--) | Bu [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) öğesinin burasagiri olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | Ardışık tireleri alır veya ayarlar. |
| [getEndIndent()](#getEndIndent--) | Son girintiyi alır veya ayarlar. |
| [getEveryLineComposer()](#getEveryLineComposer--) | Her satır besteci [every line composer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getFirstLineIndent()](#getFirstLineIndent--) | İlk satır girintisini alır veya ayarlar. |
| [getGlyphSpacing()](#getGlyphSpacing--) | Glif aralığını alır veya ayarlar. |
| [getHanging()](#getHanging--) | Bu [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) öğesinin asılı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | Tireli kelimenin boyutunu alır veya ayarlar. |
| [getJustification()](#getJustification--) | Hizalamayı alır veya ayarlar. |
| [getKinsokuOrder()](#getKinsokuOrder--) | Kinsoku sırasını alır veya ayarlar. |
| [getLeadingType()](#getLeadingType--) | Satır aralığının tipini alır veya ayarlar. |
| [getLetterSpacing()](#getLetterSpacing--) | Harf aralığını alır veya ayarlar. |
| [getPostHyphen()](#getPostHyphen--) | Son tireyi alır veya ayarlar. |
| [getPreHyphen()](#getPreHyphen--) | Ön tireyi alır veya ayarlar. |
| [getSpaceAfter()](#getSpaceAfter--) | Sonrasındaki boşluğu alır veya ayarlar. |
| [getSpaceBefore()](#getSpaceBefore--) | Öncesindeki boşluğu alır veya ayarlar. |
| [getStartIndent()](#getStartIndent--) | Başlangıç girintisini alır veya ayarlar. |
| [getWordSpacing()](#getWordSpacing--) | Kelime aralığını alır veya ayarlar. |
| [getZone()](#getZone--) | Bölgeyi alır veya ayarlar. |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Belirtilen paragrafın eşit olup olmadığını belirler. |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | Otomatik tireleme [automatic hyphenate] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAutoLeading(double value)](#setAutoLeading-double-) | Otomatik satır aralığını alır veya ayarlar. |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | Bu [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) öğesinin burasagiri olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | Ardışık tireleri alır veya ayarlar. |
| [setEndIndent(double value)](#setEndIndent-double-) | Son girintiyi alır veya ayarlar. |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | Her satır besteci [every line composer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | İlk satır girintisini alır veya ayarlar. |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | Glif aralığını alır veya ayarlar. |
| [setHanging(boolean value)](#setHanging-boolean-) | Bu [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) öğesinin asılı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | Tireli kelimenin boyutunu alır veya ayarlar. |
| [setJustification(int value)](#setJustification-int-) | Hizalamayı alır veya ayarlar. |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | Kinsoku sırasını alır veya ayarlar. |
| [setLeadingType(int value)](#setLeadingType-int-) | Satır aralığının tipini alır veya ayarlar. |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | Harf aralığını alır veya ayarlar. |
| [setPostHyphen(int value)](#setPostHyphen-int-) | Son tireyi alır veya ayarlar. |
| [setPreHyphen(int value)](#setPreHyphen-int-) | Ön tireyi alır veya ayarlar. |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | Sonrasındaki boşluğu alır veya ayarlar. |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | Öncesindeki boşluğu alır veya ayarlar. |
| [setStartIndent(double value)](#setStartIndent-double-) | Başlangıç girintisini alır veya ayarlar. |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | Kelime aralığını alır veya ayarlar. |
| [setZone(double value)](#setZone-double-) | Bölgeyi alır veya ayarlar. |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


Belirtilen paragrafı uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Paragraf. |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


Otomatik tireleme [automatic hyphenate] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [automatic hyphenate]; aksi takdirde,  false .

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


Otomatik satır aralığını alır veya ayarlar.

Değer: Otomatik satır aralığı.

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


Bu [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) öğesinin burasagiri olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer burasagiri; aksi takdirde,  false .

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


Ardışık tireleri alır veya ayarlar.

Değer: Ardışık tireler.

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


Son girintiyi alır veya ayarlar.

Değer: Son girinti.

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


Her satır besteci [every line composer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [every line composer]; aksi takdirde,  false .

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


İlk satır girintisini alır veya ayarlar.

Değer: İlk satır girintisi.

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


Glif aralığını alır veya ayarlar.

Değer: Glif aralığı.

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


Bu [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) öğesinin asılı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer hanging; aksi takdirde,  false .

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


Tireli kelimenin boyutunu alır veya ayarlar.

Değer: Hecelemiş kelimenin boyutu.

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Hizalamayı alır veya ayarlar.

Değer: Hizalama.

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


Kinsoku sırasını alır veya ayarlar.

Değer: Kinsoku sırası.

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


Satır aralığının tipini alır veya ayarlar.

Değer: Satır aralığının tipi.

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


Harf aralığını alır veya ayarlar.

Değer: Harf aralığı.

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


Son tireyi alır veya ayarlar.

Değer: Son tire.

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


Ön tireyi alır veya ayarlar.

Değer: Ön tire.

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


Sonrasındaki boşluğu alır veya ayarlar.

Değer: Sonraki boşluk.

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


Öncesindeki boşluğu alır veya ayarlar.

Değer: Önündeki boşluk.

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


Başlangıç girintisini alır veya ayarlar.

Değer: Başlangıç girintisi.

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


Kelime aralığını alır veya ayarlar.

Değer: Kelime aralığı.

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


Bölgeyi alır veya ayarlar.

Değer: Bölge.

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


Belirtilen paragrafın eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Paragraf. |

**Returns:**
boolean -  true  eğer belirtilen paragraf eşitse; aksi takdirde,  false .
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


Otomatik tireleme [automatic hyphenate] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [automatic hyphenate]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


Otomatik satır aralığını alır veya ayarlar.

Değer: Otomatik satır aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


Bu [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) öğesinin burasagiri olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer burasagiri; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


Ardışık tireleri alır veya ayarlar.

Değer: Ardışık tireler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


Son girintiyi alır veya ayarlar.

Değer: Son girinti.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


Her satır besteci [every line composer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [every line composer]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


İlk satır girintisini alır veya ayarlar.

Değer: İlk satır girintisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


Glif aralığını alır veya ayarlar.

Değer: Glif aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


Bu [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) öğesinin asılı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer hanging; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


Tireli kelimenin boyutunu alır veya ayarlar.

Değer: Hecelemiş kelimenin boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Hizalamayı alır veya ayarlar.

Değer: Hizalama.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


Kinsoku sırasını alır veya ayarlar.

Değer: Kinsoku sırası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


Satır aralığının tipini alır veya ayarlar.

Değer: Satır aralığının tipi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


Harf aralığını alır veya ayarlar.

Değer: Harf aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


Son tireyi alır veya ayarlar.

Değer: Son tire.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


Ön tireyi alır veya ayarlar.

Değer: Ön tire.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


Sonrasındaki boşluğu alır veya ayarlar.

Değer: Sonraki boşluk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


Öncesindeki boşluğu alır veya ayarlar.

Değer: Önündeki boşluk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


Başlangıç girintisini alır veya ayarlar.

Değer: Başlangıç girintisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


Kelime aralığını alır veya ayarlar.

Değer: Kelime aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


Bölgeyi alır veya ayarlar.

Değer: Bölge.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

