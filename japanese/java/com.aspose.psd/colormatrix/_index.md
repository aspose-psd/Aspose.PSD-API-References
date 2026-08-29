---
title: "ColorMatrix"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "RGBA 空間の座標を含む 5×5 行列を定義します。"
type: docs
weight: 25
url: /ja/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

RGBA 空間の座標を含む 5 x 5 行列を定義します。com.aspose.psd.ImageAttributes クラスのいくつかのメソッドは、カラー行列を使用して画像の色を調整します。このクラスは継承できません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Aspose.Imaging.ColorMatrix クラスの新しいインスタンスを初期化します。 |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | 指定された行列 newColorMatrix の要素を使用して、Aspose.Imaging.ColorMatrix クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | 行列次元の要素数です。 |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | 行列の次元数です。 |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | 行列の要素総数です。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | 行列の値を取得します。 |
| [getMatrix00()](#getMatrix00--) | この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と 0 列目の要素を取得します。 |
| [getMatrix01()](#getMatrix01--) | この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と最初の列の要素を取得します。 |
| [getMatrix02()](#getMatrix02--) | この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と2番目の列の要素を取得します。 |
| [getMatrix03()](#getMatrix03--) | この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と3番目の列の要素を取得します。 |
| [getMatrix04()](#getMatrix04--) | この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と4番目の列の要素を取得します。 |
| [getMatrix10()](#getMatrix10--) | この  Aspose.Imaging.ColorMatrix の最初の行と 0 列目（ゼロ）の要素を取得します。 |
| [getMatrix11()](#getMatrix11--) | この  Aspose.Imaging.ColorMatrix の最初の行と最初の列の要素を取得します。 |
| [getMatrix12()](#getMatrix12--) | この  Aspose.Imaging.ColorMatrix の最初の行と2番目の列の要素を取得します。 |
| [getMatrix13()](#getMatrix13--) | この  Aspose.Imaging.ColorMatrix の最初の行と3番目の列の要素を取得します。 |
| [getMatrix14()](#getMatrix14--) | この  Aspose.Imaging.ColorMatrix の最初の行と4番目の列の要素を取得します。 |
| [getMatrix20()](#getMatrix20--) | この  Aspose.Imaging.ColorMatrix の2番目の行と 0 列目（ゼロ）の要素を取得します。 |
| [getMatrix21()](#getMatrix21--) | この  Aspose.Imaging.ColorMatrix の2番目の行と最初の列の要素を取得します。 |
| [getMatrix22()](#getMatrix22--) | この  Aspose.Imaging.ColorMatrix の2番目の行と2番目の列の要素を取得します。 |
| [getMatrix23()](#getMatrix23--) | この  Aspose.Imaging.ColorMatrix の2番目の行と3番目の列の要素を取得します。 |
| [getMatrix24()](#getMatrix24--) | この  Aspose.Imaging.ColorMatrix の2番目の行と4番目の列の要素を取得します。 |
| [getMatrix30()](#getMatrix30--) | この  Aspose.Imaging.ColorMatrix の3番目の行と 0 列目（ゼロ）の要素を取得します。 |
| [getMatrix31()](#getMatrix31--) | この  Aspose.Imaging.ColorMatrix の3番目の行と最初の列の要素を取得します。 |
| [getMatrix32()](#getMatrix32--) | この  Aspose.Imaging.ColorMatrix の3番目の行と2番目の列の要素を取得します。 |
| [getMatrix33()](#getMatrix33--) | この  Aspose.Imaging.ColorMatrix の3番目の行と3番目の列の要素を取得します。 |
| [getMatrix34()](#getMatrix34--) | この  Aspose.Imaging.ColorMatrix の3番目の行と4番目の列の要素を取得します。 |
| [getMatrix40()](#getMatrix40--) | この Aspose.Imaging.ColorMatrix の第4行目と0（ゼロ）列目の要素を取得します。 |
| [getMatrix41()](#getMatrix41--) | この Aspose.Imaging.ColorMatrix の第4行目と第1列目の要素を取得します。 |
| [getMatrix42()](#getMatrix42--) | この Aspose.Imaging.ColorMatrix の第4行目と第2列目の要素を取得します。 |
| [getMatrix43()](#getMatrix43--) | この Aspose.Imaging.ColorMatrix の第4行目と第3列目の要素を取得します。 |
| [getMatrix44()](#getMatrix44--) | この Aspose.Imaging.ColorMatrix の第4行目と第4列目の要素を取得します。 |
| [get_Item(int row, int column)](#get-Item-int-int-) | Aspose.Imaging.ColorMatrix の指定された行と列の要素を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と0列目の要素を設定します。 |
| [setMatrix01(float value)](#setMatrix01-float-) | この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と第1列目の要素を設定します。 |
| [setMatrix02(float value)](#setMatrix02-float-) | この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と第2列目の要素を設定します。 |
| [setMatrix03(float value)](#setMatrix03-float-) | この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と第3列目の要素を設定します。 |
| [setMatrix04(float value)](#setMatrix04-float-) | この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と第4列目の要素を設定します。 |
| [setMatrix10(float value)](#setMatrix10-float-) | この Aspose.Imaging.ColorMatrix の第1行目と0（ゼロ）列目の要素を設定します。 |
| [setMatrix11(float value)](#setMatrix11-float-) | この Aspose.Imaging.ColorMatrix の第1行目と第1列目の要素を設定します。 |
| [setMatrix12(float value)](#setMatrix12-float-) | この Aspose.Imaging.ColorMatrix の第1行目と第2列目の要素を設定します。 |
| [setMatrix13(float value)](#setMatrix13-float-) | この Aspose.Imaging.ColorMatrix の第1行目と第3列目の要素を設定します。 |
| [setMatrix14(float value)](#setMatrix14-float-) | この Aspose.Imaging.ColorMatrix の第1行目と第4列目の要素を設定します。 |
| [setMatrix20(float value)](#setMatrix20-float-) | この Aspose.Imaging.ColorMatrix の第2行目と0（ゼロ）列目の要素を設定します。 |
| [setMatrix21(float value)](#setMatrix21-float-) | この Aspose.Imaging.ColorMatrix の第2行目と第1列目の要素を設定します。 |
| [setMatrix22(float value)](#setMatrix22-float-) | この Aspose.Imaging.ColorMatrix の第2行目と第2列目の要素を設定します。 |
| [setMatrix23(float value)](#setMatrix23-float-) | この Aspose.Imaging.ColorMatrix の第2行目と第3列目の要素を設定します。 |
| [setMatrix24(float value)](#setMatrix24-float-) | この Aspose.Imaging.ColorMatrix の第2行目と第4列目の要素を設定します。 |
| [setMatrix30(float value)](#setMatrix30-float-) | この Aspose.Imaging.ColorMatrix の第3行目と0（ゼロ）列目の要素を設定します。 |
| [setMatrix31(float value)](#setMatrix31-float-) | この Aspose.Imaging.ColorMatrix の第3行目と第1列目の要素を設定します。 |
| [setMatrix32(float value)](#setMatrix32-float-) | この Aspose.Imaging.ColorMatrix の第3行目と第2列目の要素を設定します。 |
| [setMatrix33(float value)](#setMatrix33-float-) | この Aspose.Imaging.ColorMatrix の第3行目と第3列目の要素を設定します。 |
| [setMatrix34(float value)](#setMatrix34-float-) | この Aspose.Imaging.ColorMatrix の3行目4列目の要素を設定します。 |
| [setMatrix40(float value)](#setMatrix40-float-) | この Aspose.Imaging.ColorMatrix の4行目0列目（ゼロ）の要素を設定します。 |
| [setMatrix41(float value)](#setMatrix41-float-) | この Aspose.Imaging.ColorMatrix の4行目1列目の要素を設定します。 |
| [setMatrix42(float value)](#setMatrix42-float-) | この Aspose.Imaging.ColorMatrix の4行目2列目の要素を設定します。 |
| [setMatrix43(float value)](#setMatrix43-float-) | この Aspose.Imaging.ColorMatrix の4行目3列目の要素を設定します。 |
| [setMatrix44(float value)](#setMatrix44-float-) | この Aspose.Imaging.ColorMatrix の4行目4列目の要素を設定します。 |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Aspose.Imaging.ColorMatrix の指定された行と列の要素を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Aspose.Imaging.ColorMatrix クラスの新しいインスタンスを初期化します。

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


指定された行列 newColorMatrix の要素を使用して、Aspose.Imaging.ColorMatrix クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | float[][] | 新しい Aspose.Imaging.ColorMatrix の要素の値です。 |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


行列次元の要素数です。

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


行列の次元数です。

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


行列の要素総数です。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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


行列の値を取得します。

**Returns:**
float[][] - 行列の値配列です。
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と 0 列目の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の0行目0列目の要素です。
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と最初の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の0行目1列目の要素です。
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と2番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の0行目2列目の要素です。
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と3番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の0行目3列目の要素です。
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


この  Aspose.Imaging.ColorMatrix の 0 行目（ゼロ）と4番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の0行目4列目の要素です。
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


この  Aspose.Imaging.ColorMatrix の最初の行と 0 列目（ゼロ）の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の1行目0列目の要素です。
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


この  Aspose.Imaging.ColorMatrix の最初の行と最初の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の1行目1列目の要素です。
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


この  Aspose.Imaging.ColorMatrix の最初の行と2番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の1行目2列目の要素です。
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


この  Aspose.Imaging.ColorMatrix の最初の行と3番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の1行目3列目の要素です。
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


この  Aspose.Imaging.ColorMatrix の最初の行と4番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の1行目4列目の要素です。
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


この  Aspose.Imaging.ColorMatrix の2番目の行と 0 列目（ゼロ）の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の2行目0列目の要素です。
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


この  Aspose.Imaging.ColorMatrix の2番目の行と最初の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の2行目1列目の要素です。
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


この  Aspose.Imaging.ColorMatrix の2番目の行と2番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の2行目2列目の要素です。
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


この  Aspose.Imaging.ColorMatrix の2番目の行と3番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の2行目3列目の要素です。
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


この  Aspose.Imaging.ColorMatrix の2番目の行と4番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第2行第4列の要素。
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


この  Aspose.Imaging.ColorMatrix の3番目の行と 0 列目（ゼロ）の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第3行第0列の要素。
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


この  Aspose.Imaging.ColorMatrix の3番目の行と最初の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第3行第1列の要素。
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


この  Aspose.Imaging.ColorMatrix の3番目の行と2番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第3行第2列の要素。
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


この  Aspose.Imaging.ColorMatrix の3番目の行と3番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第3行第3列の要素。
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


この  Aspose.Imaging.ColorMatrix の3番目の行と4番目の列の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第3行第4列の要素。
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


この Aspose.Imaging.ColorMatrix の第4行目と0（ゼロ）列目の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第4行第0列の要素。
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


この Aspose.Imaging.ColorMatrix の第4行目と第1列目の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第4行第1列の要素。
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


この Aspose.Imaging.ColorMatrix の第4行目と第2列目の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第4行第2列の要素。
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


この Aspose.Imaging.ColorMatrix の第4行目と第3列目の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第4行第3列の要素。
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


この Aspose.Imaging.ColorMatrix の第4行目と第4列目の要素を取得します。

**Returns:**
float - この Aspose.Imaging.ColorMatrix の第4行第4列の要素。
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Aspose.Imaging.ColorMatrix の指定された行と列の要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 行 | int | 行番号です。 |
| 列 | int | 列番号です。 |

**Returns:**
float - 指定された行と列の要素。
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


この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と0列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第0行第0列の要素。 |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と第1列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第0行第1列の要素。 |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と第2列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第0行第2列の要素。 |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と第3列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第0行第3列の要素。 |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


この Aspose.Imaging.ColorMatrix の0（ゼロ）行目と第4列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第0行第4列の要素。 |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


この Aspose.Imaging.ColorMatrix の第1行目と0（ゼロ）列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第1行第0列の要素。 |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


この Aspose.Imaging.ColorMatrix の第1行目と第1列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第1行第1列の要素。 |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


この Aspose.Imaging.ColorMatrix の第1行目と第2列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第1行第2列の要素。 |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


この Aspose.Imaging.ColorMatrix の第1行目と第3列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第1行第3列の要素。 |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


この Aspose.Imaging.ColorMatrix の第1行目と第4列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第1行第4列の要素。 |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


この Aspose.Imaging.ColorMatrix の第2行目と0（ゼロ）列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第2行0列の要素。 |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


この Aspose.Imaging.ColorMatrix の第2行目と第1列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第2行第1列の要素。 |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


この Aspose.Imaging.ColorMatrix の第2行目と第2列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第2行第2列の要素。 |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


この Aspose.Imaging.ColorMatrix の第2行目と第3列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第2行第3列の要素。 |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


この Aspose.Imaging.ColorMatrix の第2行目と第4列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第2行第4列の要素。 |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


この Aspose.Imaging.ColorMatrix の第3行目と0（ゼロ）列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第3行0列の要素。 |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


この Aspose.Imaging.ColorMatrix の第3行目と第1列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第3行第1列の要素。 |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


この Aspose.Imaging.ColorMatrix の第3行目と第2列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第3行第2列の要素。 |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


この Aspose.Imaging.ColorMatrix の第3行目と第3列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第3行第3列の要素。 |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


この Aspose.Imaging.ColorMatrix の3行目4列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第3行第4列の要素。 |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


この Aspose.Imaging.ColorMatrix の4行目0列目（ゼロ）の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第4行0列の要素。 |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


この Aspose.Imaging.ColorMatrix の4行目1列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第4行第1列の要素。 |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


この Aspose.Imaging.ColorMatrix の4行目2列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第4行第2列の要素。 |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


この Aspose.Imaging.ColorMatrix の4行目3列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第4行第3列の要素。 |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


この Aspose.Imaging.ColorMatrix の4行目4列目の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Aspose.Imaging.ColorMatrix の第4行第4列の要素。 |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Aspose.Imaging.ColorMatrix の指定された行と列の要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 行 | int | 行番号です。 |
| 列 | int | 列番号です。 |
| 値 | float | 値 |

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

