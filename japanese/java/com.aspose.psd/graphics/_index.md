---
title: "Graphics"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "現在のアセンブリで使用されているグラフィックスエンジンに従ってグラフィックスを表します。"
type: docs
weight: 49
url: /ja/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

現在のアセンブリで使用されているグラフィックスエンジンに従ってグラフィックスを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Graphics クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | 太字テキストスタイルのサイズ係数を取得します |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | 斜体テキストスタイルのサイズ係数を取得します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | 効果を適用します。 |
| [beginUpdate()](#beginUpdate--) | 以下のグラフィック操作のキャッシュを開始します。 |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | 指定された色でグラフィックサーフェスをクリアします。 |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Rectangle 構造体で指定された楕円の一部を表す弧を描画します。 |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | RectangleF 構造体で指定された楕円の一部を表す弧を描画します。 |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | 座標のペア、幅、高さで指定された楕円の一部を表す弧を描画します。 |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | 座標のペア、幅、高さで指定された楕円の一部を表す弧を描画します。 |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | 四つの  Point  構造体で定義されたベジエスプラインを描画します。 |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 四つの  PointF  構造体で定義されたベジエスプラインを描画します。 |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | 点を表す4つの座標の順序対で定義されたベジエスプラインを描画します。 |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) |   PointF  構造体の配列からベジエスプラインの系列を描画します。 |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) |   Point  構造体の配列からベジエスプラインの系列を描画します。 |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) |   PointF  構造体の配列で定義された閉じたカーディナルスプラインを描画します。 |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | 指定された張力を使用して、  PointF  構造体の配列で定義された閉じたカーディナルスプラインを描画します。 |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) |   Point  構造体の配列で定義された閉じたカーディナルスプラインを描画します。 |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | 指定された張力を使用して、  Point  構造体の配列で定義された閉じたカーディナルスプラインを描画します。 |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | 指定された  PointF  構造体の配列を通るカーディナルスプラインを描画します。 |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | 指定された張力を使用して、指定された  PointF  構造体の配列を通るカーディナルスプラインを描画します。 |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | 指定された  PointF  構造体の配列を通るカーディナルスプラインを描画します。 |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | 指定された張力を使用して、指定された  PointF  構造体の配列を通るカーディナルスプラインを描画します。 |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | 指定された  Point  構造体の配列を通るカーディナルスプラインを描画します。 |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | 指定された張力を使用して、指定された  Point  構造体の配列を通るカーディナルスプラインを描画します。 |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | 指定された張力を使用して、指定された  Point  構造体の配列を通るカーディナルスプラインを描画します。 |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | 境界  Rectangle  構造体で指定された楕円を描画します。 |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | 境界  RectangleF で定義された楕円を描画します。 |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | 座標のペア、高さ、幅で指定された境界矩形で定義された楕円を描画します。 |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | 座標のペア、高さ、幅で指定された境界矩形で定義された楕円を描画します。 |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | 指定された  Image  を、元の物理サイズのままで、指定された位置に描画します。 |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | 指定された  Image  を、元の物理サイズのままで、指定された位置に描画します。 |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | 指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | 指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | 指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | 指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | 指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | 指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | 指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | 指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | 指定された  Image  を、元の物理サイズのままで、指定された位置に描画します。 |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | 指定された画像を、元の物理サイズのままで、座標のペアで指定された位置に描画します。 |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | 指定された  Image  を、指定された位置に、指定されたサイズで描画します。 |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | 指定された画像を、元の物理サイズのままで、指定された位置に描画します。 |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 指定された画像を、元の物理サイズのままで、指定された位置に描画します。 |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | 指定された画像を、元の物理サイズのままで、座標のペアで指定された位置に描画します。 |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | 指定された画像を、元の物理サイズのままで、指定された位置に描画します。 |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 指定された画像をスケーリングせずに描画し、必要に応じて指定された矩形に収まるようにクリップします。 |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | 二つの  Point  構造体を接続する線を描画します。 |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 二つの  PointF  構造体を接続する線を描画します。 |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | 座標ペアで指定された2つの点を結ぶ線を描画します。 |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | 座標ペアで指定された2つの点を結ぶ線を描画します。 |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | PointF 構造体の配列を結ぶ一連の線分を描画します。 |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Point 構造体の配列を結ぶ一連の線分を描画します。 |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | com.aspose.psd.graphicsPath を描画します。 |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Rectangle 構造体で指定された楕円と2本の放射線で定義されたパイ形状を描画します。 |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | RectangleF 構造体で指定された楕円と2本の放射線で定義されたパイ形状を描画します。 |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | 座標ペア、幅、高さ、そして2本の放射線で指定された楕円で定義されたパイ形状を描画します。 |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | 座標ペア、幅、高さ、そして2本の放射線で指定された楕円で定義されたパイ形状を描画します。 |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | PointF 構造体の配列で定義された多角形を描画します。 |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Point 構造体の配列で定義された多角形を描画します。 |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Rectangle 構造体で指定された矩形を描画します。 |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | RectangleF 構造体で指定された矩形を描画します。 |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | 座標ペア、幅、高さで指定された矩形を描画します。 |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | 座標ペア、幅、高さで指定された矩形を描画します。 |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | RectangleF 構造体で指定された一連の矩形を描画します。 |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Rectangle 構造体で指定された一連の矩形を描画します。 |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | 指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用して、指定された位置に指定されたテキスト文字列を描画します。 |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | 指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、指定された com.aspose.psd.stringFormat の書式属性を利用して、指定された位置に指定されたテキスト文字列を描画します。 |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | 指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用して、指定された矩形内に指定されたテキスト文字列を描画します。 |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | 指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、指定された com.aspose.psd.stringFormat の書式属性を利用して、指定された矩形内に指定されたテキスト文字列を描画します。 |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | 指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用して、指定された位置に指定されたテキスト文字列を描画します。 |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | 指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、指定された com.aspose.psd.stringFormat の書式属性を利用して、指定された位置に指定されたテキスト文字列を描画します。 |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | 指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、Adobe 互換方式で指定された矩形内に指定されたテキスト文字列を描画します。 |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | 指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、Adobe 互換方式で指定された位置に指定されたテキスト文字列を描画します。 |
| [endUpdate()](#endUpdate--) | BeginUpdate が呼び出された後に開始されたグラフィック操作のキャッシュを終了します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | com.aspose.psd.PointF 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。 |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | com.aspose.psd.PointF 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードを使用して塗りつぶします。 |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | com.aspose.psd.PointF 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードとテンションを使用して塗りつぶします。 |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | com.aspose.psd.Point 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。 |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | 指定された塗りモードを使用して、com.aspose.psd.Point 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。 |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | 指定された塗りモードとテンションを使用して、com.aspose.psd.Point 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。 |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | com.aspose.psd.Rectangle 構造体で指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。 |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | com.aspose.psd.RectangleF 構造体で指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。 |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | 座標のペア、幅、および高さで指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。 |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | 座標のペア、幅、および高さで指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。 |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | com.aspose.psd.graphicsPath の内部を塗りつぶします。 |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | com.aspose.psd.RectangleF 構造体で指定された楕円と2本の放射線によって定義されたパイセクションの内部を塗りつぶします。 |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | com.aspose.psd.RectangleF 構造体で指定された楕円と2本の放射線によって定義されたパイセクションの内部を塗りつぶします。 |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | 座標のペア、幅、高さ、そして2本の放射線で指定された楕円によって定義されたパイセクションの内部を塗りつぶします。 |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | 座標のペア、幅、高さ、そして2本の放射線で指定された楕円によって定義されたパイセクションの内部を塗りつぶします。 |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | com.aspose.psd.PointF 構造体で指定されたポイントの配列と FillMode.Alternate を使用して定義されたポリゴンの内部を塗りつぶします。 |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | com.aspose.psd.PointF 構造体で指定されたポイントの配列と指定された塗りモードを使用して定義されたポリゴンの内部を塗りつぶします。 |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | com.aspose.psd.Point 構造体で指定されたポイントの配列と FillMode.Alternate を使用して定義されたポリゴンの内部を塗りつぶします。 |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | com.aspose.psd.Point 構造体で指定されたポイントの配列と指定された塗りモードを使用して定義されたポリゴンの内部を塗りつぶします。 |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Rectangle 構造体で指定された矩形の内部を塗りつぶします。 |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | RectangleF 構造体で指定された矩形の内部を塗りつぶします。 |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | 座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。 |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | 座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。 |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | RectangleF 構造体で指定された一連の矩形の内部を塗りつぶします。 |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Rectangle 構造体で指定された一連の矩形の内部を塗りつぶします。 |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | com.aspose.psd.region の内部を塗りつぶします。 |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | クリップ領域を取得または設定します。 |
| [getCompositingQuality()](#getCompositingQuality--) | 合成品質を取得または設定します。 |
| [getDpiX()](#getDpiX--) | この com.aspose.psd.graphics の水平解像度を取得します。 |
| [getDpiY()](#getDpiY--) | この com.aspose.psd.graphics の垂直解像度を取得します。 |
| [getImage()](#getImage--) | 画像を取得します。 |
| [getInterpolationMode()](#getInterpolationMode--) | 補間モードを取得または設定します。 |
| [getPageScale()](#getPageScale--) | この com.aspose.psd.graphics のワールド単位とページ単位間のスケーリングを取得または設定します。 |
| [getPageUnit()](#getPageUnit--) | この com.aspose.psd.graphics で使用されるページ座標の測定単位を取得または設定します。 |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | 描画用の塗りつぶし可能なvactor画像を作成するために使用される画像オプションを取得または設定します。 |
| [getSmoothingMode()](#getSmoothingMode--) | スムージングモードを取得または設定します。 |
| [getTextRenderingHint()](#getTextRenderingHint--) | テキストレンダリングヒントを取得または設定します。 |
| [getTransform()](#getTransform--) | この com.aspose.psd.graphics の幾何学的ワールド変換のコピーを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | graphics が BeginUpdate 呼び出し状態にあるかどうかを示す値を取得します。 |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | 文字列を [GraphicsPath](../../com.aspose.psd/graphicspath) クラスを使用して測定します。 |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | 文字列を測定します。 |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | 指定されたパラメーターで指定されたテキスト文字列を測定します |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | この com.aspose.psd.Graphics のローカル幾何変換を表す com.aspose.psd.Matrix を、指定された com.aspose.psd.Matrix で前置し、指定された com.aspose.psd.matrix を掛け合わせます。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | この com.aspose.psd.Graphics のローカル幾何変換を表す com.aspose.psd.Matrix を、指定された順序で指定された com.aspose.psd.Matrix と乗算します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | com.aspose.psd.graphics.Transform プロパティを単位行列にリセットします。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | ローカル幾何変換を指定された量だけ回転させます。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | ローカル幾何変換を指定された順序で指定された量だけ回転させます。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | ローカル幾何変換を指定された量で拡大縮小します。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | ローカル幾何変換を指定された順序で指定された量で拡大縮小します。 |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | クリップ領域を取得または設定します。 |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | 合成品質を取得または設定します。 |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | 補間モードを取得または設定します。 |
| [setPageScale(float value)](#setPageScale-float-) | この com.aspose.psd.graphics のワールド単位とページ単位間のスケーリングを取得または設定します。 |
| [setPageUnit(int value)](#setPageUnit-int-) | この com.aspose.psd.graphics で使用されるページ座標の測定単位を取得または設定します。 |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | 描画用の塗りつぶし可能なvactor画像を作成するために使用される画像オプションを取得または設定します。 |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | スムージングモードを取得または設定します。 |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | テキストレンダリングヒントを取得または設定します。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | この com.aspose.psd.graphics の幾何学的ワールド変換のコピーを取得または設定します。 |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ローカルの幾何変換を指定された寸法だけ平行移動します。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ローカルの幾何変換を指定された寸法で、指定された順序で平行移動します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Graphics クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | ソース画像。 |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


太字テキストスタイルのサイズ係数を取得します

GDI が常に Regular スタイルの測定のみを提供するため、マジックナンバーを使用しています。

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


斜体テキストスタイルのサイズ係数を取得します

GDI が常に Regular スタイルの測定のみを提供するため、マジックナンバーを使用しています。

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


効果を適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| エフェクト | com.aspose.internal.IEffect | 適用するエフェクト。 |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


以下の graphics 操作のキャッシュを開始します。その後に適用される graphics エフェクトはすぐには適用されず、代わりに EndUpdate がすべてのエフェクトを一度に適用します。

BeginUpdate が呼び出された後のエフェクトは、EndUpdate が呼び出されない場合は適用されないことに注意してください。

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


指定された色でグラフィックサーフェスをクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | graphics サーフェスをクリアする色。 |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Rectangle 構造体で指定された楕円の一部を表す弧を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 円弧の色、幅、スタイルを決定する Pen。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 楕円の境界を定義する RectangleF 構造体。 |
| 開始角度 | float | x 軸から円弧の開始点まで時計回りに測定された角度（度）。 |
| 掃引角度 | float | 円弧の終点まで、  startAngle  パラメータから時計回りに測定された角度（度）です。 |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


RectangleF 構造体で指定された楕円の一部を表す弧を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 円弧の色、幅、スタイルを決定する Pen。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 楕円の境界を定義する RectangleF 構造体。 |
| 開始角度 | float | x 軸から円弧の開始点まで時計回りに測定された角度（度）。 |
| 掃引角度 | float | 円弧の終点まで、  startAngle  パラメータから時計回りに測定された角度（度）です。 |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


座標のペア、幅、高さで指定された楕円の一部を表す弧を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 円弧の色、幅、スタイルを決定する Pen。 |
| x | float | 楕円を定義する矩形の左上隅の x 座標です。 |
| y | float | 楕円を定義する矩形の左上隅の y 座標です。 |
| 幅 | float | 楕円を定義する矩形の幅です。 |
| 高さ | float | 楕円を定義する矩形の高さです。 |
| 開始角度 | float | x 軸から円弧の開始点まで時計回りに測定された角度（度）。 |
| 掃引角度 | float | 円弧の終点まで、  startAngle  パラメータから時計回りに測定された角度（度）です。 |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


座標のペア、幅、高さで指定された楕円の一部を表す弧を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 円弧の色、幅、スタイルを決定する Pen。 |
| x | int | 楕円を定義する矩形の左上隅の x 座標です。 |
| y | int | 楕円を定義する矩形の左上隅の y 座標です。 |
| 幅 | int | 楕円を定義する矩形の幅です。 |
| 高さ | int | 楕円を定義する矩形の高さです。 |
| 開始角度 | int | x 軸から円弧の開始点まで時計回りに測定された角度（度）。 |
| 掃引角度 | int | 円弧の終点まで、  startAngle  パラメータから時計回りに測定された角度（度）です。 |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


四つの  Point  構造体で定義されたベジエスプラインを描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  構造体は曲線の色、幅、スタイルを決定します。 |
| pt1 | [Point](../../com.aspose.psd/point) | Point  構造体は曲線の開始点を表します。 |
| pt2 | [Point](../../com.aspose.psd/point) | Point  構造体は曲線の最初の制御点を表します。 |
| pt3 | [Point](../../com.aspose.psd/point) | Point  構造体は曲線の2番目の制御点を表します。 |
| pt4 | [Point](../../com.aspose.psd/point) | Point  構造体は曲線の終了点を表します。 |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


四つの  PointF  構造体で定義されたベジエスプラインを描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen は曲線の色、幅、スタイルを決定します。 |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF  構造体は曲線の開始点を表します。 |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF  構造体は曲線の最初の制御点を表します。 |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF  構造体は曲線の2番目の制御点を表します。 |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF  構造体は曲線の終了点を表します。 |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


点を表す4つの座標の順序対で定義されたベジエスプラインを描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen は曲線の色、幅、スタイルを決定します。 |
| x1 | float | 曲線の開始点の x 座標です。 |
| y1 | float | 曲線の開始点の y 座標です。 |
| x2 | float | 曲線の最初の制御点の x 座標です。 |
| y2 | float | 曲線の最初の制御点の y 座標です。 |
| x3 | float | 曲線の2番目の制御点の x 座標です。 |
| y3 | float | 曲線の第2制御点の y 座標です。 |
| x4 | float | 曲線の終点の x 座標です。 |
| y4 | float | 曲線の終点の y 座標です。 |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


  PointF  構造体の配列からベジエスプラインの系列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen は曲線の色、幅、スタイルを決定します。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 曲線を決定する点を表す PointF 構造体の配列。 |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


  Point  構造体の配列からベジエスプラインの系列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen は曲線の色、幅、スタイルを決定します。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 曲線を決定する点を表す Point 構造体の配列。 |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


PointF 構造体の配列で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 と FillMode.Alternate 塗りモードを使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | スプラインを定義する PointF 構造体の配列。 |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


指定されたテンションを使用して、PointF 構造体の配列で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトの FillMode.Alternate 塗りモードを使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | スプラインを定義する PointF 構造体の配列。 |
| テンション | float | 曲線のテンションを指定する、0.0F 以上の値です。 |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Point 構造体の配列で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 と FillMode.Alternate 塗りモードを使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [Point\[\]](../../com.aspose.psd/point) | スプラインを定義する Point 構造体の配列。 |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


指定されたテンションを使用して、Point 構造体の配列で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトの FillMode.Alternate 塗りモードを使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [Point\[\]](../../com.aspose.psd/point) | スプラインを定義する Point 構造体の配列。 |
| テンション | float | 曲線のテンションを指定する、0.0F 以上の値です。 |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


指定された PointF 構造体の配列を通ってカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 を使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | スプラインを定義する PointF 構造体の配列。 |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


指定された張力を使用して、指定された  PointF  構造体の配列を通るカーディナルスプラインを描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 曲線を定義する点を表す PointF 構造体の配列。 |
| テンション | float | 曲線のテンションを指定する、0.0F 以上の値です。 |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


指定された PointF 構造体の配列を通ってカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。このメソッドはデフォルトのテンション 0.5 を使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | スプラインを定義する PointF 構造体の配列。 |
| オフセット | int | points パラメータの配列の最初の要素から曲線の開始点までのオフセット。 |
| numberOfSegments | int | 曲線の開始点の後に含めるセグメント数です。 |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


指定されたテンションを使用して、指定された PointF 構造体の配列を通ってカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | スプラインを定義する PointF 構造体の配列。 |
| オフセット | int | points パラメータの配列の最初の要素から曲線の開始点までのオフセット。 |
| numberOfSegments | int | 曲線の開始点の後に含めるセグメント数です。 |
| テンション | float | 曲線のテンションを指定する、0.0F 以上の値です。 |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


指定された  Point  構造体の配列を通るカーディナルスプラインを描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [Point\[\]](../../com.aspose.psd/point) | スプラインを定義する Point 構造体の配列。 |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


指定された張力を使用して、指定された  Point  構造体の配列を通るカーディナルスプラインを描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [Point\[\]](../../com.aspose.psd/point) | スプラインを定義する Point 構造体の配列。 |
| テンション | float | 曲線のテンションを指定する、0.0F 以上の値です。 |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


指定された張力を使用して、指定された  Point  構造体の配列を通るカーディナルスプラインを描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 曲線の色、幅、高さを決定する Pen。 |
| points | [Point\[\]](../../com.aspose.psd/point) | スプラインを定義する Point 構造体の配列。 |
| オフセット | int | points パラメータの配列の最初の要素から曲線の開始点までのオフセット。 |
| numberOfSegments | int | 曲線の開始点の後に含めるセグメント数です。 |
| テンション | float | 曲線のテンションを指定する、0.0F 以上の値です。 |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


境界  Rectangle  構造体で指定された楕円を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 楕円の色、幅、スタイルを決定する Pen。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle 構造体は楕円の境界を定義します。 |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


境界  RectangleF で定義された楕円を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 楕円の色、幅、スタイルを決定する Pen。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 楕円の境界を定義する RectangleF 構造体。 |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


座標のペア、高さ、幅で指定された境界矩形で定義された楕円を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 楕円の色、幅、スタイルを決定する Pen。 |
| x | float | 楕円を定義する外接矩形の左上隅の x 座標。 |
| y | float | 楕円を定義する外接矩形の左上隅の y 座標。 |
| 幅 | float | 楕円を定義する外接矩形の幅。 |
| 高さ | float | 楕円を定義する外接矩形の高さ。 |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


座標のペア、高さ、幅で指定された境界矩形で定義された楕円を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 楕円の色、幅、スタイルを決定する Pen。 |
| x | int | 楕円を定義する外接矩形の左上隅の x 座標。 |
| y | int | 楕円を定義する外接矩形の左上隅の y 座標。 |
| 幅 | int | 楕円を定義する外接矩形の幅。 |
| 高さ | int | 楕円を定義する外接矩形の高さ。 |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


指定された  Image  を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| point | [Point](../../com.aspose.psd/point) | 描画された画像の左上隅の位置を表す Point 構造体。 |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


指定された  Image  を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| point | [PointF](../../com.aspose.psd/pointf) | 描画された画像の左上隅を表す PointF 構造体。 |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 描画する画像。 |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 平行四辺形を定義する 3 つの PointF 構造体の配列。 |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 描画する画像。 |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 平行四辺形を定義する 3 つの PointF 構造体の配列。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | ソース矩形。 |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 描画する画像。 |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 平行四辺形を定義する 3 つの PointF 構造体の配列。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | ソース矩形。 |
| srcUnit | int | 測定単位。 |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 描画する画像。 |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 平行四辺形を定義する 3 つの PointF 構造体の配列。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | ソース矩形。 |
| srcUnit | int | 測定単位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 画像属性。 |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 描画する画像。 |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 平行四辺形を定義する 3 つの PointF 構造体の配列。 |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 描画する画像。 |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 平行四辺形を定義する 3 つの PointF 構造体の配列。 |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | ソース矩形。 |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 描画する画像。 |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 平行四辺形を定義する 3 つの PointF 構造体の配列。 |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | ソース矩形。 |
| srcUnit | int | 測定単位。 |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


指定された  image  の指定された部分を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 描画する画像。 |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 平行四辺形を定義する 3 つの PointF 構造体の配列。 |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | ソース矩形。 |
| srcUnit | int | 測定単位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 画像属性。 |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 描画された画像の位置とサイズを指定する Rectangle 構造体。 |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | ソース矩形。 |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 宛先矩形。 |
| graphicsUnit | int | グラフィックス単位。 |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | ソース矩形。 |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 宛先矩形。 |
| graphicsUnit | int | グラフィックス単位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 画像属性。 |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 宛先矩形。 |
| graphicsUnit | int | グラフィックス単位。 |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 宛先矩形。 |
| graphicsUnit | int | グラフィックス単位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 画像属性。 |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 描画された画像の位置とサイズを指定する RectangleF 構造体。 |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | ソース矩形。 |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 宛先矩形。 |
| graphicsUnit | int | グラフィックス単位。 |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | ソース矩形。 |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 宛先矩形。 |
| graphicsUnit | int | 使用するグラフィックス単位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 使用する画像属性。 |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 宛先矩形。 |
| graphicsUnit | int | グラフィックス単位。 |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 描画先の矩形。 |
| graphicsUnit | int | グラフィックス単位。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 画像属性。 |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


指定された  Image  を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| x | float | 描画された画像の左上隅の x 座標。 |
| y | float | 描画された画像の左上隅の y 座標です。 |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| x | float | 描画された画像の左上隅の x 座標。 |
| y | float | 描画された画像の左上隅の y 座標です。 |
| 幅 | float | 描画された画像の幅です。 |
| 高さ | float | 描画された画像の高さです。 |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


指定された画像を、元の物理サイズのままで、座標のペアで指定された位置に描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| x | int | 描画された画像の左上隅の x 座標。 |
| y | int | 描画された画像の左上隅の y 座標です。 |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


指定された  Image  を、指定された位置に、指定されたサイズで描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| x | int | 描画された画像の左上隅の x 座標。 |
| y | int | 描画された画像の左上隅の y 座標です。 |
| 幅 | int | 描画された画像の幅です。 |
| 高さ | int | 描画された画像の高さです。 |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


指定された画像を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| point | [Point](../../com.aspose.psd/point) | 描画された画像の左上隅を指定する Point 構造体です。 |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


指定された画像を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 描画された画像の左上隅を指定する Rectangle です。Rectangle の X と Y プロパティが左上隅を指定し、Width と Height プロパティは無視されます。 |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


指定された画像を、元の物理サイズのままで、座標のペアで指定された位置に描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| x | int | 描画された画像の左上隅の x 座標。 |
| y | int | 描画された画像の左上隅の y 座標です。 |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


指定された画像を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| x | int | 描画された画像の左上隅の x 座標。 |
| y | int | 描画された画像の左上隅の y 座標です。 |
| 幅 | int | このパラメーターは使用されません。 |
| 高さ | int | このパラメーターは使用されません。 |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


指定された画像をスケーリングせずに描画し、必要に応じて指定された矩形に収まるようにクリップします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 描画に使用する画像。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 画像を描画する Rectangle です。 |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


二つの  Point  構造体を接続する線を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 線の色、幅、スタイルを決定する Pen です。 |
| point1 | [Point](../../com.aspose.psd/point) | 接続する最初の点を表す Point 構造体です。 |
| point2 | [Point](../../com.aspose.psd/point) | 接続する2番目の点を表す Point 構造体です。 |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


二つの  PointF  構造体を接続する線を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 線の色、幅、スタイルを決定する Pen です。 |
| point1 | [PointF](../../com.aspose.psd/pointf) | 接続する最初の点を表す PointF 構造体です。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 接続する2番目の点を表す PointF 構造体です。 |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


座標ペアで指定された2つの点を結ぶ線を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 線の色、幅、スタイルを決定する Pen です。 |
| x1 | float | 最初の点の x 座標です。 |
| y1 | float | 最初の点の y 座標です。 |
| x2 | float | 2番目の点の x 座標です。 |
| y2 | float | 2番目の点の y 座標です。 |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


座標ペアで指定された2つの点を結ぶ線を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 線の色、幅、スタイルを決定する Pen です。 |
| x1 | int | 最初の点の x 座標です。 |
| y1 | int | 最初の点の y 座標です。 |
| x2 | int | 2番目の点の x 座標です。 |
| y2 | int | 2番目の点の y 座標です。 |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


PointF 構造体の配列を結ぶ一連の線分を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 線分の色、幅、スタイルを決定する Pen です。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 接続する点を表す PointF 構造体の配列です。 |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Point 構造体の配列を結ぶ一連の線分を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 線分の色、幅、スタイルを決定する Pen です。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 接続する点を表す Point 構造体の配列です。 |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


com.aspose.psd.graphicsPath を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | パスの色、幅、スタイルを決定する com.aspose.psd.Pen です。 |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 描画するための com.aspose.psd.GraphicsPath です。 |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Rectangle 構造体で指定された楕円と2本の放射線で定義されたパイ形状を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | パイ形状の色、幅、スタイルを決定する Pen です。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | パイ形状が元になる楕円を定義する境界矩形を表す Rectangle 構造体です。 |
| 開始角度 | float | x 軸からパイ形状の最初の辺まで、時計回りに測定した角度（度）です。 |
| 掃引角度 | float | startAngle パラメーターからパイ形状の2番目の辺まで、時計回りに測定した角度（度）です。 |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


RectangleF 構造体で指定された楕円と2本の放射線で定義されたパイ形状を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | パイ形状の色、幅、スタイルを決定する Pen です。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  構造体は、パイ形状が生成される楕円を定義する境界矩形を表します。 |
| 開始角度 | float | x 軸からパイ形状の最初の辺まで、時計回りに測定した角度（度）です。 |
| 掃引角度 | float | startAngle パラメーターからパイ形状の2番目の辺まで、時計回りに測定した角度（度）です。 |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


座標ペア、幅、高さ、そして2本の放射線で指定された楕円で定義されたパイ形状を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | パイ形状の色、幅、スタイルを決定する Pen です。 |
| x | float | パイ形状が生成される楕円を定義する境界矩形の左上隅の x 座標です。 |
| y | float | パイ形状が生成される楕円を定義する境界矩形の左上隅の y 座標です。 |
| 幅 | float | パイ形状が生成される楕円を定義する境界矩形の幅です。 |
| 高さ | float | パイ形状が生成される楕円を定義する境界矩形の高さです。 |
| 開始角度 | float | x 軸からパイ形状の最初の辺まで、時計回りに測定した角度（度）です。 |
| 掃引角度 | float | startAngle パラメーターからパイ形状の2番目の辺まで、時計回りに測定した角度（度）です。 |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


座標ペア、幅、高さ、そして2本の放射線で指定された楕円で定義されたパイ形状を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | パイ形状の色、幅、スタイルを決定する Pen です。 |
| x | int | パイ形状が生成される楕円を定義する境界矩形の左上隅の x 座標です。 |
| y | int | パイ形状が生成される楕円を定義する境界矩形の左上隅の y 座標です。 |
| 幅 | int | パイ形状が生成される楕円を定義する境界矩形の幅です。 |
| 高さ | int | パイ形状が生成される楕円を定義する境界矩形の高さです。 |
| 開始角度 | int | x 軸からパイ形状の最初の辺まで、時計回りに測定した角度（度）です。 |
| 掃引角度 | int | startAngle パラメーターからパイ形状の2番目の辺まで、時計回りに測定した角度（度）です。 |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


PointF 構造体の配列で定義された多角形を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  は、ポリゴンの色、幅、スタイルを決定します。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | PointF  構造体の配列は、ポリゴンの頂点を表します。 |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Point 構造体の配列で定義された多角形を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  は、ポリゴンの色、幅、スタイルを決定します。 |
| points | [Point\[\]](../../com.aspose.psd/point) | Point  構造体の配列は、ポリゴンの頂点を表します。 |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Rectangle 構造体で指定された矩形を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  は、矩形の色、幅、スタイルを決定します。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  構造体は、描画する矩形を表します。 |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


RectangleF 構造体で指定された矩形を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  は、矩形の色、幅、スタイルを決定します。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  構造体は、描画する矩形を表します。 |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


座標ペア、幅、高さで指定された矩形を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  は、矩形の色、幅、スタイルを決定します。 |
| x | float | 描画する矩形の左上隅の x 座標です。 |
| y | float | 描画する矩形の左上隅の y 座標です。 |
| 幅 | float | 描画する矩形の幅です。 |
| 高さ | float | 描画する矩形の高さです。 |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


座標ペア、幅、高さで指定された矩形を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  は、矩形の色、幅、スタイルを決定します。 |
| x | int | 描画する矩形の左上隅の x 座標です。 |
| y | int | 描画する矩形の左上隅の y 座標です。 |
| 幅 | int | 描画する矩形の幅です。 |
| 高さ | int | 描画する矩形の高さです。 |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


RectangleF 構造体で指定された一連の矩形を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  は、矩形の輪郭の色、幅、スタイルを決定します。 |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | RectangleF  構造体の配列は、描画する矩形を表します。 |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Rectangle 構造体で指定された一連の矩形を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  は、矩形の輪郭の色、幅、スタイルを決定します。 |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Rectangle  構造体の配列は、描画する矩形を表します。 |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用して、指定された位置に指定されたテキスト文字列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | java.lang.String | 描画する文字列です。 |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  は、文字列のテキスト形式を定義します。 |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  は、描画されたテキストの色とテクスチャを決定します。 |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  構造体は描画されたテキストの左上隅を指定します。 |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、指定された com.aspose.psd.stringFormat の書式属性を利用して、指定された位置に指定されたテキスト文字列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | java.lang.String | 描画する文字列です。 |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  は、文字列のテキスト形式を定義します。 |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  は、描画されたテキストの色とテクスチャを決定します。 |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  構造体は描画されたテキストの左上隅を指定します。 |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  描画されたテキストに適用される行間や配置などの書式属性を指定する。 |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用して、指定された矩形内に指定されたテキスト文字列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | java.lang.String | 描画する文字列です。 |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  は、文字列のテキスト形式を定義します。 |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  は、描画されたテキストの色とテクスチャを決定します。 |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  構造体は描画されたテキストの位置を指定します。 |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、指定された com.aspose.psd.stringFormat の書式属性を利用して、指定された矩形内に指定されたテキスト文字列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | java.lang.String | 描画する文字列です。 |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  は、文字列のテキスト形式を定義します。 |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  は、描画されたテキストの色とテクスチャを決定します。 |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  構造体は描画されたテキストの位置を指定します。 |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  描画されたテキストに適用される行間や配置などの書式属性を指定する。 |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用して、指定された位置に指定されたテキスト文字列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | java.lang.String | 描画する文字列です。 |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  は、文字列のテキスト形式を定義します。 |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  は、描画されたテキストの色とテクスチャを決定します。 |
| x | float | 描画されたテキストの左上隅の x 座標。 |
| y | float | 描画されたテキストの左上隅の y 座標。 |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、指定された com.aspose.psd.stringFormat の書式属性を利用して、指定された位置に指定されたテキスト文字列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | java.lang.String | 描画する文字列です。 |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  は、文字列のテキスト形式を定義します。 |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  は、描画されたテキストの色とテクスチャを決定します。 |
| x | float | 描画されたテキストの左上隅の x 座標。 |
| y | float | 描画されたテキストの左上隅の y 座標。 |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  描画されたテキストに適用される行間や配置などの書式属性を指定する。 |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、Adobe 互換方式で指定された矩形内に指定されたテキスト文字列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | java.lang.String | 描画する文字列です。 |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  は、文字列のテキスト形式を定義します。 |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  は、描画されたテキストの色とテクスチャを決定します。 |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  構造体は描画されたテキストの位置を指定します。 |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  描画されたテキストに適用される行間や配置などの書式属性を指定する。 |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


指定された com.aspose.psd.Brush と com.aspose.psd.Font オブジェクトを使用し、Adobe 互換方式で指定された位置に指定されたテキスト文字列を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | java.lang.String | 描画する文字列です。 |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  は、文字列のテキスト形式を定義します。 |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  は、描画されたテキストの色とテクスチャを決定します。 |
| x | float | 描画されたテキストの左上隅の x 座標。 |
| y | float | 描画されたテキストの左上隅の y 座標。 |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


BeginUpdate が呼び出された後に開始されたグラフィック操作のキャッシュを終了します。このメソッドを呼び出すと、直前のグラフィック操作が一度に適用されます。

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
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


com.aspose.psd.PointF 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 と FillMode.Alternate 塗りつぶしモードを使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | スプラインを定義する com.aspose.psd.PointF 構造体の配列。 |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


指定された塗りつぶしモードを使用して、com.aspose.psd.PointF 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 を使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | スプラインを定義する com.aspose.psd.PointF 構造体の配列。 |
| fillmode | int | 曲線がどのように塗りつぶされるかを決定する com.aspose.psd.FillMode 列挙体のメンバー。 |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


com.aspose.psd.PointF 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードとテンションを使用して塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | スプラインを定義する com.aspose.psd.PointF 構造体の配列。 |
| fillmode | int | 曲線がどのように塗りつぶされるかを決定する com.aspose.psd.FillMode 列挙体のメンバー。 |
| テンション | float | 曲線のテンションを指定する、0.0F 以上の値です。 |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


com.aspose.psd.Point 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 と FillMode.Alternate 塗りつぶしモードを使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | スプラインを定義する com.aspose.psd.Point 構造体の配列。 |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


指定された塗りつぶしモードを使用して、com.aspose.psd.Point 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 を使用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | スプラインを定義する com.aspose.psd.Point 構造体の配列。 |
| fillmode | int | 曲線がどのように塗りつぶされるかを決定する com.aspose.psd.FillMode 列挙体のメンバー。 |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


指定された塗りモードとテンションを使用して、com.aspose.psd.Point 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | スプラインを定義する com.aspose.psd.Point 構造体の配列。 |
| fillmode | int | 曲線がどのように塗りつぶされるかを決定する com.aspose.psd.FillMode 列挙体のメンバー。 |
| テンション | float | 曲線のテンションを指定する、0.0F 以上の値です。 |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


com.aspose.psd.Rectangle 構造体で指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 楕円を定義する境界矩形を表す com.aspose.psd.Rectangle 構造体。 |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


com.aspose.psd.RectangleF 構造体で指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 楕円を定義する境界矩形を表す com.aspose.psd.RectangleF 構造体。 |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


座標のペア、幅、および高さで指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| x | float | 楕円を定義する外接矩形の左上隅の x 座標。 |
| y | float | 楕円を定義する外接矩形の左上隅の y 座標。 |
| 幅 | float | 楕円を定義する外接矩形の幅。 |
| 高さ | float | 楕円を定義する外接矩形の高さ。 |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


座標のペア、幅、および高さで指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| x | int | 楕円を定義する外接矩形の左上隅の x 座標。 |
| y | int | 楕円を定義する外接矩形の左上隅の y 座標。 |
| 幅 | int | 楕円を定義する外接矩形の幅。 |
| 高さ | int | 楕円を定義する外接矩形の高さ。 |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


com.aspose.psd.graphicsPath の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 塗りつぶすパスを表す com.aspose.psd.GraphicsPath。 |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


com.aspose.psd.RectangleF 構造体で指定された楕円と2本の放射線によって定義されたパイセクションの内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | パイセクションが始まる楕円を定義する境界矩形を表す com.aspose.psd.Rectangle 構造体。 |
| 開始角度 | float | パイセクションの第一側まで、x 軸から時計回りに測定した角度（度）です。 |
| 掃引角度 | float | パイセクションの第二側まで、startAngle パラメータから時計回りに測定した角度（度）です。 |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


com.aspose.psd.RectangleF 構造体で指定された楕円と2本の放射線によって定義されたパイセクションの内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | パイセクションが始まる楕円を定義する境界矩形を表す com.aspose.psd.RectangleF 構造体。 |
| 開始角度 | float | パイセクションの第一側まで、x 軸から時計回りに測定した角度（度）です。 |
| 掃引角度 | float | パイセクションの第二側まで、startAngle パラメータから時計回りに測定した角度（度）です。 |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


座標のペア、幅、高さ、そして2本の放射線で指定された楕円によって定義されたパイセクションの内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| x | float | パイセクションが始まる楕円を定義する境界矩形の左上隅の x 座標。 |
| y | float | パイセクションが始まる楕円を定義する境界矩形の左上隅の y 座標。 |
| 幅 | float | パイセクションが始まる楕円を定義するバウンディング矩形の幅。 |
| 高さ | float | パイセクションが始まる楕円を定義するバウンディング矩形の高さ。 |
| 開始角度 | float | パイセクションの第一側まで、x 軸から時計回りに測定した角度（度）です。 |
| 掃引角度 | float | パイセクションの第二側まで、startAngle パラメータから時計回りに測定した角度（度）です。 |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


座標のペア、幅、高さ、そして2本の放射線で指定された楕円によって定義されたパイセクションの内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| x | int | パイセクションが始まる楕円を定義する境界矩形の左上隅の x 座標。 |
| y | int | パイセクションが始まる楕円を定義する境界矩形の左上隅の y 座標。 |
| 幅 | int | パイセクションが始まる楕円を定義するバウンディング矩形の幅。 |
| 高さ | int | パイセクションが始まる楕円を定義するバウンディング矩形の高さ。 |
| 開始角度 | int | パイセクションの第一側まで、x 軸から時計回りに測定した角度（度）です。 |
| 掃引角度 | int | パイセクションの第二側まで、startAngle パラメータから時計回りに測定した角度（度）です。 |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


com.aspose.psd.PointF 構造体で指定されたポイントの配列と FillMode.Alternate を使用して定義されたポリゴンの内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 塗りつぶすポリゴンの頂点を表す com.aspose.psd.PointF 構造体の配列。 |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


com.aspose.psd.PointF 構造体で指定されたポイントの配列と指定された塗りモードを使用して定義されたポリゴンの内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 塗りつぶすポリゴンの頂点を表す com.aspose.psd.PointF 構造体の配列。 |
| fillMode | int | 塗りつぶしのスタイルを決定する com.aspose.psd.FillMode 列挙体のメンバー。 |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


com.aspose.psd.Point 構造体で指定されたポイントの配列と FillMode.Alternate を使用して定義されたポリゴンの内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 塗りつぶすポリゴンの頂点を表す com.aspose.psd.Point 構造体の配列。 |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


com.aspose.psd.Point 構造体で指定されたポイントの配列と指定された塗りモードを使用して定義されたポリゴンの内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| points | [Point\[\]](../../com.aspose.psd/point) | 塗りつぶすポリゴンの頂点を表す com.aspose.psd.Point 構造体の配列。 |
| fillMode | int | 塗りつぶしのスタイルを決定する com.aspose.psd.FillMode 列挙体のメンバー。 |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Rectangle 構造体で指定された矩形の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する Brush。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 塗りつぶす矩形を表す Rectangle 構造体。 |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


RectangleF 構造体で指定された矩形の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する Brush。 |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 塗りつぶす矩形を表す RectangleF 構造体。 |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する Brush。 |
| x | float | 塗りつぶす矩形の左上隅の x 座標。 |
| y | float | 塗りつぶす矩形の左上隅の y 座標。 |
| 幅 | float | 塗りつぶす矩形の幅。 |
| 高さ | float | 塗りつぶす矩形の高さ。 |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する Brush。 |
| x | int | 塗りつぶす矩形の左上隅の x 座標。 |
| y | int | 塗りつぶす矩形の左上隅の y 座標。 |
| 幅 | int | 塗りつぶす矩形の幅。 |
| 高さ | int | 塗りつぶす矩形の高さ。 |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


RectangleF 構造体で指定された一連の矩形の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する Brush。 |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | 塗りつぶす矩形を表す Rectangle 構造体の配列。 |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Rectangle 構造体で指定された一連の矩形の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する Brush。 |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | 塗りつぶす矩形を表す Rectangle 構造体の配列。 |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


com.aspose.psd.region の内部を塗りつぶします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 塗りつぶしの特性を決定する com.aspose.psd.Brush。 |
| region | [Region](../../com.aspose.psd/region) | 塗りつぶす領域を表す com.aspose.psd.Region。 |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClip() {#getClip--}
```
public Region getClip()
```


クリップ領域を取得または設定します。

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


合成品質を取得または設定します。

**Returns:**
int - 合成品質。
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


この com.aspose.psd.graphics の水平解像度を取得します。

**Returns:**
float - この com.aspose.psd.graphics がサポートする水平解像度（dpi）の値。
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


この com.aspose.psd.graphics の垂直解像度を取得します。

**Returns:**
float - この com.aspose.psd.graphics がサポートする垂直解像度（dpi）の値。
### getImage() {#getImage--}
```
public Image getImage()
```


画像を取得します。

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


補間モードを取得または設定します。

**Returns:**
int - 補間モード。
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


この com.aspose.psd.graphics のワールド単位とページ単位間のスケーリングを取得または設定します。

**Returns:**
float - この com.aspose.psd.graphics の世界単位とページ単位間のスケーリング。
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


この com.aspose.psd.graphics で使用されるページ座標の測定単位を取得または設定します。

**Returns:**
int - この com.aspose.psd.graphics でページ座標に使用される測定単位。
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


描画用の塗りつぶし可能なvactor画像を作成するために使用される画像オプションを取得または設定します。

値: 描画用のベクター画像を作成するために使用される画像オプション。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


スムージングモードを取得または設定します。

**Returns:**
int - スムージングモード。
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


テキストレンダリングヒントを取得または設定します。

**Returns:**
int - テキストレンダリングヒント。
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


この com.aspose.psd.graphics の幾何学的ワールド変換のコピーを取得または設定します。

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


graphics が BeginUpdate 呼び出し状態にあるかどうかを示す値を取得します。

**Returns:**
boolean - グラフィックスが BeginUpdate 呼び出し状態にある場合は True、そうでない場合は false。
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


文字列を [GraphicsPath](../../com.aspose.psd/graphicspath) クラスを使用して測定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | フォント。 |
| text | java.lang.String | テキスト。 |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


文字列を測定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | フォント。 |
|  | text | java.lang.String | テキスト。 |

--------------------

GDI の結果はイタリックの場合はほぼ常に無効で、ボールドスタイルの場合はしばしば無効です。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


指定されたパラメーターで指定されたテキスト文字列を測定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 測定するテキスト。 |
| font | [Font](../../com.aspose.psd/font) | 測定するフォント。 |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | レイアウト領域。 |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | 文字列フォーマット。 |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | プライベートフォントキャッシュを取得します。 |
| useMagicNumbersForStyles | boolean | true に設定された場合  [use magic numbers for styles]。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


この com.aspose.psd.Graphics のローカル幾何変換を表す com.aspose.psd.Matrix を、指定された com.aspose.psd.Matrix で前置し、指定された com.aspose.psd.matrix を掛け合わせます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | ジオメトリ変換に乗算するための  com.aspose.psd.Matrix  。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


この com.aspose.psd.Graphics のローカル幾何変換を表す com.aspose.psd.Matrix を、指定された順序で指定された com.aspose.psd.Matrix と乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | ジオメトリ変換に乗算するための  com.aspose.psd.Matrix  。 |
| order | int | 2 つの行列を乗算する順序を指定する  com.aspose.psd.MatrixOrder  。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


com.aspose.psd.graphics.Transform プロパティを単位行列にリセットします。

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


ローカルの幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度です。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


ローカル幾何変換を指定された順序で指定された量だけ回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度です。 |
| order | int | 回転行列を追加するか前に置くかを指定する  com.aspose.psd.MatrixOrder  。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


指定された量でローカル幾何変換を拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に付加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | x 軸方向に変換を拡大縮小する量です。 |
| sy | float | y 軸方向に変換を拡大縮小する量です。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


ローカル幾何変換を指定された順序で指定された量で拡大縮小します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | x 軸方向に変換を拡大縮小する量です。 |
| sy | float | y 軸方向に変換を拡大縮小する量です。 |
| order | int | スケーリング行列を追加するか前に置くかを指定する  com.aspose.psd.MatrixOrder  。 |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


クリップ領域を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | クリップ領域。 |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


合成品質を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 合成品質。 |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


補間モードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 補間モード。 |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


この com.aspose.psd.graphics のワールド単位とページ単位間のスケーリングを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この com.aspose.psd.graphics のワールド単位とページ単位間のスケーリング。 |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


この com.aspose.psd.graphics で使用されるページ座標の測定単位を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この com.aspose.psd.graphics で使用されるページ座標の測定単位。 |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


描画用の塗りつぶし可能なvactor画像を作成するために使用される画像オプションを取得または設定します。

値: 描画用のベクター画像を作成するために使用される画像オプション。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


スムージングモードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | スムージングモード。 |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


テキストレンダリングヒントを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | テキストレンダリングヒント。 |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


この com.aspose.psd.graphics の幾何学的ワールド変換のコピーを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | この  com.aspose.psd.graphics のジオメトリワールド変換を表す  com.aspose.psd.Matrix  のコピー。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


指定された寸法でローカル幾何変換を平行移動します。このメソッドは平行移動を変換の先頭に付加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


ローカルの幾何変換を指定された寸法で、指定された順序で平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |
| order | int | 平行移動を適用する順序（先頭に付加するか末尾に追加するか）です。 |

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

