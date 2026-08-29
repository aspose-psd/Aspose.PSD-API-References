---
title: "クラス Graphics"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Graphics クラス。現在のアセンブリで使用されているグラフィックエンジンに従ってグラフィックを表します。"
type: docs
weight: 4780
url: /ja/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

現在のアセンブリで使用されているグラフィックエンジンに従ってグラフィックを表します。

```csharp
public sealed class Graphics
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Graphics](graphics/)(Image) | `Graphics` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | クリップ領域を取得または設定します。 |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | 合成品質を取得または設定します。 |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | この Aspose.PSD.Graphics の水平解像度を取得します。 |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | この Aspose.PSD.Graphics の垂直解像度を取得します。 |
| [Image](../../aspose.psd/graphics/image/) { get; } | 画像を取得します。 |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | 補間モードを取得または設定します。 |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | グラフィックが BeginUpdate 呼び出し状態にあるかどうかを示す値を取得します。 |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | この Aspose.PSD.Graphics のワールド単位とページ単位間のスケーリングを取得または設定します。 |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | この Aspose.PSD.Graphics のページ座標に使用される測定単位を取得または設定します。 |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | 画像オプションを取得または設定します。描画用の塗りつぶし可能なベクター画像を作成するために使用されます。 |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | スムージングモードを取得または設定します。 |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | テキストレンダリングヒントを取得または設定します。 |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | `Graphics` の幾何学的ワールド変換のコピーを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | 以下のグラフィック操作のキャッシュを開始します。その後に適用されるグラフィック効果はすぐには適用されず、代わりに EndUpdate が呼び出されたときにすべての効果が一度に適用されます。 |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | 指定された色を使用してグラフィックサーフェスをクリアします。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | [`Rectangle`](../rectangle/) 構造体で指定された楕円の一部を表す弧を描画します。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | [`RectangleF`](../rectanglef/) 構造体で指定された楕円の一部を表す弧を描画します。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | 座標のペア、幅、および高さで指定された楕円の一部を表す弧を描画します。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | 座標のペア、幅、および高さで指定された楕円の一部を表す弧を描画します。 |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | 4つの [`Point`](../point/) 構造体で定義されたベジェスプラインを描画します。 |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | 4つの [`PointF`](../pointf/) 構造体で定義されたベジェスプラインを描画します。 |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | 点を表す4つの順序付き座標ペアで定義されたベジェスプラインを描画します。 |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | [`PointF`](../pointf/) 構造体の配列からベジェスプラインの系列を描画します。 |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | [`Point`](../point/) 構造体の配列からベジェスプラインの系列を描画します。 |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | [`PointF`](../pointf/) 構造体の配列で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 と Alternate 塗りつぶしモードを使用します。 |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | [`Point`](../point/) 構造体の配列で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 と Alternate 塗りつぶしモードを使用します。 |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | [`PointF`](../pointf/) 構造体の配列で定義された閉じたカーディナルスプラインを、指定されたテンションで描画します。このメソッドはデフォルトの Alternate 塗りつぶしモードを使用します。 |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | 指定されたテンションを使用して、[`Point`](../point/) 構造体の配列で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトの Alternate 塗りつぶしモードを使用します。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | 指定された [`PointF`](../pointf/) 構造体の配列を通るカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 を使用します。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | 指定された [`Point`](../point/) 構造体の配列を通るカーディナルスプラインを描画します。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | 指定されたテンションを使用して、指定された [`PointF`](../pointf/) 構造体の配列を通るカーディナルスプラインを描画します。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | 指定されたテンションを使用して、指定された [`Point`](../point/) 構造体の配列を通るカーディナルスプラインを描画します。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | 指定された [`PointF`](../pointf/) 構造体の配列を通るカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。このメソッドはデフォルトのテンション 0.5 を使用します。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | 指定されたテンションを使用して、指定された [`PointF`](../pointf/) 構造体の配列を通るカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | 指定されたテンションを使用して、指定された [`Point`](../point/) 構造体の配列を通るカーディナルスプラインを描画します。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | 境界となる [`Rectangle`](../rectangle/) 構造体で指定された楕円を描画します。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | 境界となる [`RectangleF`](../rectanglef/) で定義された楕円を描画します。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | 座標のペア、高さ、幅で指定された境界矩形により定義された楕円を描画します。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | 座標のペア、高さ、幅で指定された境界矩形により定義された楕円を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | 指定された場所に、元の物理サイズを使用して指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | 指定された場所に、元の物理サイズを使用して指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | 指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | 指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | 指定された場所に、元の物理サイズを使用して指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | 座標のペアで指定された場所に、元の物理サイズを使用して指定された画像を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | 指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | 指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | 指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | 指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | 指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | 指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | 指定された場所に、指定されたサイズで指定された [`Image`](./image/) を描画します。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | 指定された場所に、元の物理サイズを使用して指定された画像を描画します。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | 指定された場所に、元の物理サイズを使用して指定された画像を描画します。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | 座標のペアで指定された場所に、元の物理サイズを使用して指定された画像を描画します。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | 指定された場所に、元の物理サイズを使用して指定された画像を描画します。 |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | 指定された画像をスケーリングせずに描画し、必要に応じて指定された矩形に収まるようにクリップします。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | 2つの [`Point`](../point/) 構造体を接続する線を描画します。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | 2つの [`PointF`](../pointf/) 構造体を接続する線を描画します。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | 座標ペアで指定された2点を接続する線を描画します。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | 座標ペアで指定された2点を接続する線を描画します。 |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | [`PointF`](../pointf/) 構造体の配列を接続する一連の線分を描画します。 |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | [`Point`](../point/) 構造体の配列を接続する一連の線分を描画します。 |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | [`GraphicsPath`](../graphicspath/) を描画します。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | [`Rectangle`](../rectangle/) 構造体で指定された楕円と2本の放射線で定義されたパイ形状を描画します。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | [`RectangleF`](../rectanglef/) 構造体で指定された楕円と2本の放射線で定義されたパイ形状を描画します。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | 座標ペア、幅、高さ、および2本の放射線で指定された楕円によって定義されるパイ形状を描画します。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | 座標ペア、幅、高さ、および2本の放射線で指定された楕円によって定義されるパイ形状を描画します。 |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | [`PointF`](../pointf/) 構造体の配列で定義されたポリゴンを描画します。 |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | [`Point`](../point/) 構造体の配列で定義されたポリゴンを描画します。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | [`Rectangle`](../rectangle/) 構造体で指定された矩形を描画します。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | [`RectangleF`](../rectanglef/) 構造体で指定された矩形を描画します。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | 座標ペア、幅、および高さで指定された矩形を描画します。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | 座標ペア、幅、および高さで指定された矩形を描画します。 |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | [`RectangleF`](../rectanglef/) 構造体で指定された矩形の系列を描画します。 |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | [`Rectangle`](../rectangle/) 構造体で指定された矩形の系列を描画します。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | 指定された [`Brush`](../brush/) と [`Font`](../font/) オブジェクトを使用して、指定された場所に指定されたテキスト文字列を描画します。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | 指定された [`Brush`](../brush/) と [`Font`](../font/) オブジェクトを使用して、指定された矩形内に指定されたテキスト文字列を描画します。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | 指定された [`Brush`](../brush/) と [`Font`](../font/) オブジェクトを使用して、指定された場所に指定されたテキスト文字列を描画します。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | 指定された [`Brush`](../brush/) と [`Font`](../font/) オブジェクトを使用し、指定された [`StringFormat`](../stringformat/) の書式属性を使用して、指定された場所に指定されたテキスト文字列を描画します。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | 指定された [`Brush`](../brush/) と [`Font`](../font/) オブジェクトを使用し、指定された [`StringFormat`](../stringformat/) の書式属性を使用して、指定された矩形内に指定されたテキスト文字列を描画します。 |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | 指定された [`Brush`](../brush/) と [`Font`](../font/) オブジェクトを使用し、指定された [`StringFormat`](../stringformat/) の書式属性を使用して、指定された場所に指定されたテキスト文字列を描画します。 |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | BeginUpdate が呼び出された後に開始されたグラフィック操作のキャッシュを終了します。前のグラフィック操作はこのメソッドを呼び出すと一度に適用されます。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | [`PointF`](../pointf/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 と Alternate 塗りつぶしモードを使用します。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | [`Point`](../point/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 と Alternate 塗りつぶしモードを使用します。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | [`PointF`](../pointf/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードを使用して塗りつぶします。このメソッドはデフォルトのテンション 0.5 を使用します。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | [`Point`](../point/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードを使用して塗りつぶします。このメソッドはデフォルトのテンション 0.5 を使用します。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | [`PointF`](../pointf/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードとテンションを使用して塗りつぶします。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | [`Point`](../point/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードとテンションを使用して塗りつぶします。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | [`Rectangle`](../rectangle/) 構造体で指定された外接矩形で定義された楕円の内部を塗りつぶします。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | [`RectangleF`](../rectanglef/) 構造体で指定された外接矩形で定義された楕円の内部を塗りつぶします。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | 座標ペア、幅、高さで指定された外接矩形で定義された楕円の内部を塗りつぶします。 |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | 座標ペア、幅、高さで指定された外接矩形で定義された楕円の内部を塗りつぶします。 |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | [`GraphicsPath`](../graphicspath/) の内部を塗りつぶします。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | [`RectangleF`](../rectanglef/) 構造体で指定された楕円と2本の放射線で定義されたパイセクションの内部を塗りつぶします。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | [`RectangleF`](../rectanglef/) 構造体で指定された楕円と2本の放射線で定義されたパイセクションの内部を塗りつぶします。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | 座標ペア、幅、高さ、2本の放射線で指定された楕円で定義されたパイセクションの内部を塗りつぶします。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | 座標ペア、幅、高さ、2本の放射線で指定された楕円で定義されたパイセクションの内部を塗りつぶします。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | 配列で指定されたポイント [`PointF`](../pointf/) 構造体により定義された多角形の内部を、Alternate で塗りつぶします。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | 配列で指定されたポイント [`Point`](../point/) 構造体により定義された多角形の内部を、Alternate で塗りつぶします。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | 配列で指定されたポイント [`PointF`](../pointf/) 構造体により定義された多角形の内部を、指定された塗りつぶしモードで塗りつぶします。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | 配列で指定されたポイント [`Point`](../point/) 構造体により定義された多角形の内部を、指定された塗りつぶしモードで塗りつぶします。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | `[`Rectangle`](../rectangle/)` 構造体で指定された矩形の内部を塗りつぶします。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | `[`RectangleF`](../rectanglef/)` 構造体で指定された矩形の内部を塗りつぶします。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | 座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | 座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。 |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | `[`RectangleF`](../rectanglef/)` 構造体で指定された一連の矩形の内部を塗りつぶします。 |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | `[`Rectangle`](../rectangle/)` 構造体で指定された一連の矩形の内部を塗りつぶします。 |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | `[`Region`](../region/)` の内部を塗りつぶします。 |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | この `Graphics` のローカル幾何変換を表す [`Matrix`](../matrix/) に、指定された [`Matrix`](../matrix/) を前置して掛け算します。 |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | この `Graphics` のローカル幾何変換を表す [`Matrix`](../matrix/) に、指定された順序で指定された [`Matrix`](../matrix/) を掛け算します。 |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | この [`Transform`](./transform/) プロパティを単位変換にリセットします。 |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | ローカル幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に追加します。 |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された量だけ回転させます。 |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | ローカル幾何変換を指定された量だけ拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に追加します。 |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された量だけ拡大縮小します。 |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に追加します。 |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | ローカル幾何変換を指定された順序で、指定された寸法だけ平行移動します。 |

## 例

この例では Graphics クラスを使用して画像表面上に基本形状を作成します。操作を示すために、例では PSD 形式の新しい Image を作成し、Graphics クラスが提供する Draw メソッドを使用して画像表面上に基本形状を描画し、最後に PSD ファイル形式へエクスポートします。

```csharp
[C#]

//Image のインスタンスを作成します。
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics クラスのインスタンスを作成し、初期化します。
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics のサーフェスをクリアします。
    graphics.Clear(Color.Wheat);

    //Pen オブジェクトで黒色を指定して円弧を描画します、
    //円弧を囲む矩形、開始角度およびスイープ角度
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Pen オブジェクトで青色と座標ポイントを指定してベジェ曲線を描画します。
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Pen オブジェクトで緑色とポイントの配列を指定して曲線を描画します
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen オブジェクトとそれを囲む矩形を使用して楕円を描画します
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //直線を描画します
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //パイセグメントを描画します
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Pen オブジェクトで赤色とポイントの配列を指定して多角形を描画します
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //矩形を描画します
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush オブジェクトを作成し、そのさまざまなプロパティを設定します
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush オブジェクトと Font を使用して、特定の Point で文字列を描画します
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


