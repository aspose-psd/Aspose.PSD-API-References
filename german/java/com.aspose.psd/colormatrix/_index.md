---
title: "ColorMatrix"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert eine 5 × 5‑Matrix, die die Koordinaten für den RGBA‑Raum enthält."
type: docs
weight: 25
url: /de/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Definiert eine 5 x 5 Matrix, die die Koordinaten für den RGBA‑Raum enthält. Mehrere Methoden der  com.aspose.psd.ImageAttributes  Klasse passen Bildfarben mithilfe einer Farbmatrix an. Diese Klasse kann nicht vererbt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initialisiert eine neue Instanz der  Aspose.Imaging.ColorMatrix  Klasse. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initialisiert eine neue Instanz der  Aspose.Imaging.ColorMatrix  Klasse unter Verwendung der Elemente in der angegebenen Matrix  newColorMatrix . |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | Die Anzahl der Elemente in der Matrixdimension. |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | Die Anzahl der Matrixdimensionen. |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | Die Gesamtzahl der Elemente in der Matrix. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | Liefert die Matrixwerte. |
| [getMatrix00()](#getMatrix00--) | Liefert das Element in Zeile 0 (null) und Spalte 0 dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix01()](#getMatrix01--) | Liefert das Element in Zeile 0 (null) und erster Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix02()](#getMatrix02--) | Liefert das Element in Zeile 0 (null) und zweiter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix03()](#getMatrix03--) | Liefert das Element in Zeile 0 (null) und dritter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix04()](#getMatrix04--) | Liefert das Element in Zeile 0 (null) und vierter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix10()](#getMatrix10--) | Liefert das Element in der ersten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix11()](#getMatrix11--) | Liefert das Element in der ersten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix12()](#getMatrix12--) | Liefert das Element in der ersten Zeile und zweiter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix13()](#getMatrix13--) | Liefert das Element in der ersten Zeile und dritter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix14()](#getMatrix14--) | Liefert das Element in der ersten Zeile und vierter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix20()](#getMatrix20--) | Liefert das Element in der zweiten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix21()](#getMatrix21--) | Liefert das Element in der zweiten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix22()](#getMatrix22--) | Liefert das Element in der zweiten Zeile und zweiter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix23()](#getMatrix23--) | Liefert das Element in der zweiten Zeile und dritter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix24()](#getMatrix24--) | Liefert das Element in der zweiten Zeile und vierter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix30()](#getMatrix30--) | Liefert das Element in der dritten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix31()](#getMatrix31--) | Liefert das Element in der dritten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix32()](#getMatrix32--) | Liefert das Element in der dritten Zeile und zweiter Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix33()](#getMatrix33--) | Liest das Element in der dritten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix34()](#getMatrix34--) | Liest das Element in der dritten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix40()](#getMatrix40--) | Liest das Element in der vierten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix41()](#getMatrix41--) | Liest das Element in der vierten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix42()](#getMatrix42--) | Liest das Element in der vierten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix43()](#getMatrix43--) | Liest das Element in der vierten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [getMatrix44()](#getMatrix44--) | Liest das Element in der vierten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [get_Item(int row, int column)](#get-Item-int-int-) | Liest das Element in der angegebenen Zeile und Spalte der  Aspose.Imaging.ColorMatrix . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | Setzt das Element in der 0 (null) Zeile und 0 Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix01(float value)](#setMatrix01-float-) | Setzt das Element in der 0 (null) Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix02(float value)](#setMatrix02-float-) | Setzt das Element in der 0 (null) Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix03(float value)](#setMatrix03-float-) | Setzt das Element in der 0 (null) Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix04(float value)](#setMatrix04-float-) | Setzt das Element in der 0 (null) Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix10(float value)](#setMatrix10-float-) | Setzt das Element in der ersten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix11(float value)](#setMatrix11-float-) | Setzt das Element in der ersten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix12(float value)](#setMatrix12-float-) | Setzt das Element in der ersten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix13(float value)](#setMatrix13-float-) | Setzt das Element in der ersten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix14(float value)](#setMatrix14-float-) | Setzt das Element in der ersten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix20(float value)](#setMatrix20-float-) | Setzt das Element in der zweiten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix21(float value)](#setMatrix21-float-) | Setzt das Element in der zweiten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix22(float value)](#setMatrix22-float-) | Setzt das Element in der zweiten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix23(float value)](#setMatrix23-float-) | Setzt das Element in der zweiten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix24(float value)](#setMatrix24-float-) | Setzt das Element in der zweiten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix30(float value)](#setMatrix30-float-) | Setzt das Element in der dritten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix31(float value)](#setMatrix31-float-) | Setzt das Element in der dritten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix32(float value)](#setMatrix32-float-) | Setzt das Element in der dritten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix33(float value)](#setMatrix33-float-) | Setzt das Element in der dritten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix34(float value)](#setMatrix34-float-) | Setzt das Element in der dritten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix40(float value)](#setMatrix40-float-) | Setzt das Element in der vierten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix41(float value)](#setMatrix41-float-) | Setzt das Element in der vierten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix42(float value)](#setMatrix42-float-) | Setzt das Element in der vierten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix43(float value)](#setMatrix43-float-) | Setzt das Element in der vierten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [setMatrix44(float value)](#setMatrix44-float-) | Setzt das Element in der vierten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Setzt das Element in der angegebenen Zeile und Spalte in der  Aspose.Imaging.ColorMatrix . |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initialisiert eine neue Instanz der  Aspose.Imaging.ColorMatrix  Klasse.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.ColorMatrix  Klasse unter Verwendung der Elemente in der angegebenen Matrix  newColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | float[][] | Die Werte der Elemente für die neue  Aspose.Imaging.ColorMatrix . |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


Die Anzahl der Elemente in der Matrixdimension.

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


Die Anzahl der Matrixdimensionen.

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


Die Gesamtzahl der Elemente in der Matrix.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Liefert die Matrixwerte.

**Returns:**
float[][] - Das Array der Matrixwerte.
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Liefert das Element in Zeile 0 (null) und Spalte 0 dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der 0 Zeile und 0 Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Liefert das Element in Zeile 0 (null) und erster Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der 0 Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix  .
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Liefert das Element in Zeile 0 (null) und zweiter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der 0 Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Liefert das Element in Zeile 0 (null) und dritter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der 0 Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Liefert das Element in Zeile 0 (null) und vierter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der 0 Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Liefert das Element in der ersten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der ersten Zeile und 0 Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Liefert das Element in der ersten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der ersten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Liefert das Element in der ersten Zeile und zweiter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der ersten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Liefert das Element in der ersten Zeile und dritter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der ersten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Liefert das Element in der ersten Zeile und vierter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der ersten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Liefert das Element in der zweiten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der zweiten Zeile und 0 Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Liefert das Element in der zweiten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der zweiten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Liefert das Element in der zweiten Zeile und zweiter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der zweiten Zeile und zweiten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Liefert das Element in der zweiten Zeile und dritter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der zweiten Zeile und dritten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Liefert das Element in der zweiten Zeile und vierter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der zweiten Zeile und vierten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Liefert das Element in der dritten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der dritten Zeile und 0. Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Liefert das Element in der dritten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der dritten Zeile und ersten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Liefert das Element in der dritten Zeile und zweiter Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der dritten Zeile und zweiten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Liest das Element in der dritten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der dritten Zeile und dritten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Liest das Element in der dritten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der dritten Zeile und vierten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Liest das Element in der vierten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der vierten Zeile und 0. Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Liest das Element in der vierten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der vierten Zeile und ersten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Liest das Element in der vierten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der vierten Zeile und zweiten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Liest das Element in der vierten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der vierten Zeile und dritten Spalte dieses  Aspose.Imaging.ColorMatrix .
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Liest das Element in der vierten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Das Element in der vierten Zeile und vierten Spalte dieses  Aspose.Imaging.ColorMatrix .
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Liest das Element in der angegebenen Zeile und Spalte der  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeile | int | Die Zeilennummer. |
| Spalte | int | Die Spaltennummer. |

**Returns:**
float - Das Element in der angegebenen Zeile und Spalte.
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


Setzt das Element in der 0 (null) Zeile und 0 Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der 0. Zeile und 0. Spalte dieses  Aspose.Imaging.ColorMatrix . |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Setzt das Element in der 0 (null) Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der 0. Zeile und ersten Spalte dieses  Aspose.Imaging.ColorMatrix  . |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Setzt das Element in der 0 (null) Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der 0. Zeile und zweiten Spalte dieses  Aspose.Imaging.ColorMatrix . |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Setzt das Element in der 0 (null) Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der 0. Zeile und dritten Spalte dieses  Aspose.Imaging.ColorMatrix . |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Setzt das Element in der 0 (null) Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der 0. Zeile und vierten Spalte dieses  Aspose.Imaging.ColorMatrix . |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Setzt das Element in der ersten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der ersten Zeile und 0. Spalte dieses  Aspose.Imaging.ColorMatrix . |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Setzt das Element in der ersten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der ersten Zeile und ersten Spalte dieses  Aspose.Imaging.ColorMatrix . |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Setzt das Element in der ersten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der ersten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Setzt das Element in der ersten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der ersten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Setzt das Element in der ersten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der ersten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Setzt das Element in der zweiten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und 0. Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Setzt das Element in der zweiten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Setzt das Element in der zweiten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Setzt das Element in der zweiten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Setzt das Element in der zweiten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Setzt das Element in der dritten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und 0. Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Setzt das Element in der dritten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Setzt das Element in der dritten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Setzt das Element in der dritten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Setzt das Element in der dritten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Setzt das Element in der vierten Zeile und 0 (null) Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und 0. Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Setzt das Element in der vierten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und ersten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Setzt das Element in der vierten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und zweiten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Setzt das Element in der vierten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und dritten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Setzt das Element in der vierten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und vierten Spalte dieser  Aspose.Imaging.ColorMatrix . |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Setzt das Element in der angegebenen Zeile und Spalte in der  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeile | int | Die Zeilennummer. |
| Spalte | int | Die Spaltennummer. |
| Wert | float | Der Wert |

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

