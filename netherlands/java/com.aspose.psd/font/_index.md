---
title: "Lettertype"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken."
type: docs
weight: 46
url: /nl/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Initialiseert een nieuwe  com.aspose.psd.Font  die de opgegeven bestaande  com.aspose.psd.Font  en  com.aspose.psd.FontStyle  enumeratie gebruikt. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte en stijl. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte, stijl, eenheid en tekenset. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte, stijl en eenheid. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een exacte diepe kopie van deze  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | Geeft aan of het opgegeven object een  com.aspose.psd.Font  is en dezelfde eigenschapswaarden heeft als deze  com.aspose.psd.Font . |
| [getBold()](#getBold--) | Haalt een waarde op die aangeeft of deze  Font  vetgedrukt is. |
| [getCharacterSet()](#getCharacterSet--) | Haalt een byte-waarde op die de tekenset specificeert die deze  Font  gebruikt. |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Haalt een waarde op die aangeeft of deze  Font  cursief is. |
| [getName()](#getName--) | Haalt de naam van het lettertype op van deze  Font . |
| [getSize()](#getSize--) | Haalt de em-grootte van deze  Font  op, gemeten in de eenheden die zijn opgegeven door de eigenschap  P:Aspose.Imaging.Font.Unit . |
| [getStrikeout()](#getStrikeout--) | Haalt een waarde op die aangeeft of deze  Font  een horizontale doorstreping specificeert. |
| [getStyle()](#getStyle--) | Haalt stijlinformatie op voor deze  Font . |
| [getUnderline()](#getUnderline--) | Haalt een waarde op die aangeeft of deze  Font  onderstreept is. |
| [getUnit()](#getUnit--) | Haalt de meeteenheid op voor deze  Font . |
| [hashCode()](#hashCode--) | Haalt de hashcode op voor deze  com.aspose.psd.Font . |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte en eenheid. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze  com.aspose.psd.Font . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initialiseert een nieuwe  com.aspose.psd.Font  die de opgegeven bestaande  com.aspose.psd.Font  en  com.aspose.psd.FontStyle  enumeratie gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | De bestaande  com.aspose.psd.Font  waaruit de nieuwe  com.aspose.psd.Font  wordt gecreëerd. |
| newStyle | int | De  com.aspose.psd.FontStyle  die moet worden toegepast op de nieuwe  com.aspose.psd.Font . Meerdere waarden van de  com.aspose.psd.FontStyle  enumeratie kunnen worden gecombineerd met de OR-operator. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte. De tekenset is ingesteld op  F:Aspose.Imaging.CharacterSet.Default , de grafische eenheid op  F:Aspose.Imaging.GraphicsUnit.Point , de lettertype stijl op  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Een tekenreeksrepresentatie van de  com.aspose.psd.Font  naam. |
| emSize | float | De em-grootte, in punten, van het nieuwe lettertype. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte en stijl. De tekenset is ingesteld op  F:Aspose.Imaging.CharacterSet.Default , de grafische eenheid op  F:Aspose.Imaging.GraphicsUnit.Point .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Een tekenreeksrepresentatie van de  com.aspose.psd.Font  naam. |
| emSize | float | De em-grootte, in punten, van het nieuwe lettertype. |
| style | int | De  com.aspose.psd.FontStyle  van het nieuwe lettertype. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte, stijl, eenheid en tekenset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Een tekenreeksrepresentatie van de  com.aspose.psd.Font  naam. |
| emSize | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn opgegeven door de  unit  parameter. |
| style | int | De  com.aspose.psd.FontStyle  van het nieuwe lettertype. |
| unit | int | De  com.aspose.psd.GraphicsUnit  van het nieuwe lettertype. |
| characterSet | int | Een tekenset om te gebruiken voor dit lettertype. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte, stijl en eenheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Een tekenreeksrepresentatie van de  com.aspose.psd.Font  naam. |
| emSize | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn opgegeven door de  unit  parameter. |
| style | int | De  com.aspose.psd.FontStyle  van het nieuwe lettertype. |
| unit | int | De  com.aspose.psd.GraphicsUnit  van het nieuwe lettertype. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Maakt een exacte diepe kopie van deze  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Geeft aan of het opgegeven object een  com.aspose.psd.Font  is en dezelfde eigenschapswaarden heeft als deze  com.aspose.psd.Font .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te testen. |

**Returns:**
boolean - True als de  obj  parameter een  com.aspose.psd.Font  is en dezelfde eigenschapswaarden heeft als deze  com.aspose.psd.Font ; anders, false.
### getBold() {#getBold--}
```
public boolean getBold()
```


Haalt een waarde op die aangeeft of deze  Font  vetgedrukt is.

**Returns:**
boolean - True als dit  Font  vet is; anders, false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Haalt een byte-waarde op die de tekenset specificeert die deze  Font  gebruikt.

**Returns:**
int - Een tekenset die dit  Font  gebruikt.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Haalt een waarde op die aangeeft of deze  Font  cursief is.

**Returns:**
boolean - True als dit  Font  cursief is; anders, false.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam van het lettertype op van deze  Font .

**Returns:**
java.lang.String - Een tekenreeksrepresentatie van de gezichtsnaam van dit  Font .
### getSize() {#getSize--}
```
public float getSize()
```


Haalt de em-grootte van deze  Font  op, gemeten in de eenheden die zijn opgegeven door de eigenschap  P:Aspose.Imaging.Font.Unit .

**Returns:**
float - De em-grootte van dit  Font .
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Haalt een waarde op die aangeeft of deze  Font  een horizontale doorstreping specificeert.

**Returns:**
boolean - True als dit  Font  een horizontale streep erdoor heeft; anders, false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Haalt stijlinformatie op voor deze  Font .

**Returns:**
int - Een  FontStyle  enumeratie die stijlinformatie bevat voor dit  Font .
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Haalt een waarde op die aangeeft of deze  Font  onderstreept is.

**Returns:**
boolean - True als dit  Font  onderstreept is; anders, false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Haalt de meeteenheid op voor deze  Font .

**Returns:**
int - Een  GraphicsUnit  die de meeteenheid voor dit  Font  weergeeft.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Haalt de hashcode op voor deze  com.aspose.psd.Font .

**Returns:**
int - De hashcode voor deze  com.aspose.psd.Font .
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Initialiseert een nieuwe  com.aspose.psd.Font  met een opgegeven grootte en eenheid. De tekenset is ingesteld op  F:Aspose.Imaging.CharacterSet.Default , de stijl is ingesteld op  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Een tekenreeksrepresentatie van de  com.aspose.psd.Font  naam. |
| emSize | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn opgegeven door de  unit  parameter. |
| unit | int | De  com.aspose.psd.GraphicsUnit  van het nieuwe lettertype. |

**Returns:**
[Font](../../com.aspose.psd/font)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze  com.aspose.psd.Font .

**Returns:**
java.lang.String - Een tekenreeks die deze  com.aspose.psd.Font  weergeeft.
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

