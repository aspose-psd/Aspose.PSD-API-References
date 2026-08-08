---
title: "ColorMatrix"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar en 5 x 5-matris som innehåller koordinaterna för RGBA-rymden."
type: docs
weight: 25
url: /sv/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Definierar en 5 x 5-matris som innehåller koordinaterna för RGBA-rymden. Flera metoder i klassen  com.aspose.psd.ImageAttributes  justerar bildfärger genom att använda en färgmatris. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initialiserar en ny instans av klassen Aspose.Imaging.ColorMatrix. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initialiserar en ny instans av klassen Aspose.Imaging.ColorMatrix med elementen i den angivna matrisen newColorMatrix. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | Antalet element i matrisens dimension. |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | Antalet matrisdimensioner. |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | Det totala antalet element i matrisen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | Hämtar matrisens värden. |
| [getMatrix00()](#getMatrix00--) | Hämtar elementet på rad 0 (noll) och kolumn 0 i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix01()](#getMatrix01--) | Hämtar elementet på rad 0 (noll) och första kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix02()](#getMatrix02--) | Hämtar elementet på rad 0 (noll) och andra kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix03()](#getMatrix03--) | Hämtar elementet på rad 0 (noll) och tredje kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix04()](#getMatrix04--) | Hämtar elementet på rad 0 (noll) och fjärde kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix10()](#getMatrix10--) | Hämtar elementet på första raden och kolumn 0 (noll) i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix11()](#getMatrix11--) | Hämtar elementet på första raden och första kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix12()](#getMatrix12--) | Hämtar elementet på första raden och andra kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix13()](#getMatrix13--) | Hämtar elementet på första raden och tredje kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix14()](#getMatrix14--) | Hämtar elementet på första raden och fjärde kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix20()](#getMatrix20--) | Hämtar elementet på andra raden och kolumn 0 (noll) i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix21()](#getMatrix21--) | Hämtar elementet på andra raden och första kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix22()](#getMatrix22--) | Hämtar elementet på andra raden och andra kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix23()](#getMatrix23--) | Hämtar elementet på andra raden och tredje kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix24()](#getMatrix24--) | Hämtar elementet på andra raden och fjärde kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix30()](#getMatrix30--) | Hämtar elementet på tredje raden och kolumn 0 (noll) i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix31()](#getMatrix31--) | Hämtar elementet på tredje raden och första kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix32()](#getMatrix32--) | Hämtar elementet på tredje raden och andra kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix33()](#getMatrix33--) | Hämtar elementet på tredje raden och tredje kolumnen i denna Aspose.Imaging.ColorMatrix. |
| [getMatrix34()](#getMatrix34--) | Hämtar elementet i den tredje raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [getMatrix40()](#getMatrix40--) | Hämtar elementet i den fjärde raden och 0 (noll) kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [getMatrix41()](#getMatrix41--) | Hämtar elementet i den fjärde raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [getMatrix42()](#getMatrix42--) | Hämtar elementet i den fjärde raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [getMatrix43()](#getMatrix43--) | Hämtar elementet i den fjärde raden och tredje kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [getMatrix44()](#getMatrix44--) | Hämtar elementet i den fjärde raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [get_Item(int row, int column)](#get-Item-int-int-) | Hämtar elementet i den angivna raden och kolumnen i  Aspose.Imaging.ColorMatrix . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | Sätter elementet i den 0 (noll) raden och 0 kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix01(float value)](#setMatrix01-float-) | Sätter elementet i den 0 (noll) raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix02(float value)](#setMatrix02-float-) | Sätter elementet i den 0 (noll) raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix03(float value)](#setMatrix03-float-) | Sätter elementet i den 0 (noll) raden och tredje kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix04(float value)](#setMatrix04-float-) | Sätter elementet i den 0 (noll) raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix10(float value)](#setMatrix10-float-) | Sätter elementet i den första raden och 0 (noll) kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix11(float value)](#setMatrix11-float-) | Sätter elementet i den första raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix12(float value)](#setMatrix12-float-) | Sätter elementet i den första raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix13(float value)](#setMatrix13-float-) | Sätter elementet i den första raden och tredje kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix14(float value)](#setMatrix14-float-) | Sätter elementet i den första raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix20(float value)](#setMatrix20-float-) | Sätter elementet i den andra raden och 0 (noll) kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix21(float value)](#setMatrix21-float-) | Sätter elementet i den andra raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix22(float value)](#setMatrix22-float-) | Sätter elementet i den andra raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix23(float value)](#setMatrix23-float-) | Sätter elementet i den andra raden och tredje kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix24(float value)](#setMatrix24-float-) | Sätter elementet i den andra raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix30(float value)](#setMatrix30-float-) | Sätter elementet i den tredje raden och 0 (noll) kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix31(float value)](#setMatrix31-float-) | Sätter elementet i den tredje raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix32(float value)](#setMatrix32-float-) | Sätter elementet i den tredje raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix . |
| [setMatrix33(float value)](#setMatrix33-float-) | Ställer in elementet på den tredje raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix . |
| [setMatrix34(float value)](#setMatrix34-float-) | Ställer in elementet på den tredje raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix . |
| [setMatrix40(float value)](#setMatrix40-float-) | Ställer in elementet på den fjärde raden och 0 (noll) kolumnen i denna  Aspose.Imaging.ColorMatrix . |
| [setMatrix41(float value)](#setMatrix41-float-) | Ställer in elementet på den fjärde raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix . |
| [setMatrix42(float value)](#setMatrix42-float-) | Ställer in elementet på den fjärde raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix . |
| [setMatrix43(float value)](#setMatrix43-float-) | Ställer in elementet på den fjärde raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix . |
| [setMatrix44(float value)](#setMatrix44-float-) | Ställer in elementet på den fjärde raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix . |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Ställer in elementet på den angivna raden och kolumnen i  Aspose.Imaging.ColorMatrix . |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initialiserar en ny instans av klassen Aspose.Imaging.ColorMatrix.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initialiserar en ny instans av klassen Aspose.Imaging.ColorMatrix med elementen i den angivna matrisen newColorMatrix.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | float[][] | Värdena för elementen i den nya  Aspose.Imaging.ColorMatrix . |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


Antalet element i matrisens dimension.

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


Antalet matrisdimensioner.

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


Det totala antalet element i matrisen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


Hämtar matrisens värden.

**Returns:**
float[][] - Matrisens värdearray.
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Hämtar elementet på rad 0 (noll) och kolumn 0 i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på rad 0 och kolumn 0 i denna  Aspose.Imaging.ColorMatrix .
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Hämtar elementet på rad 0 (noll) och första kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på rad 0 och första kolumnen i denna  Aspose.Imaging.ColorMatrix  .
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Hämtar elementet på rad 0 (noll) och andra kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på rad 0 och andra kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Hämtar elementet på rad 0 (noll) och tredje kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på rad 0 och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Hämtar elementet på rad 0 (noll) och fjärde kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på rad 0 och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Hämtar elementet på första raden och kolumn 0 (noll) i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på första raden och kolumn 0 i denna  Aspose.Imaging.ColorMatrix .
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Hämtar elementet på första raden och första kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på första raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Hämtar elementet på första raden och andra kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på första raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Hämtar elementet på första raden och tredje kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på första raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Hämtar elementet på första raden och fjärde kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på första raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Hämtar elementet på andra raden och kolumn 0 (noll) i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på andra raden och kolumn 0 i denna  Aspose.Imaging.ColorMatrix .
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Hämtar elementet på andra raden och första kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på andra raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Hämtar elementet på andra raden och andra kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på andra raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Hämtar elementet på andra raden och tredje kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på den andra raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Hämtar elementet på andra raden och fjärde kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på den andra raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Hämtar elementet på tredje raden och kolumn 0 (noll) i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på den tredje raden och kolumn 0 i denna  Aspose.Imaging.ColorMatrix .
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Hämtar elementet på tredje raden och första kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på den tredje raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Hämtar elementet på tredje raden och andra kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på den tredje raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Hämtar elementet på tredje raden och tredje kolumnen i denna Aspose.Imaging.ColorMatrix.

**Returns:**
float - Elementet på den tredje raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Hämtar elementet i den tredje raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Elementet på den tredje raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Hämtar elementet i den fjärde raden och 0 (noll) kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Elementet på den fjärde raden och kolumn 0 i denna  Aspose.Imaging.ColorMatrix .
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Hämtar elementet i den fjärde raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Elementet på den fjärde raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Hämtar elementet i den fjärde raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Elementet på den fjärde raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Hämtar elementet i den fjärde raden och tredje kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Elementet på den fjärde raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix .
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Hämtar elementet i den fjärde raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Elementet på den fjärde raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix .
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Hämtar elementet i den angivna raden och kolumnen i  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rad | int | Radnumret. |
| kolumn | int | Kolumnnumret. |

**Returns:**
float - Elementet på den angivna raden och kolumnen.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Sätter elementet i den 0 (noll) raden och 0 kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på rad 0 och kolumn 0 i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Sätter elementet i den 0 (noll) raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på rad 0 och första kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Sätter elementet i den 0 (noll) raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på rad 0 och andra kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Sätter elementet i den 0 (noll) raden och tredje kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på rad 0 och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Sätter elementet i den 0 (noll) raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på rad 0 och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Sätter elementet i den första raden och 0 (noll) kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på första raden och kolumn 0 i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Sätter elementet i den första raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på första raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Sätter elementet i den första raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på första raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Sätter elementet i den första raden och tredje kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den första raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Sätter elementet i den första raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den första raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Sätter elementet i den andra raden och 0 (noll) kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och 0 kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Sätter elementet i den andra raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Sätter elementet i den andra raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Sätter elementet i den andra raden och tredje kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Sätter elementet i den andra raden och fjärde kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Sätter elementet i den tredje raden och 0 (noll) kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och 0 kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Sätter elementet i den tredje raden och första kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Sätter elementet i den tredje raden och andra kolumnen i detta  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Ställer in elementet på den tredje raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Ställer in elementet på den tredje raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Ställer in elementet på den fjärde raden och 0 (noll) kolumnen i denna  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och 0 kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Ställer in elementet på den fjärde raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och första kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Ställer in elementet på den fjärde raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och andra kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Ställer in elementet på den fjärde raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och tredje kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Ställer in elementet på den fjärde raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och fjärde kolumnen i denna  Aspose.Imaging.ColorMatrix . |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Ställer in elementet på den angivna raden och kolumnen i  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rad | int | Radnumret. |
| kolumn | int | Kolumnnumret. |
| värde | float | Värdet |

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

