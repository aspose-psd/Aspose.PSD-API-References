---
title: Class Graphics
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Graphics sınıf. Geçerli derlemede kullanılan grafik motoruna göre grafikleri temsil eder.
type: docs
weight: 4310
url: /tr/net/aspose.psd/graphics/
---
## Graphics class

Geçerli derlemede kullanılan grafik motoruna göre grafikleri temsil eder.

```csharp
public sealed class Graphics
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Graphics](graphics/)(Image) | Yeni bir örneğini başlatır.`Graphics` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Klip bölgesini alır veya ayarlar. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Birleştirme kalitesini alır veya ayarlar. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Bu Aspose.PSD.Graphics. 'nin yatay çözünürlüğünü alır |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Bu Aspose.PSD.Graphics. 'nin dikey çözünürlüğünü alır |
| [Image](../../aspose.psd/graphics/image/) { get; } | Görüntüyü alır. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Enterpolasyon modunu alır veya ayarlar. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Grafiklerin BeginUpdate çağrı durumunda olup olmadığını gösteren bir değer alır. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Bu Aspose.PSD.Graphics. için dünya birimleri ve sayfa birimleri arasındaki ölçeklendirmeyi alır veya ayarlar |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Bu Aspose.PSD.Graphics. 'de sayfa koordinatları için kullanılan ölçü birimini alır veya ayarlar. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Düzleştirme modunu alır veya ayarlar. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Metin işleme ipucunu alır veya ayarlar. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Bunun için geometrik dünya dönüşümünün bir kopyasını alır veya ayarlar`Graphics` . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Aşağıdaki grafik işlemlerinin önbelleğe alınmasını başlatır. Daha sonra uygulanan grafik efektleri hemen uygulanmaz, bunun yerine EndUpdate tüm efektlerin bir kerede uygulanmasına neden olur. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Belirtilen rengi kullanarak grafik yüzeyini temizler. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer.[`Rectangle`](../rectangle/)yapı. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer.[`RectangleF`](../rectanglef/)yapı. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Bir çift koordinat, genişlik ve yükseklik tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Bir çift koordinat, genişlik ve yükseklik tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Dört ile tanımlanan bir Bézier spline çizer[`Point`](../point/) yapılar. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Dört ile tanımlanan bir Bézier spline çizer[`PointF`](../pointf/) yapılar. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Noktaları temsil eden sıralı dört koordinat çifti tarafından tanımlanan bir Bézier spline çizer. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Bir diziden bir dizi Bézier spline çizer.[`PointF`](../pointf/) yapılar. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Bir diziden bir dizi Bézier spline çizer.[`Point`](../point/) yapılar. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline çizer.[`PointF`](../pointf/) yapılar. Bu yöntem, varsayılan olarak 0,5'lik bir gerilim kullanır veAlternate modu doldur. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline çizer.[`Point`](../point/) yapılar. Bu yöntem, varsayılan olarak 0,5'lik bir gerilim kullanır veAlternate modu doldur. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline çizer.[`PointF`](../pointf/) belirli bir gerilim kullanan yapılar. Bu yöntem bir varsayılan kullanırAlternate modu doldur. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline çizer.[`Point`](../point/) belirli bir gerilim kullanan yapılar. Bu yöntem bir varsayılan kullanırAlternate modu doldur. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Belirli bir dizi boyunca bir kardinal spline çizer.[`PointF`](../pointf/) yapılar. Bu yöntem, 0.5. varsayılan gerginliğini kullanır. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Belirli bir dizi boyunca bir kardinal spline çizer.[`Point`](../point/) yapılar. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Belirli bir dizi boyunca bir kardinal spline çizer.[`PointF`](../pointf/) belirli bir gerilimi kullanan yapılar. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Belirli bir dizi boyunca bir kardinal spline çizer.[`Point`](../point/) belirli bir gerilimi kullanan yapılar. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Belirli bir dizi boyunca bir kardinal spline çizer.[`PointF`](../pointf/) yapılar. Çizim, dizinin başından ofset olarak başlar. Bu yöntem, 0.5. varsayılan gerginliğini kullanır. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Belirli bir dizi boyunca bir kardinal spline çizer.[`PointF`](../pointf/) belirli bir gerilim kullanan yapılar. Çizim, dizinin başından itibaren kaydırılarak başlar. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Belirli bir dizi boyunca bir kardinal spline çizer.[`Point`](../point/) belirli bir gerilimi kullanan yapılar. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Sınırlayıcı tarafından belirtilen bir elips çizer[`Rectangle`](../rectangle/)yapı. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Sınırlayıcı tarafından tanımlanan bir elips çizer[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Bir çift koordinat, yükseklik ve genişlik tarafından belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Bir çift koordinat, yükseklik ve genişlik tarafından belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Belirtileni çizer[`Image`](./image/) , belirtilen konumda orijinal fiziksel boyutunu kullanarak. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Belirtileni çizer[`Image`](./image/) , belirtilen konumda orijinal fiziksel boyutunu kullanarak. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Belirtilen parçanın belirtilen kısmını çizer.*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Belirtilen parçanın belirtilen kısmını çizer.*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Belirtileni çizer[`Image`](./image/) , belirtilen konumda orijinal fiziksel boyutunu kullanarak. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Belirtilen görüntüyü, bir koordinat çifti tarafından belirtilen konumda orijinal fiziksel boyutunu kullanarak çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Belirtilen parçanın belirtilen kısmını çizer.*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Belirtilen parçanın belirtilen kısmını çizer.*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Belirtilen parçanın belirtilen kısmını çizer.*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Belirtilen parçanın belirtilen kısmını çizer.*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Belirtilen parçanın belirtilen kısmını çizer.*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Belirtilen parçanın belirtilen kısmını çizer.*image* belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Belirtileni çizer[`Image`](./image/) belirtilen konumda ve belirtilen boyutta. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Belirtilen bir konumdaki orijinal fiziksel boyutunu kullanarak belirli bir görüntü çizer. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Belirtilen bir konumdaki orijinal fiziksel boyutunu kullanarak belirli bir görüntü çizer. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Belirtilen görüntüyü, bir koordinat çifti tarafından belirtilen konumda orijinal fiziksel boyutunu kullanarak çizer. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Belirtilen bir konumdaki orijinal fiziksel boyutunu kullanarak belirli bir görüntü çizer. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Belirtilen görüntüyü ölçeklendirmeden çizer ve gerekirse belirtilen dikdörtgene sığdırmak için kırpar. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | İkiyi birleştiren bir çizgi çizer[`Point`](../point/) yapılar. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | İkiyi birleştiren bir çizgi çizer[`PointF`](../pointf/) yapılar. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Koordinat çiftleri tarafından belirtilen iki noktayı birleştiren bir çizgi çizer. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Koordinat çiftleri tarafından belirtilen iki noktayı birleştiren bir çizgi çizer. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Bir diziyi birbirine bağlayan bir dizi çizgi parçası çizer.[`PointF`](../pointf/) yapılar. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Bir diziyi birbirine bağlayan bir dizi çizgi parçası çizer.[`Point`](../point/) yapılar. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | bir çizer[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | tarafından belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.[`Rectangle`](../rectangle/) yapı ve iki radyal çizgi. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | tarafından belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.[`RectangleF`](../rectanglef/) yapı ve iki radyal çizgi. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgi tarafından belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgi tarafından belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Bir dizi tarafından tanımlanan bir çokgen çizer.[`PointF`](../pointf/) yapılar. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Bir dizi tarafından tanımlanan bir çokgen çizer.[`Point`](../point/) yapılar. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | tarafından belirtilen bir dikdörtgen çizer.[`Rectangle`](../rectangle/)yapı. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | tarafından belirtilen bir dikdörtgen çizer.[`RectangleF`](../rectanglef/)yapı. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Koordinat çifti, genişlik ve yükseklik tarafından belirtilen bir dikdörtgen çizer. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Koordinat çifti, genişlik ve yükseklik tarafından belirtilen bir dikdörtgen çizer. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | tarafından belirtilen bir dizi dikdörtgen çizer.[`RectangleF`](../rectanglef/) yapılar. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | tarafından belirtilen bir dizi dikdörtgen çizer.[`Rectangle`](../rectangle/) yapılar. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Belirtilen metin dizesini belirtilen konumda belirtilen konumla çizer.[`Brush`](../brush/) Ve[`Font`](../font/) nesneler. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Belirtilen metin dizesini, belirtilen dikdörtgene belirtilen değerle çizer.[`Brush`](../brush/) Ve[`Font`](../font/) nesneler. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Belirtilen metin dizesini belirtilen konumda belirtilen konumla çizer.[`Brush`](../brush/) Ve[`Font`](../font/) nesneler. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Belirtilen metin dizesini belirtilen konumda belirtilen konumla çizer.[`Brush`](../brush/) Ve[`Font`](../font/) belirtilen biçimlendirme özniteliklerini kullanan nesneler[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Belirtilen metin dizesini, belirtilen dikdörtgene belirtilen değerle çizer.[`Brush`](../brush/) Ve[`Font`](../font/) belirtilen biçimlendirme özniteliklerini kullanan nesneler[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Belirtilen metin dizesini belirtilen konumda belirtilen konumla çizer.[`Brush`](../brush/) Ve[`Font`](../font/) belirtilen biçimlendirme özniteliklerini kullanan nesneler[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | BeginUpdate çağrıldıktan sonra başlatılan grafik işlemlerinin önbelleğe alınmasını bitirir. Bu yöntem çağrılırken önceki grafik işlemleri bir kerede uygulanacaktır. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.[`PointF`](../pointf/) yapılar. Bu yöntem, varsayılan olarak 0,5'lik bir gerilim kullanır veAlternate modu doldur. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.[`Point`](../point/) yapılar. Bu yöntem, varsayılan olarak 0,5'lik bir gerilim kullanır veAlternate modu doldur. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.[`PointF`](../pointf/) belirtilen dolgu modunu kullanan yapılar. Bu yöntem, 0.5. varsayılan gerginliğini kullanır. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.[`Point`](../point/) belirtilen dolgu modunu kullanan yapılar. Bu yöntem, 0.5. varsayılan gerginliğini kullanır. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.[`PointF`](../pointf/) belirtilen dolgu modunu ve gerilimi kullanan yapılar. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Bir dizi tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.[`Point`](../point/) belirtilen dolgu modunu ve gerilimi kullanan yapılar. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | tarafından belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elipsin içini doldurur.[`Rectangle`](../rectangle/)yapı. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | tarafından belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elipsin içini doldurur.[`RectangleF`](../rectanglef/)yapı. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Bir çift koordinat, genişlik ve yükseklik tarafından belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elipsin içini doldurur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Bir çift koordinat, genişlik ve yükseklik tarafından belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elipsin içini doldurur. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | içini doldurur[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | tarafından belirtilen bir elips tarafından tanımlanan bir pasta bölümünün içini doldurur.[`RectangleF`](../rectanglef/) yapı ve iki radyal çizgi. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | tarafından belirtilen bir elips tarafından tanımlanan bir pasta bölümünün içini doldurur.[`RectangleF`](../rectanglef/) yapı ve iki radyal çizgi. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Bir çift koordinat, bir genişlik, bir yükseklik ve iki radyal çizgi tarafından belirtilen bir elips tarafından tanımlanan bir pasta bölümünün içini doldurur. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Bir çift koordinat, bir genişlik, bir yükseklik ve iki radyal çizgi tarafından belirtilen bir elips tarafından tanımlanan bir pasta bölümünün içini doldurur. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | tarafından belirtilen bir dizi nokta tarafından tanımlanan bir çokgenin içini doldurur.[`PointF`](../pointf/) yapılar veAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | tarafından belirtilen bir dizi nokta tarafından tanımlanan bir çokgenin içini doldurur.[`Point`](../point/) yapılar veAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | tarafından belirtilen bir dizi nokta tarafından tanımlanan bir çokgenin içini doldurur.[`PointF`](../pointf/) belirtilen dolgu modunu kullanan yapılar. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | tarafından belirtilen bir dizi nokta tarafından tanımlanan bir çokgenin içini doldurur.[`Point`](../point/) belirtilen dolgu modunu kullanan yapılar. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | tarafından belirtilen bir dikdörtgenin içini doldurur.[`Rectangle`](../rectangle/)yapı. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | tarafından belirtilen bir dikdörtgenin içini doldurur.[`RectangleF`](../rectanglef/)yapı. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Bir çift koordinat, genişlik ve yükseklik tarafından belirtilen bir dikdörtgenin içini doldurur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Bir çift koordinat, genişlik ve yükseklik tarafından belirtilen bir dikdörtgenin içini doldurur. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | tarafından belirtilen bir dizi dikdörtgenin içini doldurur.[`RectangleF`](../rectanglef/) yapılar. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | tarafından belirtilen bir dizi dikdörtgenin içini doldurur.[`Rectangle`](../rectangle/) yapılar. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | içini doldurur[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | [`Matrix`](../matrix/) bunun yerel geometrik dönüşümünü temsil eden`Graphics` belirtilen tarafından[`Matrix`](../matrix/) belirtilenin başına ekleyerek[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | [`Matrix`](../matrix/) bunun yerel geometrik dönüşümünü temsil eden`Graphics` belirtilen tarafından[`Matrix`](../matrix/) belirtilen sırada. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | sıfırlar[`Transform`](./transform/) kimlik için özellik. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem, dönüşü transform. 'nin başına ekler |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırada belirtilen miktarda döndürür. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Yerel geometrik dönüşümü belirtilen miktarlarda ölçekler. Bu yöntem, ölçeklendirme matrisini transform. 'nin başına ekler. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırada belirtilen miktarlarda ölçekler. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlara çevirir. Bu yöntem, çeviriyi transform. 'nin başına ekler. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırayla belirtilen boyutlara çevirir. |

### Örnekler

Bu örnek, Image yüzeyinde ilkel şekiller oluşturmak için Graphics sınıfını kullanır. İşlemi göstermek için örnek, PSD biçiminde yeni bir Görüntü oluşturur ve Graphics sınıfı tarafından sunulan Draw yöntemlerini kullanarak Görüntü yüzeyinde ilkel şekiller çizer ve ardından bunu PSD dosya biçimine dışa aktarır.

```csharp
[C#]

//Görüntünün bir örneğini oluştur 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics sınıfının bir örneğini oluştur ve başlat
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafik yüzeyini temizle
    graphics.Clear(Color.Wheat);

    //Siyah renkli Kalem nesnesini belirterek bir Yay çizin, 
    //Yay, Başlangıç Açısı ve Tarama Açısını çevreleyen bir Dikdörtgen
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Mavi renk ve koordinat Noktalarına sahip Kalem nesnesini belirterek bir Bezier çizin.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Yeşil renge ve bir Nokta dizisine sahip Kalem nesnesini belirterek bir Eğri çizin
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Kalem nesnesini ve çevreleyen Dikdörtgeni kullanarak bir Elips çizin
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Bir çizgi çiz 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Pasta parçası çiz
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Kırmızı renge ve Nokta dizisine sahip Kalem nesnesini belirterek bir Çokgen çizin
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dikdörtgen Çiz
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Bir SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Belirli Noktada SolidBrush nesnesini ve Fontu kullanarak bir String çizin
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions örneğini oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // tüm değişiklikleri kaydet.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


