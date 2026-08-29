---
title: "HatchStyle"
second_title: "Aspose.PSD 的 Java API 参考"
description: "指定 HatchBrush 对象可用的不同图案。"
type: docs
weight: 52
url: /zh/java/com.aspose.psd/hatchstyle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

指定 HatchBrush 对象可用的不同图案。
## 字段

| 字段 | 描述 |
| --- | --- |
| [BackwardDiagonal](#BackwardDiagonal) | 从右上角到左下角的对角线图案。 |
| [Cross](#Cross) | 指定交叉的水平线和垂直线。 |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | 指定从顶部点到底部点向右倾斜的对角线，这些线的间距比 ForwardDiagonal 小 50%，且宽度是其两倍。 |
| [DarkHorizontal](#DarkHorizontal) | 指定水平线，其间距比 Horizontal 小 50%，且宽度是 Horizontal 的两倍。 |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | 指定从顶部点到底部点向左倾斜的对角线，这些线的间距比 BackwardDiagonal 小 50%，宽度是其两倍，但线条未进行抗锯齿处理。 |
| [DarkVertical](#DarkVertical) | 指定垂直线，其间距比 Vertical 小 50%，且宽度是其两倍。 |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | 指定从顶部点到底部点向右倾斜的虚线对角线。 |
| [DashedHorizontal](#DashedHorizontal) | 指定虚线水平线。 |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | 指定从顶部点到底部点向左倾斜的虚线对角线。 |
| [DashedVertical](#DashedVertical) | 指定虚线垂直线。 |
| [DiagonalBrick](#DiagonalBrick) | 指定一种填充图案，其外观为从上到下向左倾斜的层叠砖块。 |
| [DiagonalCross](#DiagonalCross) | 交叉对角线的图案。 |
| [Divot](#Divot) | 指定一种外观为凹痕的填充图案。 |
| [DottedDiamond](#DottedDiamond) | 指定由点组成的前向对角线和后向对角线交叉。 |
| [DottedGrid](#DottedGrid) | 指定由点组成的水平线和垂直线交叉。 |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ForwardDiagonal](#ForwardDiagonal) | 从左上到右下的对角线图案。 |
| [Horizontal](#Horizontal) | 水平线的图案。 |
| [HorizontalBrick](#HorizontalBrick) | 指定一种外观为水平层叠砖块的填充图案。 |
| [LargeCheckerBoard](#LargeCheckerBoard) | 指定一种外观为棋盘格的填充图案，其方块大小是 SmallCheckerBoard 的两倍。 |
| [LargeConfetti](#LargeConfetti) | 指定一种外观为五彩纸屑的填充图案，其碎片比 SmallConfetti 更大。 |
| [LargeGrid](#LargeGrid) | 指定填充样式 Cross。 |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | 指定从上到下向右倾斜的对角线，其间距比 ForwardDiagonal 小 50%，且未进行抗锯齿处理。 |
| [LightHorizontal](#LightHorizontal) | 指定水平线，其间距比 Horizontal 小 50%。 |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | 指定从上到下向左倾斜的对角线，其间距比 BackwardDiagonal 小 50%，且未进行抗锯齿处理。 |
| [LightVertical](#LightVertical) | 指定垂直线，其间距比 Vertical 小 50%。 |
| [Max](#Max) | 指定填充样式 SolidDiamond。 |
| [Min](#Min) | 指定填充样式 Horizontal。 |
| [NarrowHorizontal](#NarrowHorizontal) | 指定水平线，其间距比填充样式 Horizontal 小 75%（或比 LightHorizontal 小 25%）。 |
| [NarrowVertical](#NarrowVertical) | 指定垂直线，其间距比填充样式 Vertical 小 75%（或比 LightVertical 小 25%）。 |
| [OutlinedDiamond](#OutlinedDiamond) | 指定交叉的前向对角线和后向对角线，但未进行抗锯齿处理。 |
| [Percent05](#Percent05) | 指定 5% 的填充。 |
| [Percent10](#Percent10) | 指定 10% 的填充。 |
| [Percent20](#Percent20) | 指定 20% 的填充。 |
| [Percent25](#Percent25) | 指定 25% 的填充。 |
| [Percent30](#Percent30) | 指定 30% 的填充。 |
| [Percent40](#Percent40) | 指定 40% 的填充。 |
| [Percent50](#Percent50) | 指定 50% 的填充。 |
| [Percent60](#Percent60) | 指定 60% 的填充。 |
| [Percent70](#Percent70) | 指定 70% 的填充。 |
| [Percent75](#Percent75) | 指定 75% 的填充。 |
| [Percent80](#Percent80) | 指定 80% 的填充。 |
| [Percent90](#Percent90) | 指定 90% 的填充。 |
| [Plaid](#Plaid) | 指定一种外观类似格子材料的填充。 |
| [Shingle](#Shingle) | 指定一种外观为对角层叠瓦片、从上点向下点向右倾斜的填充。 |
| [SmallCheckerBoard](#SmallCheckerBoard) | 指定一种外观为棋盘格的填充。 |
| [SmallConfetti](#SmallConfetti) | 指定一种外观为五彩纸屑的填充。 |
| [SmallGrid](#SmallGrid) | 指定水平和垂直交叉的线条，其间距比填充样式 Cross 小 50%。 |
| [SolidDiamond](#SolidDiamond) | 指定一种外观为对角放置的棋盘格的填充。 |
| [Sphere](#Sphere) | 指定一种外观为相邻球体排列的填充。 |
| [Trellis](#Trellis) | 指定一种外观为格子架的填充。 |
| [Vertical](#Vertical) | 垂直线条的图案。 |
| [Wave](#Wave) | 指定由波浪线组成的水平线。 |
| [Weave](#Weave) | 指定一种外观为编织材料的填充。 |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | 指定从上点向下点向右倾斜的对角线，其间距与填充样式 ForwardDiagonal 相同，宽度为其三倍，但不进行抗锯齿处理。 |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | 指定从上点向下点向左倾斜的对角线，其间距与填充样式 BackwardDiagonal 相同，宽度为其三倍，但不进行抗锯齿处理。 |
| [ZigZag](#ZigZag) | 指定由锯齿线组成的水平线。 |
## Methods

| Method | 描述 |
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


从右上角到左下角的对角线图案。

### Cross {#Cross}
```
public static final int Cross
```


指定交叉的水平线和垂直线。

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


指定从上点向下点向右倾斜的对角线，其间距比 ForwardDiagonal 小 50%，宽度为其两倍。此填充图案不进行抗锯齿处理。

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


指定水平线，其间距比 Horizontal 小 50%，且宽度是 Horizontal 的两倍。

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


指定从顶部点到底部点向左倾斜的对角线，这些线的间距比 BackwardDiagonal 小 50%，宽度是其两倍，但线条未进行抗锯齿处理。

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


指定垂直线，其间距比 Vertical 小 50%，且宽度是其两倍。

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


指定从顶部点到底部点向右倾斜的虚线对角线。

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


指定虚线水平线。

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


指定从顶部点到底部点向左倾斜的虚线对角线。

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


指定虚线垂直线。

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


指定一种填充图案，其外观为从上到下向左倾斜的层叠砖块。

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


交叉对角线的图案。

### Divot {#Divot}
```
public static final int Divot
```


指定一种外观为凹痕的填充图案。

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


指定由点组成的前向对角线和后向对角线交叉。

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


指定由点组成的水平线和垂直线交叉。

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


从左上到右下的对角线图案。

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


水平线的图案。

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


指定一种外观为水平层叠砖块的填充图案。

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


指定一种外观为棋盘格的填充图案，其方块大小是 SmallCheckerBoard 的两倍。

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


指定一种外观为五彩纸屑的填充图案，其碎片比 SmallConfetti 更大。

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


指定填充样式 Cross。

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


指定从上到下向右倾斜的对角线，其间距比 ForwardDiagonal 小 50%，且未进行抗锯齿处理。

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


指定水平线，其间距比 Horizontal 小 50%。

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


指定从上到下向左倾斜的对角线，其间距比 BackwardDiagonal 小 50%，且未进行抗锯齿处理。

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


指定垂直线，其间距比 Vertical 小 50%。

### Max {#Max}
```
public static final int Max
```


指定填充样式 SolidDiamond。

### Min {#Min}
```
public static final int Min
```


指定填充样式 Horizontal。

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


指定水平线，其间距比填充样式 Horizontal 小 75%（或比 LightHorizontal 小 25%）。

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


指定垂直线，其间距比填充样式 Vertical 小 75%（或比 LightVertical 小 25%）。

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


指定交叉的前向对角线和后向对角线，但未进行抗锯齿处理。

### Percent05 {#Percent05}
```
public static final int Percent05
```


指定 5% 的填充。前景色与背景色的比例为 5:95。

### Percent10 {#Percent10}
```
public static final int Percent10
```


指定 10% 的填充。前景色与背景色的比例为 10:90。

### Percent20 {#Percent20}
```
public static final int Percent20
```


指定 20% 的填充。前景色与背景色的比例为 20:80。

### Percent25 {#Percent25}
```
public static final int Percent25
```


指定 25% 的填充。前景色与背景色的比例为 25:75。

### Percent30 {#Percent30}
```
public static final int Percent30
```


指定 30% 的填充。前景色与背景色的比例为 30:70。

### Percent40 {#Percent40}
```
public static final int Percent40
```


指定 40% 的填充。前景色与背景色的比例为 40:60。

### Percent50 {#Percent50}
```
public static final int Percent50
```


指定 50% 的填充。前景色与背景色的比例为 50:50。

### Percent60 {#Percent60}
```
public static final int Percent60
```


指定 60% 的填充。前景色与背景色的比例为 60:40。

### Percent70 {#Percent70}
```
public static final int Percent70
```


指定 70% 的填充。前景色与背景色的比例为 70:30。

### Percent75 {#Percent75}
```
public static final int Percent75
```


指定 75% 的填充。前景色与背景色的比例为 75:25。

### Percent80 {#Percent80}
```
public static final int Percent80
```


指定 80% 的填充。前景色与背景色的比例为 80:100。

### Percent90 {#Percent90}
```
public static final int Percent90
```


指定 90% 的填充。前景色与背景色的比例为 90:10。

### Plaid {#Plaid}
```
public static final int Plaid
```


指定一种外观类似格子材料的填充。

### Shingle {#Shingle}
```
public static final int Shingle
```


指定一种外观为对角层叠瓦片、从上点向下点向右倾斜的填充。

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


指定一种外观为棋盘格的填充。

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


指定一种外观为五彩纸屑的填充。

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


指定水平和垂直交叉的线条，其间距比填充样式 Cross 小 50%。

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


指定一种外观为对角放置的棋盘格的填充。

### Sphere {#Sphere}
```
public static final int Sphere
```


指定一种外观为相邻球体排列的填充。

### Trellis {#Trellis}
```
public static final int Trellis
```


指定一种外观为格子架的填充。

### Vertical {#Vertical}
```
public static final int Vertical
```


垂直线条的图案。

### Wave {#Wave}
```
public static final int Wave
```


指定由波浪线组成的水平线。

### Weave {#Weave}
```
public static final int Weave
```


指定一种外观为编织材料的填充。

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


指定从上点向下点向右倾斜的对角线，其间距与填充样式 ForwardDiagonal 相同，宽度为其三倍，但不进行抗锯齿处理。

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


指定从上点向下点向左倾斜的对角线，其间距与填充样式 BackwardDiagonal 相同，宽度为其三倍，但不进行抗锯齿处理。

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


指定由锯齿线组成的水平线。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

