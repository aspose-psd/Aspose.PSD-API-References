---
title: "ColorMatrix"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert een 5 x 5 matrix die de coördinaten voor de RGBA-ruimte bevat."
type: docs
weight: 25
url: /nl/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Definieert een 5 x 5 matrix die de coördinaten voor de RGBA-ruimte bevat. Verschillende methoden van de  com.aspose.psd.ImageAttributes  klasse passen afbeeldingskleuren aan door een kleurmatrix te gebruiken. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.ColorMatrix  klasse. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.ColorMatrix  klasse met behulp van de elementen in de opgegeven matrix  newColorMatrix . |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | Het aantal elementen in matrixdimensie. |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | Het aantal matrixdimensies. |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | Het totale aantal elementen in de matrix. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | Haalt de matrixwaarden op. |
| [getMatrix00()](#getMatrix00--) | Haalt het element op in de 0 (nul) rij en 0 kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix01()](#getMatrix01--) | Haalt het element op in de 0 (nul) rij en eerste kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix02()](#getMatrix02--) | Haalt het element op in de 0 (nul) rij en tweede kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix03()](#getMatrix03--) | Haalt het element op in de 0 (nul) rij en derde kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix04()](#getMatrix04--) | Haalt het element op in de 0 (nul) rij en vierde kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix10()](#getMatrix10--) | Haalt het element op in de eerste rij en 0 (nul) kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix11()](#getMatrix11--) | Haalt het element op in de eerste rij en eerste kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix12()](#getMatrix12--) | Haalt het element op in de eerste rij en tweede kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix13()](#getMatrix13--) | Haalt het element op in de eerste rij en derde kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix14()](#getMatrix14--) | Haalt het element op in de eerste rij en vierde kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix20()](#getMatrix20--) | Haalt het element op in de tweede rij en 0 (nul) kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix21()](#getMatrix21--) | Haalt het element op in de tweede rij en eerste kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix22()](#getMatrix22--) | Haalt het element op in de tweede rij en tweede kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix23()](#getMatrix23--) | Haalt het element op in de tweede rij en derde kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix24()](#getMatrix24--) | Haalt het element op in de tweede rij en vierde kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix30()](#getMatrix30--) | Haalt het element op in de derde rij en 0 (nul) kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix31()](#getMatrix31--) | Haalt het element op in de derde rij en eerste kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix32()](#getMatrix32--) | Haalt het element op in de derde rij en tweede kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix33()](#getMatrix33--) | Haalt het element op in de derde rij en derde kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix34()](#getMatrix34--) | Haalt het element op in de derde rij en vierde kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix40()](#getMatrix40--) | Haalt het element op in de vierde rij en 0 (nul) kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix41()](#getMatrix41--) | Haalt het element op in de vierde rij en eerste kolom van deze Aspose.Imaging.ColorMatrix. |
| [getMatrix42()](#getMatrix42--) | Haalt het element op in de vierde rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix . |
| [getMatrix43()](#getMatrix43--) | Haalt het element op in de vierde rij en derde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [getMatrix44()](#getMatrix44--) | Haalt het element op in de vierde rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [get_Item(int row, int column)](#get-Item-int-int-) | Haalt het element op in de opgegeven rij en kolom in de  Aspose.Imaging.ColorMatrix . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | Stelt het element in op de 0 (nul) rij en 0 kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix01(float value)](#setMatrix01-float-) | Stelt het element in op de 0 (nul) rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix02(float value)](#setMatrix02-float-) | Stelt het element in op de 0 (nul) rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix03(float value)](#setMatrix03-float-) | Stelt het element in op de 0 (nul) rij en derde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix04(float value)](#setMatrix04-float-) | Stelt het element in op de 0 (nul) rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix10(float value)](#setMatrix10-float-) | Stelt het element in op de eerste rij en 0 (nul) kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix11(float value)](#setMatrix11-float-) | Stelt het element in op de eerste rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix12(float value)](#setMatrix12-float-) | Stelt het element in op de eerste rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix13(float value)](#setMatrix13-float-) | Stelt het element in op de eerste rij en derde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix14(float value)](#setMatrix14-float-) | Stelt het element in op de eerste rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix20(float value)](#setMatrix20-float-) | Stelt het element in op de tweede rij en 0 (nul) kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix21(float value)](#setMatrix21-float-) | Stelt het element in op de tweede rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix22(float value)](#setMatrix22-float-) | Stelt het element in op de tweede rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix23(float value)](#setMatrix23-float-) | Stelt het element in op de tweede rij en derde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix24(float value)](#setMatrix24-float-) | Stelt het element in op de tweede rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix30(float value)](#setMatrix30-float-) | Stelt het element in op de derde rij en 0 (nul) kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix31(float value)](#setMatrix31-float-) | Stelt het element in op de derde rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix32(float value)](#setMatrix32-float-) | Stelt het element in op de derde rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix33(float value)](#setMatrix33-float-) | Stelt het element in op de derde rij en derde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix34(float value)](#setMatrix34-float-) | Stelt het element in op de derde rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix40(float value)](#setMatrix40-float-) | Stelt het element in op de vierde rij en 0 (nul) kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix41(float value)](#setMatrix41-float-) | Stelt het element in op de vierde rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix42(float value)](#setMatrix42-float-) | Stelt het element in op de vierde rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix43(float value)](#setMatrix43-float-) | Stelt het element in op de vierde rij en derde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [setMatrix44(float value)](#setMatrix44-float-) | Stelt het element in op de vierde rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix . |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Stelt het element in op de opgegeven rij en kolom in de  Aspose.Imaging.ColorMatrix . |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.ColorMatrix  klasse.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.ColorMatrix  klasse met behulp van de elementen in de opgegeven matrix  newColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | float[][] | De waarden van de elementen voor de nieuwe  Aspose.Imaging.ColorMatrix . |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


Het aantal elementen in matrixdimensie.

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


Het aantal matrixdimensies.

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


Het totale aantal elementen in de matrix.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de matrixwaarden op.

**Returns:**
float[][] - De matrixwaarden array.
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Haalt het element op in de 0 (nul) rij en 0 kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op rij 0 en kolom 0 van deze  Aspose.Imaging.ColorMatrix .
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Haalt het element op in de 0 (nul) rij en eerste kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op rij 0 en eerste kolom van deze  Aspose.Imaging.ColorMatrix  .
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Haalt het element op in de 0 (nul) rij en tweede kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op rij 0 en tweede kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Haalt het element op in de 0 (nul) rij en derde kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op rij 0 en derde kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Haalt het element op in de 0 (nul) rij en vierde kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op rij 0 en vierde kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Haalt het element op in de eerste rij en 0 (nul) kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op eerste rij en kolom 0 van deze  Aspose.Imaging.ColorMatrix .
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Haalt het element op in de eerste rij en eerste kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op eerste rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Haalt het element op in de eerste rij en tweede kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op eerste rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Haalt het element op in de eerste rij en derde kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op eerste rij en derde kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Haalt het element op in de eerste rij en vierde kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op eerste rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Haalt het element op in de tweede rij en 0 (nul) kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op tweede rij en kolom 0 van deze  Aspose.Imaging.ColorMatrix .
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Haalt het element op in de tweede rij en eerste kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op tweede rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Haalt het element op in de tweede rij en tweede kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op tweede rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Haalt het element op in de tweede rij en derde kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op tweede rij en derde kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Haalt het element op in de tweede rij en vierde kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op tweede rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix .
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Haalt het element op in de derde rij en 0 (nul) kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op derde rij en kolom 0 van deze  Aspose.Imaging.ColorMatrix .
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Haalt het element op in de derde rij en eerste kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op de derde rij en eerste kolom van deze Aspose.Imaging.ColorMatrix.
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Haalt het element op in de derde rij en tweede kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op de derde rij en tweede kolom van deze Aspose.Imaging.ColorMatrix.
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Haalt het element op in de derde rij en derde kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op de derde rij en derde kolom van deze Aspose.Imaging.ColorMatrix.
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Haalt het element op in de derde rij en vierde kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op de derde rij en vierde kolom van deze Aspose.Imaging.ColorMatrix.
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Haalt het element op in de vierde rij en 0 (nul) kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op de vierde rij en 0 kolom van deze Aspose.Imaging.ColorMatrix.
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Haalt het element op in de vierde rij en eerste kolom van deze Aspose.Imaging.ColorMatrix.

**Returns:**
float - Het element op de vierde rij en eerste kolom van deze Aspose.Imaging.ColorMatrix.
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Haalt het element op in de vierde rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Het element op de vierde rij en tweede kolom van deze Aspose.Imaging.ColorMatrix.
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Haalt het element op in de vierde rij en derde kolom van deze  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Het element op de vierde rij en derde kolom van deze Aspose.Imaging.ColorMatrix.
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Haalt het element op in de vierde rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Het element op de vierde rij en vierde kolom van deze Aspose.Imaging.ColorMatrix.
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Haalt het element op in de opgegeven rij en kolom in de  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rij | int | Het rijnummer. |
| kolom | int | Het kolomnummer. |

**Returns:**
float - Het element op de opgegeven rij en kolom.
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


Stelt het element in op de 0 (nul) rij en 0 kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de 0 rij en 0 kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Stelt het element in op de 0 (nul) rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de 0 rij en eerste kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Stelt het element in op de 0 (nul) rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de 0 rij en tweede kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Stelt het element in op de 0 (nul) rij en derde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de 0 rij en derde kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Stelt het element in op de 0 (nul) rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de 0 rij en vierde kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Stelt het element in op de eerste rij en 0 (nul) kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de eerste rij en 0 kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Stelt het element in op de eerste rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de eerste rij en eerste kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Stelt het element in op de eerste rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de eerste rij en tweede kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Stelt het element in op de eerste rij en derde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de eerste rij en derde kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Stelt het element in op de eerste rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de eerste rij en vierde kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Stelt het element in op de tweede rij en 0 (nul) kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de tweede rij en 0 kolom van deze Aspose.Imaging.ColorMatrix. |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Stelt het element in op de tweede rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de tweede rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Stelt het element in op de tweede rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de tweede rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Stelt het element in op de tweede rij en derde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de tweede rij en derde kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Stelt het element in op de tweede rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de tweede rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Stelt het element in op de derde rij en 0 (nul) kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de derde rij en 0 kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Stelt het element in op de derde rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de derde rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Stelt het element in op de derde rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de derde rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Stelt het element in op de derde rij en derde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de derde rij en derde kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Stelt het element in op de derde rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de derde rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Stelt het element in op de vierde rij en 0 (nul) kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de vierde rij en 0 kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Stelt het element in op de vierde rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de vierde rij en eerste kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Stelt het element in op de vierde rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de vierde rij en tweede kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Stelt het element in op de vierde rij en derde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de vierde rij en derde kolom van deze  Aspose.Imaging.ColorMatrix . |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Stelt het element in op de vierde rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Het element op de vierde rij en vierde kolom van deze  Aspose.Imaging.ColorMatrix . |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Stelt het element in op de opgegeven rij en kolom in de  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rij | int | Het rijnummer. |
| kolom | int | Het kolomnummer. |
| waarde | float | De waarde |

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

