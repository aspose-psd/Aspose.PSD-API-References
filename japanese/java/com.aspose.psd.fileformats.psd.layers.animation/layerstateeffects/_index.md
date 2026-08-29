---
title: "LayerStateEffects"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "レイヤー状態のエフェクト。"
type: docs
weight: 13
url: /ja/java/com.aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Inheritance:**
java.lang.Object
```
public class LayerStateEffects
```

レイヤー状態のエフェクト。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addColorOverlay()](#addColorOverlay--) | カラーオーバーレイ効果を追加します。 |
| [addDropShadow()](#addDropShadow--) | ドロップシャドウ効果を追加します。 |
| [addGradientOverlay()](#addGradientOverlay--) | グラデーションオーバーレイ効果を追加します。 |
| [addInnerShadow()](#addInnerShadow--) | インナーシャドウ効果を追加します。 |
| [addOuterGlow()](#addOuterGlow--) | 外側のグロー効果を追加します。 |
| [addPatternOverlay()](#addPatternOverlay--) | パターンオーバーレイ効果を追加します。 |
| [addStroke(int fillType)](#addStroke-int-) | ストローク効果を追加します。 |
| [clearLayerStyle()](#clearLayerStyle--) | すべてのレイヤースタイル効果をクリアします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEffects()](#getEffects--) | レイヤー効果を取得します。 |
| [getLayerStyleFX()](#getLayerStyleFX--) | レイヤースタイル効果モデルを取得または設定します。 |
| [getScale()](#getScale--) | スケール値を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeEffectAt(int index)](#removeEffectAt-int-) | 特定のインデックスにあるレイヤー効果を削除します。 |
| [setLayerStyleFX_internalized(LayerStyleFX value)](#setLayerStyleFX-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | レイヤースタイル効果モデルを取得または設定します。 |
| [setLayerStyle_internalized(LayerStyleFX layerStyle)](#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | レイヤースタイルを設定し、効果リストを更新します。 |
| [setScale(double value)](#setScale-double-) | スケール値を取得または設定します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addColorOverlay() {#addColorOverlay--}
```
public final ColorOverlayEffect addColorOverlay()
```


カラーオーバーレイ効果を追加します。

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) - The new instance of the [ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) class.
### addDropShadow() {#addDropShadow--}
```
public final DropShadowEffect addDropShadow()
```


ドロップシャドウ効果を追加します。

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) - The new instance of the [DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) class.
### addGradientOverlay() {#addGradientOverlay--}
```
public final GradientOverlayEffect addGradientOverlay()
```


グラデーションオーバーレイ効果を追加します。

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) - The new instance of the [GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) class.
### addInnerShadow() {#addInnerShadow--}
```
public final InnerShadowEffect addInnerShadow()
```


インナーシャドウ効果を追加します。

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) - The new instance of the [InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) class.
### addOuterGlow() {#addOuterGlow--}
```
public final OuterGlowEffect addOuterGlow()
```


外側のグロー効果を追加します。

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) - The new instance of the [OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) class.
### addPatternOverlay() {#addPatternOverlay--}
```
public final PatternOverlayEffect addPatternOverlay()
```


パターンオーバーレイ効果を追加します。

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) - The new instance of the [PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) class.
### addStroke(int fillType) {#addStroke-int-}
```
public final StrokeEffect addStroke(int fillType)
```


ストローク効果を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillType | int | ストローク塗りのタイプです。 |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) - The new instance of the [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) class.
### clearLayerStyle() {#clearLayerStyle--}
```
public final void clearLayerStyle()
```


すべてのレイヤースタイル効果をクリアします。

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
### getEffects() {#getEffects--}
```
public final ILayerEffect[] getEffects()
```


レイヤー効果を取得します。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect[]
### getLayerStyleFX() {#getLayerStyleFX--}
```
public final LayerStyleFX getLayerStyleFX()
```


レイヤースタイル効果モデルを取得または設定します。

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX
### getScale() {#getScale--}
```
public final double getScale()
```


スケール値を取得または設定します。

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


このインスタンスが表示されているかどうかを示す値を取得または設定します。

Value:  true  このインスタンスが表示されている場合; それ以外の場合は  false .

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




### removeEffectAt(int index) {#removeEffectAt-int-}
```
public final void removeEffectAt(int index)
```


特定のインデックスにあるレイヤー効果を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | レイヤー効果のインデックスです。 |

### setLayerStyleFX_internalized(LayerStyleFX value) {#setLayerStyleFX-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyleFX_internalized(LayerStyleFX value)
```


レイヤースタイル効果モデルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX |  |

### setLayerStyle_internalized(LayerStyleFX layerStyle) {#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyle_internalized(LayerStyleFX layerStyle)
```


レイヤースタイルを設定し、効果リストを更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX | レイヤースタイルです。 |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


スケール値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


このインスタンスが表示されているかどうかを示す値を取得または設定します。

Value:  true  このインスタンスが表示されている場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

