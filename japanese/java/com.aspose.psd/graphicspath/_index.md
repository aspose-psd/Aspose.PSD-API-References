---
title: "GraphicsPath"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "接続された直線と曲線の系列を表します。"
type: docs
weight: 50
url: /ja/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object、[com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

接続された直線と曲線の系列を表します。このクラスは継承できません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | GraphicsPath クラスの新しいインスタンスを初期化します。 |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | GraphicsPath クラスの新しいインスタンスを初期化します。 |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | GraphicsPath クラスの新しいインスタンスを初期化します。 |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | GraphicsPath クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | 新しい図形を追加します。 |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | 新しい図形を追加します。 |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | 指定された com.aspose.psd.GraphicsPath をこのパスに追加します。 |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | 指定された com.aspose.psd.GraphicsPath をこのパスに追加します。 |
| [deepClone()](#deepClone--) | このグラフィック パスのディープ クローンを実行します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | このパス内の各曲線を接続された線分のシーケンスに変換します。 |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | 指定された変換を適用し、その後この com.aspose.psd.GraphicsPath 内の各曲線を接続された線分のシーケンスに変換します。 |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | この com.aspose.psd.GraphicsPath 内の各曲線を接続された線分のシーケンスに変換します。 |
| [getBounds()](#getBounds--) | オブジェクトの境界を取得または設定します。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | オブジェクトの境界を取得します。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | オブジェクトの境界を取得します。 |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | パスの図形を取得します。 |
| [getFillMode()](#getFillMode--) | この com.aspose.psd.GraphicsPath の形状の内部がどのように塗りつぶされるかを決定する com.aspose.psd.FillMode 列挙体を取得します。 |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | 指定された点が、指定された com.aspose.psd.pen で描画されたときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。 |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 指定された点が、指定された com.aspose.psd.Pen で描画され、指定された com.aspose.psd.graphics を使用したときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。 |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | 指定された点が、指定された com.aspose.psd.pen で描画されたときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。 |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 指定された点が、指定された com.aspose.psd.Pen で描画され、指定された com.aspose.psd.graphics を使用したときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。 |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | 指定された点が、指定された com.aspose.psd.pen で描画されたときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。 |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 指定された点が、指定された com.aspose.psd.Pen で描画され、指定された com.aspose.psd.graphics を使用したときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。 |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | 指定された点が、指定された com.aspose.psd.pen で描画されたときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。 |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 指定された点が、指定された com.aspose.psd.Pen で描画され、指定された com.aspose.psd.graphics を使用したときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。 |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | 指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。 |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | 指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。 |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | 指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。 |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | 指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。 |
| [isVisible(float x, float y)](#isVisible-float-float-) | 指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。 |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | 指定された点が、指定された com.aspose.psd.graphics の可視クリップ領域内で、この com.aspose.psd.GraphicsPath に含まれているかどうかを示します。 |
| [isVisible(int x, int y)](#isVisible-int-int-) | 指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。 |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | 指定された点が、指定された com.aspose.psd.graphics を使用して、この com.aspose.psd.GraphicsPath に含まれているかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | 図形を削除します。 |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | 図形を削除します。 |
| [reset()](#reset--) | グラフィックパスを空にし、com.aspose.psd.FillMode を F:com.aspose.psd.fillMode.alternate に設定します。 |
| [reverse()](#reverse--) | この com.aspose.psd.graphicsPath の各シェイプ内の図形、形状、ポイントの順序を逆にします。 |
| [setFillMode(int value)](#setFillMode-int-) | この com.aspose.psd.GraphicsPath の形状の内部がどのように塗りつぶされるかを決定する com.aspose.psd.FillMode 列挙体を設定します。 |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 指定された変換をシェイプに適用します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | 矩形と平行四辺形で定義されたワープ変換をこの com.aspose.psd.graphicsPath に適用します。 |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | 矩形と平行四辺形で定義されたワープ変換をこの com.aspose.psd.graphicsPath に適用します。 |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | 矩形と平行四辺形で定義されたワープ変換をこの com.aspose.psd.graphicsPath に適用します。 |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | 矩形と平行四辺形で定義されたワープ変換をこの com.aspose.psd.graphicsPath に適用します。 |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | パスに追加の輪郭を追加します。 |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | com.aspose.psd.graphicsPath に追加の輪郭を追加します。 |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | この com.aspose.psd.GraphicsPath を、指定されたペンでこのパスが描画されたときに塗りつぶされる領域を囲む曲線に置き換えます。 |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


GraphicsPath クラスの新しいインスタンスを初期化します。

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


GraphicsPath クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 初期化元の図形。 |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


GraphicsPath クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 初期化元の図形。 |
| fillMode | int | 塗りつぶしモード。 |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


GraphicsPath クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillMode | int | 塗りつぶしモード。 |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


新しい図形を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | 追加する図形。 |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


新しい図形を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 追加する図形。 |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


指定された com.aspose.psd.GraphicsPath をこのパスに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 追加する com.aspose.psd.GraphicsPath。 |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


指定された com.aspose.psd.GraphicsPath をこのパスに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 追加する com.aspose.psd.GraphicsPath。 |
| connect | boolean | 追加されたパスの最初の図形がこのパスの最後の図形の一部であるかどうかを指定するブール値です。true の場合、追加されたパスの最初の図形はこのパスの最後の図形の一部であることを示します。false の場合、追加されたパスの最初の図形はこのパスの最後の図形とは別であることを示します。 |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


このグラフィック パスのディープ クローンを実行します。

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
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
### flatten() {#flatten--}
```
public void flatten()
```


このパス内の各曲線を接続された線分のシーケンスに変換します。

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


指定された変換を適用し、その後この com.aspose.psd.GraphicsPath 内の各曲線を接続された線分のシーケンスに変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 平坦化する前にこの com.aspose.psd.GraphicsPath を変換するための com.aspose.psd.Matrix。 |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


この com.aspose.psd.GraphicsPath 内の各曲線を接続された線分のシーケンスに変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 平坦化する前にこの com.aspose.psd.GraphicsPath を変換するための com.aspose.psd.Matrix。 |
| flatness | float | 曲線とその平坦化近似との間の許容最大誤差を指定します。デフォルト値は 0.25 です。flatness の値を小さくすると、近似における線分の数が増加します。 |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


オブジェクトの境界を取得または設定します。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


オブジェクトの境界を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 境界が計算される前に適用する行列。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


オブジェクトの境界を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 境界が計算される前に適用する行列。 |
| pen | [Pen](../../com.aspose.psd/pen) | オブジェクトに使用するペン。これによりオブジェクトの境界サイズが影響を受ける可能性があります。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


パスの図形を取得します。

**Returns:**
com.aspose.psd.Figure[] - パスの図形。
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


この com.aspose.psd.GraphicsPath の形状の内部がどのように塗りつぶされるかを決定する com.aspose.psd.FillMode 列挙体を取得します。

**Returns:**
int - 塗りつぶしモード。 この com.aspose.psd.GraphicsPath の形状の内部がどのように塗りつぶされるかを指定する com.aspose.psd.FillMode 列挙体。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


指定された点が、指定された com.aspose.psd.pen で描画されたときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | テストする位置を指定する com.aspose.psd.Point。 |
| pen | [Pen](../../com.aspose.psd/pen) | テストする com.aspose.psd.Pen。 |

**Returns:**
boolean - 指定されたポイントが、指定された com.aspose.psd.Pen で描画されたこの com.aspose.psd.GraphicsPath のアウトライン内に含まれる場合は true を返し、そうでない場合は false を返します。
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


指定された点が、指定された com.aspose.psd.Pen で描画され、指定された com.aspose.psd.graphics を使用したときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | テストする位置を指定する com.aspose.psd.Point。 |
| pen | [Pen](../../com.aspose.psd/pen) | テストする com.aspose.psd.Pen。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 可視性をテストする対象の com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定されたポイントが、指定された com.aspose.psd.Pen で描画されたこの com.aspose.psd.GraphicsPath のアウトライン内に含まれる場合は true を返し、そうでない場合は false を返します。
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


指定された点が、指定された com.aspose.psd.pen で描画されたときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | テストする位置を指定する com.aspose.psd.PointF。 |
| pen | [Pen](../../com.aspose.psd/pen) | テストする com.aspose.psd.Pen。 |

**Returns:**
boolean - 指定されたポイントが、指定された com.aspose.psd.Pen で描画されたこの com.aspose.psd.GraphicsPath のアウトライン内に含まれる場合は true を返し、そうでない場合は false を返します。
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


指定された点が、指定された com.aspose.psd.Pen で描画され、指定された com.aspose.psd.graphics を使用したときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | テストする位置を指定する com.aspose.psd.PointF。 |
| pen | [Pen](../../com.aspose.psd/pen) | テストする com.aspose.psd.Pen。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 可視性をテストする対象の com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定されたポイントが、指定された com.aspose.psd.Pen で描画されたこの com.aspose.psd.GraphicsPath のアウトラインの下（内部）に含まれる場合は true を返し、そうでない場合は false を返します。
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


指定された点が、指定された com.aspose.psd.pen で描画されたときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の点の x 座標です。 |
| y | float | テスト対象の点の y 座標です。 |
| pen | [Pen](../../com.aspose.psd/pen) | テストする com.aspose.psd.Pen。 |

**Returns:**
boolean - 指定されたポイントが、指定された com.aspose.psd.Pen で描画されたこの com.aspose.psd.GraphicsPath のアウトライン内に含まれる場合は true を返し、そうでない場合は false を返します。
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


指定された点が、指定された com.aspose.psd.Pen で描画され、指定された com.aspose.psd.graphics を使用したときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の点の x 座標です。 |
| y | float | テスト対象の点の y 座標です。 |
| pen | [Pen](../../com.aspose.psd/pen) | テストする com.aspose.psd.Pen。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 可視性をテストする対象の com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定されたポイントが、指定された com.aspose.psd.Pen で描画されたこの com.aspose.psd.GraphicsPath のアウトラインの下（内部）に含まれる場合は true を返し、そうでない場合は false を返します。
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


指定された点が、指定された com.aspose.psd.pen で描画されたときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の点の x 座標です。 |
| y | int | テスト対象の点の y 座標です。 |
| pen | [Pen](../../com.aspose.psd/pen) | テストする com.aspose.psd.Pen。 |

**Returns:**
boolean - 指定されたポイントが、指定された com.aspose.psd.Pen で描画されたこの com.aspose.psd.GraphicsPath のアウトライン内に含まれる場合は true を返し、そうでない場合は false を返します。
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


指定された点が、指定された com.aspose.psd.Pen で描画され、指定された com.aspose.psd.graphics を使用したときに、この com.aspose.psd.GraphicsPath の輪郭（内部）に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の点の x 座標です。 |
| y | int | テスト対象の点の y 座標です。 |
| pen | [Pen](../../com.aspose.psd/pen) | テストする com.aspose.psd.Pen。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 可視性をテストする対象の com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定されたポイントが、指定された com.aspose.psd.Pen で描画されたこの com.aspose.psd.GraphicsPath のアウトライン内に含まれる場合は true を返し、そうでない場合は false を返します。
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | テストするポイントを表す com.aspose.psd.Point。 |

**Returns:**
boolean - 指定されたポイントがこの com.aspose.psd.GraphicsPath の内部に含まれる場合は true を返し、そうでない場合は false を返します。
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | テストするポイントを表す com.aspose.psd.Point。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 可視性をテストする対象の com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定されたポイントがこの com.aspose.psd.GraphicsPath の内部に含まれる場合は true を返し、そうでない場合は false を返します。
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | テストするポイントを表す com.aspose.psd.PointF。 |

**Returns:**
boolean - 指定されたポイントがこの com.aspose.psd.GraphicsPath の内部に含まれる場合は true を返し、そうでない場合は false を返します。
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | テストするポイントを表す com.aspose.psd.PointF。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 可視性をテストする対象の com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定されたポイントがこれの内部に含まれる場合は true を返し、そうでない場合は false を返します。
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の点の x 座標です。 |
| y | float | テスト対象の点の y 座標です。 |

**Returns:**
boolean - 指定されたポイントがこの com.aspose.psd.GraphicsPath の内部に含まれる場合は true を返し、そうでない場合は false を返します。
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


指定された点が、指定された com.aspose.psd.graphics の可視クリップ領域内で、この com.aspose.psd.GraphicsPath に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の点の x 座標です。 |
| y | float | テスト対象の点の y 座標です。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 可視性をテストする対象の com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定されたポイントがこの com.aspose.psd.GraphicsPath の内部に含まれる場合は true を返し、そうでない場合は false を返します。
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


指定された点が、この com.aspose.psd.graphicsPath 内に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の点の x 座標です。 |
| y | int | テスト対象の点の y 座標です。 |

**Returns:**
boolean - 指定されたポイントがこの com.aspose.psd.GraphicsPath の内部に含まれる場合は true を返し、そうでない場合は false を返します。
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


指定された点が、指定された com.aspose.psd.graphics を使用して、この com.aspose.psd.GraphicsPath に含まれているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の点の x 座標です。 |
| y | int | テスト対象の点の y 座標です。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 可視性をテストする対象の com.aspose.psd.Graphics。 |

**Returns:**
boolean - 指定されたポイントがこの com.aspose.psd.GraphicsPath の内部に含まれる場合は true を返し、そうでない場合は false を返します。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


図形を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | 削除する図形。 |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


図形を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 削除する図形群。 |

### reset() {#reset--}
```
public void reset()
```


グラフィックパスを空にし、com.aspose.psd.FillMode を F:com.aspose.psd.fillMode.alternate に設定します。

### reverse() {#reverse--}
```
public void reverse()
```


この com.aspose.psd.graphicsPath の各シェイプ内の図形、形状、ポイントの順序を逆にします。

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


この com.aspose.psd.GraphicsPath の形状の内部がどのように塗りつぶされるかを決定する com.aspose.psd.FillMode 列挙体を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 塗りつぶしモード。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


指定された変換をシェイプに適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | 適用する変換。 |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


矩形と平行四辺形で定義されたワープ変換をこの com.aspose.psd.graphicsPath に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect で定義された矩形が変換される平行四辺形を定義する com.aspose.psd.PointF 構造体の配列。この配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints で定義された平行四辺形に変換される矩形を表す com.aspose.psd.RectangleF。 |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


矩形と平行四辺形で定義されたワープ変換をこの com.aspose.psd.graphicsPath に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect で定義された矩形が変換される平行四辺形を定義する com.aspose.psd.PointF 構造体の配列。この配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints で定義された平行四辺形に変換される矩形を表す com.aspose.psd.RectangleF。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | パスに適用する幾何変換を指定する com.aspose.psd.Matrix。 |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


矩形と平行四辺形で定義されたワープ変換をこの com.aspose.psd.graphicsPath に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect で定義された矩形が変換される平行四辺形を定義する com.aspose.psd.PointF 構造体の配列。この配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints で定義された平行四辺形に変換される矩形を表す com.aspose.psd.RectangleF。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | パスに適用する幾何変換を指定する com.aspose.psd.Matrix。 |
| warpMode | int | このワープ操作が透視投影モードか双一次モードかを指定する com.aspose.psd.WarpMode 列挙体。 |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


矩形と平行四辺形で定義されたワープ変換をこの com.aspose.psd.graphicsPath に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect で定義された矩形が変換される平行四辺形を定義する com.aspose.psd.PointF 構造体の配列。この配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints で定義された平行四辺形に変換される矩形を表す com.aspose.psd.RectangleF。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | パスに適用する幾何変換を指定する com.aspose.psd.Matrix。 |
| warpMode | int | このワープ操作が透視投影モードか双一次モードかを指定する com.aspose.psd.WarpMode 列挙体。 |
| flatness | float | 結果のパスがどれほど平坦であるかを指定する 0 から 1 までの値。詳細については com.aspose.psd.GraphicsPath.flatten メソッドを参照してください。 |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


パスに追加の輪郭を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | このメソッドが作成する新しいアウトラインと元のパスのアウトラインとの間の幅を指定する com.aspose.psd.Pen。 |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


com.aspose.psd.graphicsPath に追加の輪郭を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | このメソッドが作成する新しいアウトラインと元のパスのアウトラインとの間の幅を指定する com.aspose.psd.Pen。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 拡張前にパスに適用する変換を指定する com.aspose.psd.Matrix。 |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


この com.aspose.psd.GraphicsPath を、指定されたペンでこのパスが描画されたときに塗りつぶされる領域を囲む曲線に置き換えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | このメソッドが作成する新しいアウトラインと元のパスのアウトラインとの間の幅を指定する com.aspose.psd.Pen。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 拡張前にパスに適用する変換を指定する com.aspose.psd.Matrix。 |
| flatness | float | 曲線の平坦度を指定する値。 |

