---
title: "PatternFillSettings"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "パターン塗り効果設定"
type: docs
weight: 20
url: /ja/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

パターン塗り効果設定
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | 新しい [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) クラスのインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | LFX2 リソースノードを生成します。 |
| [getAlignWithLayer()](#getAlignWithLayer--) | この [link with layer] があるかどうかを示す値を取得または設定します。 |
| [getAngle()](#getAngle--) | 角度を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 色を取得または設定します。 |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | 塗りタイプ |
| [getHorizontalOffset()](#getHorizontalOffset--) | 水平オフセットを取得または設定します。 |
| [getLinked()](#getLinked--) | この [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) がリンクされているかどうかを示す値を取得または設定します。 |
| [getPatternData()](#getPatternData--) | パターンデータを取得または設定します。 |
| [getPatternHeight()](#getPatternHeight--) | パターンの高さを取得または設定します。 |
| [getPatternId()](#getPatternId--) | パターン識別子を取得または設定します。 |
| [getPatternName()](#getPatternName--) | パターンの名前を取得または設定します。 |
| [getPatternWidth()](#getPatternWidth--) | パターンの幅を取得または設定します。 |
| [getPhase_internalized()](#getPhase-internalized--) | 位相を取得または設定します。 |
| [getPointType()](#getPointType--) | ポイントのタイプを取得または設定します。 |
| [getScale()](#getScale--) | スケールを取得または設定します。 |
| [getVerticalOffset()](#getVerticalOffset--) | 垂直オフセットを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 値が変更されたことを通知します。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | この [link with layer] があるかどうかを示す値を取得または設定します。 |
| [setAngle(double value)](#setAngle-double-) | 角度を取得または設定します。 |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 色を取得または設定します。 |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | 水平オフセットを取得または設定します。 |
| [setLinked(boolean value)](#setLinked-boolean-) | この [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) がリンクされているかどうかを示す値を取得または設定します。 |
| [setPatternData(int[] value)](#setPatternData-int---) | パターンデータを取得または設定します。 |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | 保存時に使用する圧縮モードとパターン\u2019s ピクセルバッファを設定します。 |
| [setPatternHeight(int value)](#setPatternHeight-int-) | パターンの高さを取得または設定します。 |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | パターン識別子を取得または設定します。 |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | パターンの名前を取得または設定します。 |
| [setPatternWidth(int value)](#setPatternWidth-int-) | パターンの幅を取得または設定します。 |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | 位相を取得または設定します。 |
| [setPointType(String value)](#setPointType-java.lang.String-) | ポイントのタイプを取得または設定します。 |
| [setScale(double value)](#setScale-double-) | スケールを取得または設定します。 |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | 垂直オフセットを取得または設定します。 |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | パターンのデフォルトデータを [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) インスタンスに設定します。 |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) インスタンスからパターンプロパティを更新します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


新しい [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) クラスのインスタンスを初期化します。

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


LFX2 リソースノードを生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pointType | java.lang.String | ポイントのタイプ。 |
| color | [Color](../../com.aspose.psd/color) | 色。 |
| patternName | java.lang.String | パターンの名前。 |
| identifier | java.lang.String | 識別子。 |
| スケール | double | スケール。 |
| linked | boolean | true に設定された場合は [linked]。 |
| offset | [PointF](../../com.aspose.psd/pointf) | オフセット。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) のリスト
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


この [link with layer] があるかどうかを示す値を取得または設定します。

値: true の場合は [link with layer]、それ以外の場合は false。

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


角度を取得または設定します。

値: 角度です。

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


色を取得または設定します。

値: 色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getCompressionModeOnSave_internalized() {#getCompressionModeOnSave-internalized--}
```
public final byte getCompressionModeOnSave_internalized()
```




**Returns:**
byte
### getFillType() {#getFillType--}
```
public int getFillType()
```


塗りタイプ

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


水平オフセットを取得または設定します。

値: 水平オフセット。

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


この [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) がリンクされているかどうかを示す値を取得または設定します。

値: linked の場合は true、そうでない場合は false。

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


パターンデータを取得または設定します。

値: パターン データ。

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


パターンの高さを取得または設定します。

値: パターンの高さ。

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


パターン識別子を取得または設定します。

値: パターン識別子。

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


パターンの名前を取得または設定します。

値: パターンの名前。

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


パターンの幅を取得または設定します。

値: パターンの幅。

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


位相を取得または設定します。

値: 位相。

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


ポイントのタイプを取得または設定します。

値: 点の種類。

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


スケールを取得または設定します。

値: スケール。

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


垂直オフセットを取得または設定します。

値: 垂直オフセット。

**Returns:**
int
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


値が変更されたことを通知します。

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


この [link with layer] があるかどうかを示す値を取得または設定します。

値: true の場合は [link with layer]、それ以外の場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


角度を取得または設定します。

値: 角度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


色を取得または設定します。

値: 色。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


水平オフセットを取得または設定します。

値: 水平オフセット。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


この [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) がリンクされているかどうかを示す値を取得または設定します。

値: linked の場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


パターンデータを取得または設定します。

値: パターン データ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


保存時に使用する圧縮モードとパターン\u2019s ピクセルバッファを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| patternData | int[] | 0xAARRGGBB 形式の 32 ビットピクセル。 |
| compressionModeOnSave | byte | psd ファイル保存時にパターン データの圧縮を定義するために使用される圧縮モード。 |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


パターンの高さを取得または設定します。

値: パターンの高さ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


パターン識別子を取得または設定します。

値: パターン識別子。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


パターンの名前を取得または設定します。

値: パターンの名前。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


パターンの幅を取得または設定します。

値: パターンの幅。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


位相を取得または設定します。

値: 位相。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


ポイントのタイプを取得または設定します。

値: 点の種類。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


スケールを取得または設定します。

値: スケール。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


垂直オフセットを取得または設定します。

値: 垂直オフセット。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


パターンのデフォルトデータを [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) インスタンスに設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | パターン塗り設定です。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePatternData_internalized(PattResourceData pattResourceData) {#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-}
```
public final void updatePatternData_internalized(PattResourceData pattResourceData)
```


[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) インスタンスからパターンプロパティを更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | パターン データを含む [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) インスタンス。 |

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

