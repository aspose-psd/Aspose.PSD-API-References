---
title: "HatchStyle"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "HatchBrush オブジェクトで利用可能なさまざまなパターンを指定します。"
type: docs
weight: 52
url: /ja/java/com.aspose.psd/hatchstyle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

HatchBrush オブジェクトで利用可能なさまざまなパターンを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [BackwardDiagonal](#BackwardDiagonal) | 右上から左下へ斜めに走る線のパターンです。 |
| [Cross](#Cross) | 水平線と垂直線が交差することを指定します。 |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | ForwardDiagonal より 50% 間隔が狭く、幅が 2 倍の、上部から下部へ右方向に傾く斜線を指定します。 |
| [DarkHorizontal](#DarkHorizontal) | Horizontal より 50% 間隔が狭く、幅が 2 倍の水平線を指定します。 |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | BackwardDiagonal より 50% 間隔が狭く、幅が 2 倍で、上部から下部へ左方向に傾く斜線を指定しますが、線はアンチエイリアスされません。 |
| [DarkVertical](#DarkVertical) | Vertical より 50% 間隔が狭く、幅が 2 倍の垂直線を指定します。 |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | 上部から下部へ右方向に傾く破線の斜線を指定します。 |
| [DashedHorizontal](#DashedHorizontal) | 破線の水平線を指定します。 |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | 上部から下部へ左方向に傾く破線の斜線を指定します。 |
| [DashedVertical](#DashedVertical) | 破線の垂直線を指定します。 |
| [DiagonalBrick](#DiagonalBrick) | 上部から下部へ左方向に傾く、層状のレンガの外観を持つハッチを指定します。 |
| [DiagonalCross](#DiagonalCross) | 交差する斜線のパターンです。 |
| [Divot](#Divot) | へこみの外観を持つハッチを指定します。 |
| [DottedDiamond](#DottedDiamond) | 前方斜線と後方斜線を、各々ドットで構成された交差する線として指定します。 |
| [DottedGrid](#DottedGrid) | 水平線と垂直線を、各々ドットで構成された交差する線として指定します。 |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ForwardDiagonal](#ForwardDiagonal) | 左上から右下へ斜めに走る線のパターンです。 |
| [Horizontal](#Horizontal) | 水平線のパターンです。 |
| [HorizontalBrick](#HorizontalBrick) | 水平に層状のレンガの外観を持つハッチを指定します。 |
| [LargeCheckerBoard](#LargeCheckerBoard) | SmallCheckerBoard の 2 倍のサイズの正方形を持つチェッカーボードの外観を持つハッチを指定します。 |
| [LargeConfetti](#LargeConfetti) | SmallConfetti より大きなピースで構成された、紙吹雪の外観を持つハッチを指定します。 |
| [LargeGrid](#LargeGrid) | ハッチスタイル Cross を指定します。 |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | ForwardDiagonal より 50% 間隔が狭く、上部から下部へ右方向に傾く斜線を指定しますが、アンチエイリアスされません。 |
| [LightHorizontal](#LightHorizontal) | Horizontal より 50% 間隔が狭い水平線を指定します。 |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | BackwardDiagonal より 50% 間隔が狭く、上部から下部へ左方向に傾く斜線を指定しますが、アンチエイリアスされません。 |
| [LightVertical](#LightVertical) | Vertical より 50 パーセント間隔が狭い垂直線を指定します。 |
| [Max](#Max) | ハッチスタイル SolidDiamond を指定します。 |
| [Min](#Min) | ハッチスタイル Horizontal を指定します。 |
| [NarrowHorizontal](#NarrowHorizontal) | ハッチスタイル Horizontal より 75 パーセント間隔が狭い水平線を指定します（または LightHorizontal より 25 パーセント間隔が狭い）。 |
| [NarrowVertical](#NarrowVertical) | ハッチスタイル Vertical より 75 パーセント間隔が狭い垂直線を指定します（または LightVertical より 25 パーセント間隔が狭い）。 |
| [OutlinedDiamond](#OutlinedDiamond) | 前方対角線と後方対角線が交差するが、アンチエイリアスが適用されていないことを指定します。 |
| [Percent05](#Percent05) | 5 パーセントのハッチを指定します。 |
| [Percent10](#Percent10) | 10 パーセントのハッチを指定します。 |
| [Percent20](#Percent20) | 20 パーセントのハッチを指定します。 |
| [Percent25](#Percent25) | 25 パーセントのハッチを指定します。 |
| [Percent30](#Percent30) | 30 パーセントのハッチを指定します。 |
| [Percent40](#Percent40) | 40 パーセントのハッチを指定します。 |
| [Percent50](#Percent50) | 50 パーセントのハッチを指定します。 |
| [Percent60](#Percent60) | 60 パーセントのハッチを指定します。 |
| [Percent70](#Percent70) | 70 パーセントのハッチを指定します。 |
| [Percent75](#Percent75) | 75 パーセントのハッチを指定します。 |
| [Percent80](#Percent80) | 80 パーセントのハッチを指定します。 |
| [Percent90](#Percent90) | 90 パーセントのハッチを指定します。 |
| [Plaid](#Plaid) | 格子模様の外観を持つハッチを指定します。 |
| [Shingle](#Shingle) | 上部から下部へ右方向に傾斜した、対角線状に層状のシングル（屋根瓦）外観を持つハッチを指定します。 |
| [SmallCheckerBoard](#SmallCheckerBoard) | チェッカーボードの外観を持つハッチを指定します。 |
| [SmallConfetti](#SmallConfetti) | 紙吹雪の外観を持つハッチを指定します。 |
| [SmallGrid](#SmallGrid) | ハッチスタイル Cross より 50 パーセント間隔が狭い、交差する水平線と垂直線を指定します。 |
| [SolidDiamond](#SolidDiamond) | 対角線上に配置されたチェッカーボードの外観を持つハッチを指定します。 |
| [Sphere](#Sphere) | 隣接して配置された球体の外観を持つハッチを指定します。 |
| [Trellis](#Trellis) | 格子状の外観を持つハッチを指定します。 |
| [Vertical](#Vertical) | 垂直線のパターンです。 |
| [Wave](#Wave) | チルダで構成された水平線を指定します。 |
| [Weave](#Weave) | 織物の外観を持つハッチを指定します。 |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | 上部から下部へ右方向に傾く対角線を指定します。間隔はハッチスタイル ForwardDiagonal と同じで、幅はその3倍ですが、アンチエイリアスは適用されません。 |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | 上部から下部へ左方向に傾く対角線を指定します。間隔はハッチスタイル BackwardDiagonal と同じで、幅はその3倍ですが、アンチエイリアスは適用されません。 |
| [ZigZag](#ZigZag) | ジグザグで構成された水平線を指定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames()](#getNames--) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues()](#getValues--) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [getValues(Class<?> arg0)](#getValues-java.lang.Class----) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, String arg1)](#isDefined-java.lang.Class----java.lang.String-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [toString(long arg0)](#toString-long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


右上から左下へ斜めに走る線のパターンです。

### Cross {#Cross}
```
public static final int Cross
```


水平線と垂直線が交差することを指定します。

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


上部から下部へ右方向に傾く対角線を指定します。間隔は ForwardDiagonal より 50% 近く、幅はその2倍です。このハッチパターンはアンチエイリアスが適用されません。

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Horizontal より 50% 間隔が狭く、幅が 2 倍の水平線を指定します。

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


BackwardDiagonal より 50% 間隔が狭く、幅が 2 倍で、上部から下部へ左方向に傾く斜線を指定しますが、線はアンチエイリアスされません。

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Vertical より 50% 間隔が狭く、幅が 2 倍の垂直線を指定します。

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


上部から下部へ右方向に傾く破線の斜線を指定します。

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


破線の水平線を指定します。

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


上部から下部へ左方向に傾く破線の斜線を指定します。

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


破線の垂直線を指定します。

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


上部から下部へ左方向に傾く、層状のレンガの外観を持つハッチを指定します。

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


交差する斜線のパターンです。

### Divot {#Divot}
```
public static final int Divot
```


へこみの外観を持つハッチを指定します。

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


前方斜線と後方斜線を、各々ドットで構成された交差する線として指定します。

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


水平線と垂直線を、各々ドットで構成された交差する線として指定します。

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


左上から右下へ斜めに走る線のパターンです。

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


水平線のパターンです。

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


水平に層状のレンガの外観を持つハッチを指定します。

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


SmallCheckerBoard の 2 倍のサイズの正方形を持つチェッカーボードの外観を持つハッチを指定します。

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


SmallConfetti より大きなピースで構成された、紙吹雪の外観を持つハッチを指定します。

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


ハッチスタイル Cross を指定します。

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


ForwardDiagonal より 50% 間隔が狭く、上部から下部へ右方向に傾く斜線を指定しますが、アンチエイリアスされません。

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Horizontal より 50% 間隔が狭い水平線を指定します。

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


BackwardDiagonal より 50% 間隔が狭く、上部から下部へ左方向に傾く斜線を指定しますが、アンチエイリアスされません。

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Vertical より 50 パーセント間隔が狭い垂直線を指定します。

### Max {#Max}
```
public static final int Max
```


ハッチスタイル SolidDiamond を指定します。

### Min {#Min}
```
public static final int Min
```


ハッチスタイル Horizontal を指定します。

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


ハッチスタイル Horizontal より 75 パーセント間隔が狭い水平線を指定します（または LightHorizontal より 25 パーセント間隔が狭い）。

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


ハッチスタイル Vertical より 75 パーセント間隔が狭い垂直線を指定します（または LightVertical より 25 パーセント間隔が狭い）。

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


前方対角線と後方対角線が交差するが、アンチエイリアスが適用されていないことを指定します。

### Percent05 {#Percent05}
```
public static final int Percent05
```


5% のハッチを指定します。前景色と背景色の比率は 5:95 です。

### Percent10 {#Percent10}
```
public static final int Percent10
```


10% のハッチを指定します。前景色と背景色の比率は 10:90 です。

### Percent20 {#Percent20}
```
public static final int Percent20
```


20% のハッチを指定します。前景色と背景色の比率は 20:80 です。

### Percent25 {#Percent25}
```
public static final int Percent25
```


25% のハッチを指定します。前景色と背景色の比率は 25:75 です。

### Percent30 {#Percent30}
```
public static final int Percent30
```


30% のハッチを指定します。前景色と背景色の比率は 30:70 です。

### Percent40 {#Percent40}
```
public static final int Percent40
```


40% のハッチを指定します。前景色と背景色の比率は 40:60 です。

### Percent50 {#Percent50}
```
public static final int Percent50
```


50% のハッチを指定します。前景色と背景色の比率は 50:50 です。

### Percent60 {#Percent60}
```
public static final int Percent60
```


60% のハッチを指定します。前景色と背景色の比率は 60:40 です。

### Percent70 {#Percent70}
```
public static final int Percent70
```


70% のハッチを指定します。前景色と背景色の比率は 70:30 です。

### Percent75 {#Percent75}
```
public static final int Percent75
```


75% のハッチを指定します。前景色と背景色の比率は 75:25 です。

### Percent80 {#Percent80}
```
public static final int Percent80
```


80% のハッチを指定します。前景色と背景色の比率は 80:100 です。

### Percent90 {#Percent90}
```
public static final int Percent90
```


90% のハッチを指定します。前景色と背景色の比率は 90:10 です。

### Plaid {#Plaid}
```
public static final int Plaid
```


格子模様の外観を持つハッチを指定します。

### Shingle {#Shingle}
```
public static final int Shingle
```


上部から下部へ右方向に傾斜した、対角線状に層状のシングル（屋根瓦）外観を持つハッチを指定します。

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


チェッカーボードの外観を持つハッチを指定します。

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


紙吹雪の外観を持つハッチを指定します。

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


ハッチスタイル Cross より 50 パーセント間隔が狭い、交差する水平線と垂直線を指定します。

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


対角線上に配置されたチェッカーボードの外観を持つハッチを指定します。

### Sphere {#Sphere}
```
public static final int Sphere
```


隣接して配置された球体の外観を持つハッチを指定します。

### Trellis {#Trellis}
```
public static final int Trellis
```


格子状の外観を持つハッチを指定します。

### Vertical {#Vertical}
```
public static final int Vertical
```


垂直線のパターンです。

### Wave {#Wave}
```
public static final int Wave
```


チルダで構成された水平線を指定します。

### Weave {#Weave}
```
public static final int Weave
```


織物の外観を持つハッチを指定します。

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


上部から下部へ右方向に傾く対角線を指定します。間隔はハッチスタイル ForwardDiagonal と同じで、幅はその3倍ですが、アンチエイリアスは適用されません。

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


上部から下部へ左方向に傾く対角線を指定します。間隔はハッチスタイル BackwardDiagonal と同じで、幅はその3倍ですが、アンチエイリアスは適用されません。

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


ジグザグで構成された水平線を指定します。

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

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
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames() {#getNames--}
```
public String[] getNames()
```




**Returns:**
java.lang.String[]
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues() {#getValues--}
```
public Long[] getValues()
```




**Returns:**
java.lang.Long[]
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Long[]
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, String arg1) {#isDefined-java.lang.Class----java.lang.String-}
```
public static boolean isDefined(Class<?> arg0, String arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### toString(long arg0) {#toString-long-}
```
public String toString(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

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

