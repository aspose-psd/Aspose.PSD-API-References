---
title: "Region"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "矩形とパスで構成されたグラフィック形状の内部を記述します。"
type: docs
weight: 90
url: /ja/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

矩形とパスで構成されたグラフィックシェイプの内部を記述します。このクラスは継承できません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Region()](#Region--) | 新しい T:Aspose.Imaging.Region を初期化します。 |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | 指定された T:Aspose.Imaging.RectangleF 構造体から新しい T:Aspose.Imaging.Region を初期化します。 |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | 指定された T:Aspose.Imaging.Rectangle 構造体から新しい T:Aspose.Imaging.Region を初期化します。 |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | 指定された T:Aspose.Imaging.GraphicsPath を使用して新しい T:Aspose.Imaging.Region を初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | この com.aspose.psd.Region を更新し、指定された com.aspose.psd.GraphicsPath のうち、この com.aspose.psd.region と交差しない部分を含めます。 |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | この com.aspose.psd.Region を更新し、指定された com.aspose.psd.Rectangle 構造体のうち、この com.aspose.psd.region と交差しない部分を含めます。 |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | この com.aspose.psd.Region を更新し、指定された com.aspose.psd.RectangleF 構造体のうち、この com.aspose.psd.region と交差しない部分を含めます。 |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | この com.aspose.psd.Region を更新し、指定された com.aspose.psd.Region のうち、この com.aspose.psd.region と交差しない部分を含めます。 |
| [deepClone()](#deepClone--) | この com.aspose.psd.region の正確なディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | この com.aspose.psd.Region を更新し、内部のうち、指定された com.aspose.psd.graphicsPath と交差しない部分だけを含めます。 |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | この com.aspose.psd.Region を更新し、内部のうち、指定された com.aspose.psd.Rectangle 構造体と交差しない部分だけを含めます。 |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | この com.aspose.psd.Region を更新し、内部のうち、指定された com.aspose.psd.RectangleF 構造体と交差しない部分だけを含めます。 |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | この com.aspose.psd.Region を更新し、内部のうち、指定された com.aspose.psd.region と交差しない部分だけを含めます。 |
| [getActions_internalized()](#getActions-internalized--) | リージョンのアクションを取得します。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | この com.aspose.psd.Region を更新し、指定された com.aspose.psd.graphicsPath との交差部分にします。 |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | この com.aspose.psd.Region を更新し、指定された com.aspose.psd.Rectangle 構造体との交差部分にします。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | この com.aspose.psd.Region を更新し、指定された com.aspose.psd.RectangleF 構造体との交差部分にします。 |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | この com.aspose.psd.Region を更新し、指定された com.aspose.psd.region との交差部分にします。 |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | 指定された描画サーフェス上で、この com.aspose.psd.Region の内部が空であるかどうかをテストします。 |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | 指定された描画サーフェス上で、指定された com.aspose.psd.Region がこの com.aspose.psd.Region と同一かどうかをテストします。 |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | 指定された描画サーフェス上で、この com.aspose.psd.Region の内部が無限であるかどうかをテストします。 |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | 指定された com.aspose.psd.Point 構造体がこの com.aspose.psd.region に含まれるかどうかをテストします。 |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | 指定された com.aspose.psd.graphics を使用して描画した場合、指定された com.aspose.psd.Point 構造体がこの com.aspose.psd.Region に含まれるかどうかをテストします。 |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | 指定された com.aspose.psd.PointF 構造体がこの com.aspose.psd.region に含まれるかどうかをテストします。 |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | 指定された com.aspose.psd.graphics を使用して描画した場合、指定された com.aspose.psd.PointF 構造体がこの com.aspose.psd.Region に含まれるかどうかをテストします。 |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | 指定された com.aspose.psd.Rectangle 構造体の任意の部分がこの com.aspose.psd.region に含まれるかどうかをテストします。 |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | 指定された com.aspose.psd.graphics を使用して描画した場合、指定された com.aspose.psd.Rectangle 構造体の任意の部分がこの com.aspose.psd.Region に含まれるかどうかをテストします。 |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | 指定された com.aspose.psd.RectangleF 構造体の任意の部分がこの com.aspose.psd.region に含まれるかどうかをテストします。 |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | 指定された com.aspose.psd.graphics を使用して描画した場合、指定された com.aspose.psd.RectangleF 構造体の任意の部分がこの com.aspose.psd.Region に含まれるかどうかをテストします。 |
| [isVisible(float x, float y)](#isVisible-float-float-) | 指定された点がこの  com.aspose.psd.region に含まれているかテストします。 |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | 指定された点が、指定された  com.aspose.psd.graphics を使用して描画されたこの  com.aspose.psd.Region に含まれているかテストします。 |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | 指定された矩形の任意の部分がこの  com.aspose.psd.region に含まれているかテストします。 |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | 指定された矩形の任意の部分が、指定された  com.aspose.psd.graphics を使用して描画されたこの  com.aspose.psd.Region に含まれているかテストします。 |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | 指定された点が、指定された  com.aspose.psd.Graphics オブジェクトを使用して描画されたこの  com.aspose.psd.Region オブジェクトに含まれているかテストします。 |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | 指定された矩形の任意の部分がこの  com.aspose.psd.region に含まれているかテストします。 |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | 指定された矩形の任意の部分が、指定された  com.aspose.psd.graphics を使用して描画されたこの  com.aspose.psd.Region に含まれているかテストします。 |
| [makeEmpty()](#makeEmpty--) | この  com.aspose.psd.Region を空の内部に初期化します。 |
| [makeInfinite()](#makeInfinite--) | この  com.aspose.psd.Region オブジェクトを無限の内部に初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | 変更時の領域を取得または設定します。 |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | 指定された  com.aspose.psd.matrix によってこの  com.aspose.psd.Region を変換します。 |
| [translate(float dx, float dy)](#translate-float-float-) | 指定された量だけこの  com.aspose.psd.Region の座標をオフセットします。 |
| [translate(int dx, int dy)](#translate-int-int-) | 指定された量だけこの  com.aspose.psd.Region の座標をオフセットします。 |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.graphicsPath の合併に更新します。 |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.Rectangle 構造体の合併に更新します。 |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.RectangleF 構造体の合併に更新します。 |
| [union(Region region)](#union-com.aspose.psd.Region-) | この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.region の合併に更新します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.graphicsPath の交差部分を除いた合併に更新します。 |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.Rectangle 構造体の交差部分を除いた合併に更新します。 |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.RectangleF 構造体の交差部分を除いた合併に更新します。 |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.region の交差部分を除いた合併に更新します。 |
### Region() {#Region--}
```
public Region()
```


新しい T:Aspose.Imaging.Region を初期化します。

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


指定された T:Aspose.Imaging.RectangleF 構造体から新しい T:Aspose.Imaging.Region を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 新しい T:Aspose.Imaging.Region の内部を定義する T:Aspose.Imaging.RectangleF 構造体です。 |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


指定された T:Aspose.Imaging.Rectangle 構造体から新しい T:Aspose.Imaging.Region を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 新しい T:Aspose.Imaging.Region の内部を定義する T:Aspose.Imaging.Rectangle 構造体です。 |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


指定された T:Aspose.Imaging.GraphicsPath を使用して新しい T:Aspose.Imaging.Region を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 新しい T:Aspose.Imaging.Region を定義する T:Aspose.Imaging.GraphicsPath です。 |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


この com.aspose.psd.Region を更新し、指定された com.aspose.psd.GraphicsPath のうち、この com.aspose.psd.region と交差しない部分を含めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | この  com.aspose.psd.region を補完するための com.aspose.psd.GraphicsPath です。 |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


この com.aspose.psd.Region を更新し、指定された com.aspose.psd.Rectangle 構造体のうち、この com.aspose.psd.region と交差しない部分を含めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | この  com.aspose.psd.region を補完するための com.aspose.psd.Rectangle 構造体です。 |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


この com.aspose.psd.Region を更新し、指定された com.aspose.psd.RectangleF 構造体のうち、この com.aspose.psd.region と交差しない部分を含めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | この  com.aspose.psd.region を補完するための com.aspose.psd.RectangleF 構造体です。 |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


この com.aspose.psd.Region を更新し、指定された com.aspose.psd.Region のうち、この com.aspose.psd.region と交差しない部分を含めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | この  com.aspose.psd.Region オブジェクトを補完するための com.aspose.psd.Region オブジェクトです。 |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


この com.aspose.psd.region の正確なディープコピーを作成します。

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


この com.aspose.psd.Region を更新し、内部のうち、指定された com.aspose.psd.graphicsPath と交差しない部分だけを含めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | この com.aspose.psd.region から除外する com.aspose.psd.GraphicsPath。 |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


この com.aspose.psd.Region を更新し、内部のうち、指定された com.aspose.psd.Rectangle 構造体と交差しない部分だけを含めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | この com.aspose.psd.region から除外する com.aspose.psd.Rectangle 構造体。 |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


この com.aspose.psd.Region を更新し、内部のうち、指定された com.aspose.psd.RectangleF 構造体と交差しない部分だけを含めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | この com.aspose.psd.region から除外する com.aspose.psd.RectangleF 構造体。 |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


この com.aspose.psd.Region を更新し、内部のうち、指定された com.aspose.psd.region と交差しない部分だけを含めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | この com.aspose.psd.region から除外する com.aspose.psd.Region。 |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


リージョンのアクションを取得します。

**Returns:**
com.aspose.internal.RegionAction[] - 領域アクション。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


この com.aspose.psd.Region を更新し、指定された com.aspose.psd.graphicsPath との交差部分にします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | この com.aspose.psd.region と交差させる com.aspose.psd.GraphicsPath。 |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


この com.aspose.psd.Region を更新し、指定された com.aspose.psd.Rectangle 構造体との交差部分にします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | この com.aspose.psd.region と交差させる com.aspose.psd.Rectangle 構造体。 |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


この com.aspose.psd.Region を更新し、指定された com.aspose.psd.RectangleF 構造体との交差部分にします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | この com.aspose.psd.region と交差させる com.aspose.psd.RectangleF 構造体。 |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


この com.aspose.psd.Region を更新し、指定された com.aspose.psd.region との交差部分にします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | この com.aspose.psd.region と交差させる com.aspose.psd.Region。 |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


指定された描画サーフェス上で、この com.aspose.psd.Region の内部が空であるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | 描画サーフェスを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - g に関連付けられた変換が適用されたとき、この com.aspose.psd.Region の内部が空である場合は true、そうでなければ false。
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


指定された描画サーフェス上で、指定された com.aspose.psd.Region がこの com.aspose.psd.Region と同一かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | テスト対象の com.aspose.psd.Region。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 描画サーフェスを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - g パラメータに関連付けられた変換が適用されたとき、region の内部がこの region の内部と同一である場合は True、そうでなければ false。
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


指定された描画サーフェス上で、この com.aspose.psd.Region の内部が無限であるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | 描画サーフェスを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - g に関連付けられた変換が適用されたとき、この com.aspose.psd.Region の内部が無限である場合は true、そうでなければ false。
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


指定された com.aspose.psd.Point 構造体がこの com.aspose.psd.region に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | テスト対象の com.aspose.psd.Point 構造体。 |

**Returns:**
boolean - point がこの com.aspose.psd.Region に含まれる場合は true、そうでなければ false。
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


指定された com.aspose.psd.graphics を使用して描画した場合、指定された com.aspose.psd.Point 構造体がこの com.aspose.psd.Region に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | テスト対象の com.aspose.psd.Point 構造体。 |
| g | [Graphics](../../com.aspose.psd/graphics) | グラフィックスコンテキストを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - point がこの com.aspose.psd.Region に含まれる場合は true、そうでなければ false。
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


指定された com.aspose.psd.PointF 構造体がこの com.aspose.psd.region に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | テスト対象の com.aspose.psd.PointF 構造体。 |

**Returns:**
boolean - point がこの com.aspose.psd.Region に含まれる場合は true、そうでなければ false。
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


指定された com.aspose.psd.graphics を使用して描画した場合、指定された com.aspose.psd.PointF 構造体がこの com.aspose.psd.Region に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | テスト対象の com.aspose.psd.PointF 構造体。 |
| g | [Graphics](../../com.aspose.psd/graphics) | グラフィックスコンテキストを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - point がこの com.aspose.psd.Region に含まれる場合は true、そうでなければ false。
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


指定された com.aspose.psd.Rectangle 構造体の任意の部分がこの com.aspose.psd.region に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | テスト対象の com.aspose.psd.Rectangle 構造体。 |

**Returns:**
boolean - rect の任意の部分がこの com.aspose.psd.Region に含まれる場合は true を返し、そうでなければ false を返す。
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


指定された com.aspose.psd.graphics を使用して描画した場合、指定された com.aspose.psd.Rectangle 構造体の任意の部分がこの com.aspose.psd.Region に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | テスト対象の com.aspose.psd.Rectangle 構造体。 |
| g | [Graphics](../../com.aspose.psd/graphics) | グラフィックスコンテキストを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - rect の任意の部分がこの com.aspose.psd.Region に含まれる場合は true、そうでなければ false。
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


指定された com.aspose.psd.RectangleF 構造体の任意の部分がこの com.aspose.psd.region に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | テスト対象の com.aspose.psd.RectangleF 構造体。 |

**Returns:**
boolean - rect の任意の部分がこの com.aspose.psd.Region に含まれる場合は true、そうでなければ false。
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


指定された com.aspose.psd.graphics を使用して描画した場合、指定された com.aspose.psd.RectangleF 構造体の任意の部分がこの com.aspose.psd.Region に含まれるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | テスト対象の com.aspose.psd.RectangleF 構造体。 |
| g | [Graphics](../../com.aspose.psd/graphics) | グラフィックスコンテキストを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - rect がこの com.aspose.psd.Region に含まれる場合は true、そうでなければ false。
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


指定された点がこの  com.aspose.psd.region に含まれているかテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の点の x 座標です。 |
| y | float | テスト対象の点の y 座標です。 |

**Returns:**
boolean - 指定されたポイントがこの com.aspose.psd.Region に含まれる場合は True、そうでなければ false。
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


指定された点が、指定された  com.aspose.psd.graphics を使用して描画されたこの  com.aspose.psd.Region に含まれているかテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の点の x 座標です。 |
| y | float | テスト対象の点の y 座標です。 |
| g | [Graphics](../../com.aspose.psd/graphics) | グラフィックスコンテキストを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定されたポイントがこの com.aspose.psd.Region に含まれる場合は True、そうでなければ false。
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


指定された矩形の任意の部分がこの  com.aspose.psd.region に含まれているかテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の矩形の左上隅の x 座標。 |
| y | float | テスト対象の矩形の左上隅の y 座標。 |
| 幅 | float | テスト対象の矩形の幅。 |
| 高さ | float | テスト対象の矩形の高さ。 |

**Returns:**
boolean - 指定された矩形の一部がこの  com.aspose.psd.Region  オブジェクトに含まれる場合は true、そうでない場合は false。
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


指定された矩形の任意の部分が、指定された  com.aspose.psd.graphics を使用して描画されたこの  com.aspose.psd.Region に含まれているかテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の矩形の左上隅の x 座標。 |
| y | float | テスト対象の矩形の左上隅の y 座標。 |
| 幅 | float | テスト対象の矩形の幅。 |
| 高さ | float | テスト対象の矩形の高さ。 |
| g | [Graphics](../../com.aspose.psd/graphics) | グラフィックスコンテキストを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定された矩形の一部がこの  com.aspose.psd.Region  に含まれる場合は true、そうでない場合は false。
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


指定された点が、指定された  com.aspose.psd.Graphics オブジェクトを使用して描画されたこの  com.aspose.psd.Region オブジェクトに含まれているかテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の点の x 座標です。 |
| y | int | テスト対象の点の y 座標です。 |
| g | [Graphics](../../com.aspose.psd/graphics) | グラフィックスコンテキストを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定された点がこの  com.aspose.psd.Region  に含まれる場合は true、そうでない場合は false。
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


指定された矩形の任意の部分がこの  com.aspose.psd.region に含まれているかテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の矩形の左上隅の x 座標。 |
| y | int | テスト対象の矩形の左上隅の y 座標。 |
| 幅 | int | テスト対象の矩形の幅。 |
| 高さ | int | テスト対象の矩形の高さ。 |

**Returns:**
boolean - 指定された矩形の一部がこの  com.aspose.psd.Region  に含まれる場合は true、そうでない場合は false。
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


指定された矩形の任意の部分が、指定された  com.aspose.psd.graphics を使用して描画されたこの  com.aspose.psd.Region に含まれているかテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の矩形の左上隅の x 座標。 |
| y | int | テスト対象の矩形の左上隅の y 座標。 |
| 幅 | int | テスト対象の矩形の幅。 |
| 高さ | int | テスト対象の矩形の高さ。 |
| g | [Graphics](../../com.aspose.psd/graphics) | グラフィックスコンテキストを表す com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定された矩形の一部がこの  com.aspose.psd.Region  に含まれる場合は true、そうでない場合は false。
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


この  com.aspose.psd.Region を空の内部に初期化します。

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


この  com.aspose.psd.Region オブジェクトを無限の内部に初期化します。

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


変更時の領域を取得または設定します。

Value: 変更時の領域。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


指定された  com.aspose.psd.matrix によってこの  com.aspose.psd.Region を変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | この  com.aspose.psd.region を変換するための  com.aspose.psd.Matrix 。 |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


指定された量だけこの  com.aspose.psd.Region の座標をオフセットします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | この  com.aspose.psd.Region  を水平方向にオフセットする量。 |
| dy | float | この  com.aspose.psd.Region  を垂直方向にオフセットする量。 |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


指定された量だけこの  com.aspose.psd.Region の座標をオフセットします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | int | この  com.aspose.psd.Region  を水平方向にオフセットする量。 |
| dy | int | この  com.aspose.psd.Region  を垂直方向にオフセットする量。 |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.graphicsPath の合併に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | この  com.aspose.psd.region と結合するための  com.aspose.psd.GraphicsPath 。 |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.Rectangle 構造体の合併に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | この  com.aspose.psd.region と結合するための  com.aspose.psd.Rectangle 構造体。 |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.RectangleF 構造体の合併に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | この  com.aspose.psd.region と結合するための  com.aspose.psd.RectangleF 構造体。 |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.region の合併に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | この  com.aspose.psd.region と結合するための  com.aspose.psd.Region 。 |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.graphicsPath の交差部分を除いた合併に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | この  com.aspose.psd.region と排他的論理和 (xor) するための  com.aspose.psd.GraphicsPath 。 |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.Rectangle 構造体の交差部分を除いた合併に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | この  com.aspose.psd.region と排他的論理和 (xor) するための  com.aspose.psd.Rectangle 構造体。 |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.RectangleF 構造体の交差部分を除いた合併に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | この  com.aspose.psd.region と排他的論理和 (xor) するための  com.aspose.psd.RectangleF 構造体。 |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


この  com.aspose.psd.Region を自身と指定された  com.aspose.psd.region の交差部分を除いた合併に更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | この  com.aspose.psd.region と排他的論理和 (xor) するための  com.aspose.psd.Region 。 |

