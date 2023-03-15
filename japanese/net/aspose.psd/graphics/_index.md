---
title: Class Graphics
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Graphics クラス. 現在のアセンブリで使用されているグラフィック エンジンに従ってグラフィックを表します
type: docs
weight: 4310
url: /ja/net/aspose.psd/graphics/
---
## Graphics class

現在のアセンブリで使用されているグラフィック エンジンに従ってグラフィックを表します。

```csharp
public sealed class Graphics
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Graphics](graphics/)(Image) | の新しいインスタンスを初期化します`Graphics`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | クリップ領域を取得または設定します。 |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | 合成品質を取得または設定します。 |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | この Aspose.PSD.Graphics. の水平解像度を取得します。 |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | この Aspose.PSD.Graphics. の垂直解像度を取得します。 |
| [Image](../../aspose.psd/graphics/image/) { get; } | 画像を取得します。 |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | 補間モードを取得または設定します。 |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | グラフィックスが BeginUpdate 呼び出し状態かどうかを示す値を取得します。 |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | この Aspose.PSD.Graphics. のワールド単位とページ単位の間のスケーリングを取得または設定します |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | この Aspose.PSD.Graphics. でページ座標に使用される計測単位を取得または設定します |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | スムージング モードを取得または設定します。 |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | テキスト レンダリング ヒントを取得または設定します。 |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | このジオメトリック ワールド変換のコピーを取得または設定します`Graphics` . |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | 次のグラフィック操作のキャッシュを開始します。その後適用されたグラフィック効果はすぐには適用されず、代わりに EndUpdate によってすべての効果が一度に適用されます. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | 指定された色を使用してグラフィックス サーフェスをクリアします。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | で指定された楕円の一部を表す円弧を描画します[`Rectangle`](../rectangle/)構造体. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | で指定された楕円の一部を表す円弧を描画します[`RectangleF`](../rectanglef/)構造体. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | 座標、幅、および高さのペアで指定された楕円の一部を表す円弧を描画します。 |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | 座標、幅、および高さのペアで指定された楕円の一部を表す円弧を描画します。 |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | 4 で定義されるベジェ スプラインを描画します。[`Point`](../point/)構造物. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | 4 で定義されるベジェ スプラインを描画します。[`PointF`](../pointf/)構造物. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | 点を表す 4 つの順序付けられた座標のペアによって定義されるベジエ スプラインを描画します。 |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | の配列から一連のベジェ スプラインを描画します。[`PointF`](../pointf/)構造物. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | の配列から一連のベジェ スプラインを描画します。[`Point`](../point/)構造物. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | の配列で定義された閉じたカーディナル スプラインを描画します。[`PointF`](../pointf/)構造。この方法では、デフォルトのテンション 0.5 を使用し、Alternate塗りつぶしモード. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | の配列で定義された閉じたカーディナル スプラインを描画します。[`Point`](../point/)構造。この方法では、デフォルトのテンション 0.5 を使用し、Alternate塗りつぶしモード. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | の配列で定義された閉じたカーディナル スプラインを描画します。[`PointF`](../pointf/)指定された張力を使用する構造。このメソッドはデフォルトを使用しますAlternate塗りつぶしモード. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | の配列で定義された閉じたカーディナル スプラインを描画します。[`Point`](../point/)指定された張力を使用する構造。このメソッドはデフォルトを使用しますAlternate塗りつぶしモード. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | の指定された配列を介してカーディナル スプラインを描画します。[`PointF`](../pointf/)構造。この方法では、デフォルトのテンション 0.5. を使用します。 |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | の指定された配列を介してカーディナル スプラインを描画します。[`Point`](../point/)構造物. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | の指定された配列を介してカーディナル スプラインを描画します。[`PointF`](../pointf/)指定された張力を使用する構造. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | の指定された配列を介してカーディナル スプラインを描画します。[`Point`](../point/)指定された張力を使用する構造. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | の指定された配列を介してカーディナル スプラインを描画します。[`PointF`](../pointf/)構造。描画は、配列の先頭からのオフセットで開始されます. この方法では、デフォルトのテンション 0.5 を使用します. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | の指定された配列を介してカーディナル スプラインを描画します。[`PointF`](../pointf/)指定された張力を使用する構造。描画は配列の先頭からのオフセットで始まります. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | の指定された配列を介してカーディナル スプラインを描画します。[`Point`](../point/)指定された張力を使用する構造. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | 境界で指定された楕円を描画します[`Rectangle`](../rectangle/)構造体. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | 境界によって定義された楕円を描画します[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | 座標、高さ、幅のペアで指定された外接する四角形で定義される楕円を描画します。 |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | 座標、高さ、幅のペアで指定された外接する四角形で定義される楕円を描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | 指定された[`Image`](./image/)、元の物理サイズを使用して、指定された場所で. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | 指定された[`Image`](./image/)、元の物理サイズを使用して、指定された場所で. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | 指定されたオブジェクトの指定された部分を描画します*image*指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | 指定されたオブジェクトの指定された部分を描画します*image*指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | 指定された[`Image`](./image/)、元の物理サイズを使用して、指定された場所で. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | 座標ペアで指定された位置に、元の物理サイズを使用して、指定されたイメージを描画します。 |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | 指定されたオブジェクトの指定された部分を描画します*image*指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | 指定されたオブジェクトの指定された部分を描画します*image*指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | 指定されたオブジェクトの指定された部分を描画します*image*指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | 指定されたオブジェクトの指定された部分を描画します*image*指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | 指定されたオブジェクトの指定された部分を描画します*image*指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | 指定されたオブジェクトの指定された部分を描画します*image*指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | 指定された[`Image`](./image/)指定された場所に、指定されたサイズで. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | 指定された位置に元の物理サイズを使用して、指定されたイメージを描画します。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | 指定された位置に元の物理サイズを使用して、指定されたイメージを描画します。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | 座標ペアで指定された位置に元の物理サイズを使用して、指定されたイメージを描画します。 |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | 指定された位置に元の物理サイズを使用して、指定されたイメージを描画します。 |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | 指定された画像をスケーリングせずに描画し、必要に応じて、指定された四角形に収まるようにクリップします。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | 2 つを結ぶ線を描画します[`Point`](../point/)構造物. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | 2 つを結ぶ線を描画します[`PointF`](../pointf/)構造物. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | 座標ペアで指定された 2 点を結ぶ線を描画します。 |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | 座標ペアで指定された 2 点を結ぶ線を描画します。 |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | の配列を接続する一連の線分を描画します[`PointF`](../pointf/)構造物. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | の配列を接続する一連の線分を描画します[`Point`](../point/)構造物. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | を描画します[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | で指定された楕円で定義されるパイの形状を描画します[`Rectangle`](../rectangle/)構造と 2 つの放射状の線. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | で指定された楕円で定義されるパイの形状を描画します[`RectangleF`](../rectanglef/)構造と 2 つの放射状の線. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | 座標ペア、幅、高さ、および 2 本の放射状線で指定された楕円によって定義されるパイ形状を描画します。 |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | 座標ペア、幅、高さ、および 2 本の放射状線で指定された楕円によって定義されるパイ形状を描画します。 |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | の配列で定義された多角形を描画します[`PointF`](../pointf/)構造物. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | の配列で定義された多角形を描画します[`Point`](../point/)構造物. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | で指定された長方形を描画します[`Rectangle`](../rectangle/)構造体. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | で指定された長方形を描画します[`RectangleF`](../rectanglef/)構造体. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | 座標ペア、幅、高さで指定された長方形を描画します。 |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | 座標ペア、幅、高さで指定された長方形を描画します。 |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | で指定された一連の長方形を描画します[`RectangleF`](../rectanglef/)構造物. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | で指定された一連の長方形を描画します[`Rectangle`](../rectangle/)構造物. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | 指定した位置に指定した文字列を指定した文字列で描画します。[`Brush`](../brush/)と[`Font`](../font/)オブジェクト. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | 指定されたテキスト文字列を、指定された長方形内に指定された色で描画します。[`Brush`](../brush/)と[`Font`](../font/)オブジェクト. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | 指定した位置に指定した文字列を指定した文字列で描画します。[`Brush`](../brush/)と[`Font`](../font/)オブジェクト. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | 指定した位置に指定した文字列を指定した文字列で描画します。[`Brush`](../brush/)と[`Font`](../font/)指定された書式設定属性を使用するオブジェクト[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | 指定されたテキスト文字列を、指定された長方形内に指定された色で描画します。[`Brush`](../brush/)と[`Font`](../font/)指定された書式設定属性を使用するオブジェクト[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | 指定した位置に指定した文字列を指定した文字列で描画します。[`Brush`](../brush/)と[`Font`](../font/)指定された書式設定属性を使用するオブジェクト[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | BeginUpdate が呼び出された後に開始されたグラフィック操作のキャッシュを終了します。このメソッドを呼び出すと、以前のグラフィックス操作が一度に適用されます. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | の配列で定義された閉じたカーディナル スプライン曲線の内部を塗りつぶします。[`PointF`](../pointf/)構造。この方法では、デフォルトのテンション 0.5 を使用し、Alternate塗りつぶしモード. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | の配列で定義された閉じたカーディナル スプライン曲線の内部を塗りつぶします。[`Point`](../point/)構造。この方法では、デフォルトのテンション 0.5 を使用し、Alternate塗りつぶしモード. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | の配列で定義された閉じたカーディナル スプライン曲線の内部を塗りつぶします。[`PointF`](../pointf/)指定された塗りつぶしモードを使用する構造。この方法では、デフォルトのテンション 0.5. を使用します。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | の配列で定義された閉じたカーディナル スプライン曲線の内部を塗りつぶします。[`Point`](../point/)指定された塗りつぶしモードを使用する構造。この方法では、デフォルトのテンション 0.5. を使用します。 |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | の配列で定義された閉じたカーディナル スプライン曲線の内部を塗りつぶします。[`PointF`](../pointf/)指定された充填モードとテンションを使用した構造. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | の配列で定義された閉じたカーディナル スプライン曲線の内部を塗りつぶします。[`Point`](../point/)指定された充填モードとテンションを使用した構造. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | によって指定された外接する長方形によって定義された楕円の内部を塗りつぶします。[`Rectangle`](../rectangle/)構造体. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | によって指定された外接する長方形によって定義された楕円の内部を塗りつぶします。[`RectangleF`](../rectanglef/)構造体. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | 座標、幅、および高さのペアによって指定された外接する長方形によって定義された楕円の内部を塗りつぶします. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | 座標、幅、および高さのペアによって指定された外接する長方形によって定義された楕円の内部を塗りつぶします. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | の内部を塗りつぶします[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | で指定された楕円で定義されたパイ セクションの内部を塗りつぶします。[`RectangleF`](../rectanglef/)構造と 2 つの放射状の線. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | で指定された楕円で定義されたパイ セクションの内部を塗りつぶします。[`RectangleF`](../rectanglef/)構造と 2 つの放射状の線. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | 1 組の座標、幅、高さ、および 2 本の放射状の線で指定された楕円で定義されるパイ セクションの内部を塗りつぶします。 |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | 1 組の座標、幅、高さ、および 2 本の放射状の線で指定された楕円で定義されるパイ セクションの内部を塗りつぶします。 |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | によって指定された点の配列によって定義された多角形の内部を塗りつぶします。[`PointF`](../pointf/)構造とAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | によって指定された点の配列によって定義された多角形の内部を塗りつぶします。[`Point`](../point/)構造とAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | によって指定された点の配列によって定義された多角形の内部を塗りつぶします。[`PointF`](../pointf/)指定された塗りつぶしモードを使用する構造. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | によって指定された点の配列によって定義された多角形の内部を塗りつぶします。[`Point`](../point/)指定された塗りつぶしモードを使用する構造. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | によって指定された長方形の内部を塗りつぶします。[`Rectangle`](../rectangle/)構造体. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | によって指定された長方形の内部を塗りつぶします。[`RectangleF`](../rectanglef/)構造体. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | 座標のペア、幅と高さで指定された長方形の内部を塗りつぶします。 |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | 座標のペア、幅と高さで指定された長方形の内部を塗りつぶします。 |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | によって指定された一連の長方形の内部を塗りつぶします。[`RectangleF`](../rectanglef/)構造物. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | によって指定された一連の長方形の内部を塗りつぶします。[`Rectangle`](../rectangle/)構造物. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | の内部を塗りつぶします[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | を乗算します。[`Matrix`](../matrix/)これは、この局所的な幾何学的変換を表します`Graphics`指定された[`Matrix`](../matrix/)指定された[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | を乗算します。[`Matrix`](../matrix/)これは、この局所的な幾何学的変換を表します`Graphics`指定された[`Matrix`](../matrix/)指定された順序で. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | をリセットします[`Transform`](./transform/)プロパティからidentity. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | 指定された量だけローカル ジオメトリック トランスフォームを回転させます。このメソッドは、変換の前に回転を追加します. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 指定された順序で、指定された量だけローカル ジオメトリック トランスフォームを回転させます。 |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | 指定した量だけローカル ジオメトリック トランスフォームをスケーリングします。このメソッドは、スケーリング マトリックスを変換の先頭に追加します。 |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 指定された順序で、指定された量だけローカル ジオメトリック トランスフォームをスケーリングします。 |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | 指定された次元でローカル ジオメトリック トランスフォームを変換します。このメソッドは、transform. の先頭に翻訳を追加します。 |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 指定された順序で、指定された次元でローカル ジオメトリック トランスフォームを変換します。 |

### 例

この例では、Graphics クラスを使用して、イメージ サーフェス上にプリミティブ シェイプを作成します。操作を示すために、この例では PSD 形式で新しい画像を作成し、Graphics クラスによって公開された Draw メソッドを使用して画像表面にプリミティブ形状を描画し、それを PSD ファイル形式にエクスポートします。

```csharp
[C#]

//Image のインスタンスを作成する 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics クラスのインスタンスを作成して初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // グラフィック サーフェスをクリアする
    graphics.Clear(Color.Wheat);

    //黒色のペンオブジェクトを指定して円弧を描き、 
    //円弧、開始角度、およびスイープ角度を囲む長方形
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //青色で座標ポイントを持つ Pen オブジェクトを指定して、ベジエを描画します。
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //緑色のペン オブジェクトとポイントの配列を指定して、曲線を描画します
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen オブジェクトと周囲の Rectangle を使用して Ellipse を描画します
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //線を引く 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //円のセグメントを描画します
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //赤色の Pen オブジェクトと Point の配列を指定して Polygon を描画します
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //長方形を描く
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush オブジェクトを作成し、さまざまなプロパティを設定します
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush オブジェクトと Font を使用して、特定の Point に文字列を描画します
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    // PngOptions のインスタンスを作成し、さまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


