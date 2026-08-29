---
title: "Typsnitt"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar ett specifikt format för text inklusive teckensnittsstorlek och stilattribut."
type: docs
weight: 46
url: /sv/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Initierar ett nytt  com.aspose.psd.Font  som använder den angivna befintliga  com.aspose.psd.Font  och  com.aspose.psd.FontStyle  uppräkningen. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Initierar ett nytt  com.aspose.psd.Font  med en angiven storlek. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initierar ett nytt  com.aspose.psd.Font  med en angiven storlek och stil. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Initierar ett nytt  com.aspose.psd.Font  med en angiven storlek, stil, enhet och teckenuppsättning. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initierar ett nytt  com.aspose.psd.Font  med en angiven storlek, stil och enhet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en exakt djup kopia av detta  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | Indikerar om det angivna objektet är en  com.aspose.psd.Font  och har samma egenskapsvärden som detta  com.aspose.psd.Font . |
| [getBold()](#getBold--) | Hämtar ett värde som indikerar om detta  Font  är fetstil. |
| [getCharacterSet()](#getCharacterSet--) | Hämtar ett bytevärde som specificerar teckenuppsättningen som detta  Font  använder. |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Hämtar ett värde som indikerar om detta  Font  är kursiv. |
| [getName()](#getName--) | Hämtar teckensnittsnamnet för detta  Font . |
| [getSize()](#getSize--) | Hämtar em-storleken för detta  Font  mätt i de enheter som anges av egenskapen  P:Aspose.Imaging.Font.Unit . |
| [getStrikeout()](#getStrikeout--) | Hämtar ett värde som indikerar om detta  Font  specificerar en horisontell linje genom teckensnittet. |
| [getStyle()](#getStyle--) | Hämtar stilinformation för detta  Font . |
| [getUnderline()](#getUnderline--) | Hämtar ett värde som indikerar om detta  Font  är understruket. |
| [getUnit()](#getUnit--) | Hämtar måttenheten för detta  Font . |
| [hashCode()](#hashCode--) | Hämtar hashkoden för detta  com.aspose.psd.Font . |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Initierar ett nytt  com.aspose.psd.Font  med en angiven storlek och enhet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta  com.aspose.psd.Font . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initierar ett nytt  com.aspose.psd.Font  som använder den angivna befintliga  com.aspose.psd.Font  och  com.aspose.psd.FontStyle  uppräkningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | Den befintliga com.aspose.psd.Font från vilken den nya com.aspose.psd.Font ska skapas. |
| newStyle | int | Den com.aspose.psd.FontStyle som ska tillämpas på den nya com.aspose.psd.Font. Flera värden i com.aspose.psd.FontStyle‑enumerationen kan kombineras med OR‑operatorn. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Initierar ett nytt com.aspose.psd.Font med en angiven storlek. Teckenuppsättningen sätts till F:Aspose.Imaging.CharacterSet.Default, grafik‑enheten till F:Aspose.Imaging.GraphicsUnit.Point och teckensnittsstilen till F:Aspose.Imaging.FontStyle.Regular.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av com.aspose.psd.Font‑namnet. |
| emSize | float | Em‑storleken, i punkter, för det nya teckensnittet. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Initierar ett nytt com.aspose.psd.Font med en angiven storlek och stil. Teckenuppsättningen sätts till F:Aspose.Imaging.CharacterSet.Default, grafik‑enheten till F:Aspose.Imaging.GraphicsUnit.Point.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av com.aspose.psd.Font‑namnet. |
| emSize | float | Em‑storleken, i punkter, för det nya teckensnittet. |
| style | int | Den com.aspose.psd.FontStyle för det nya teckensnittet. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Initierar ett nytt  com.aspose.psd.Font  med en angiven storlek, stil, enhet och teckenuppsättning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av com.aspose.psd.Font‑namnet. |
| emSize | float | Em‑storleken för det nya teckensnittet i de enheter som anges av unit‑parametern. |
| style | int | Den com.aspose.psd.FontStyle för det nya teckensnittet. |
| unit | int | Den com.aspose.psd.GraphicsUnit för det nya teckensnittet. |
| characterSet | int | En boolean – True om obj‑parameter är ett com.aspose.psd.Font och har samma egenskapsvärden som detta com.aspose.psd.Font; annars false. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Initierar ett nytt  com.aspose.psd.Font  med en angiven storlek, stil och enhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av com.aspose.psd.Font‑namnet. |
| emSize | float | Em‑storleken för det nya teckensnittet i de enheter som anges av unit‑parametern. |
| style | int | Den com.aspose.psd.FontStyle för det nya teckensnittet. |
| unit | int | Den com.aspose.psd.GraphicsUnit för det nya teckensnittet. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Skapar en exakt djup kopia av detta  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indikerar om det angivna objektet är en  com.aspose.psd.Font  och har samma egenskapsvärden som detta  com.aspose.psd.Font .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
En boolean – True om detta Font är fetstil; annars false.
### getBold() {#getBold--}
```
public boolean getBold()
```


Hämtar ett värde som indikerar om detta  Font  är fetstil.

**Returns:**
int – En teckenuppsättning som detta Font använder.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Hämtar ett bytevärde som specificerar teckenuppsättningen som detta  Font  använder.

**Returns:**
En boolean – True om detta Font är kursivt; annars false.
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


Hämtar ett värde som indikerar om detta  Font  är kursiv.

**Returns:**
java.lang.String – En strängrepresentation av detta Fonts typsnittsnamn.
### getName() {#getName--}
```
public String getName()
```


Hämtar teckensnittsnamnet för detta  Font .

**Returns:**
float – Em‑storleken för detta Font.
### getSize() {#getSize--}
```
public float getSize()
```


Hämtar em-storleken för detta  Font  mätt i de enheter som anges av egenskapen  P:Aspose.Imaging.Font.Unit .

**Returns:**
En boolean – True om detta Font har ett horisontellt streck igenom; annars false.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Hämtar ett värde som indikerar om detta  Font  specificerar en horisontell linje genom teckensnittet.

**Returns:**
int – En FontStyle‑enumeration som innehåller stilinformation för detta Font.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Hämtar stilinformation för detta  Font .

**Returns:**
En boolean – True om detta Font är understruket; annars false.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Hämtar ett värde som indikerar om detta  Font  är understruket.

**Returns:**
int – En GraphicsUnit som representerar måttenheten för detta Font.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Hämtar måttenheten för detta  Font .

**Returns:**
int - En  GraphicsUnit  som representerar måttenheten för detta  Font .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hashkoden för detta  com.aspose.psd.Font .

**Returns:**
int - Hashkoden för detta  com.aspose.psd.Font .
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Initierar ett nytt  com.aspose.psd.Font  med en angiven storlek och enhet. Teckenuppsättningen är satt till  F:Aspose.Imaging.CharacterSet.Default , stilen är satt till  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av com.aspose.psd.Font‑namnet. |
| emSize | float | Em‑storleken för det nya teckensnittet i de enheter som anges av unit‑parametern. |
| unit | int | Den com.aspose.psd.GraphicsUnit för det nya teckensnittet. |

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


Returnerar en människoläsbar strängrepresentation av detta  com.aspose.psd.Font .

**Returns:**
java.lang.String - En sträng som representerar detta  com.aspose.psd.Font .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

