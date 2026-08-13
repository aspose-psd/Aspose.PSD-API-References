---
title: "Sınıf Graphics"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Graphics sınıfı. Geçerli derlemede kullanılan grafik motoruna göre grafikleri temsil eder."
type: docs
weight: 4810
url: /tr/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

Geçerli derlemede kullanılan grafik motoruna göre grafikleri temsil eder.

```csharp
public sealed class Graphics
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Graphics](graphics/)(Image) | Yeni bir `Graphics` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Kırpma bölgesini alır veya ayarlar. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Bileşim kalitesini alır veya ayarlar. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Bu Aspose.PSD.Graphics nesnesinin yatay çözünürlüğünü alır. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Bu Aspose.PSD.Graphics nesnesinin dikey çözünürlüğünü alır. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Görüntüyü alır. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Enterpolasyon modunu alır veya ayarlar. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Grafiğin BeginUpdate çağrı durumunda olup olmadığını gösteren bir değeri alır. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Bu Aspose.PSD.Graphics için dünya birimleri ile sayfa birimleri arasındaki ölçeklemeyi alır veya ayarlar. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Bu Aspose.PSD.Graphics içindeki sayfa koordinatları için kullanılan ölçü birimini alır veya ayarlar. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | Görüntü seçeneklerini alır veya ayarlar, çizim için boyanabilir vektör görüntüleri oluşturmakta kullanılır. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Alır veya ayarlar yumuşatma modunu. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Alır veya ayarlar metin renderleme ipucunu. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Bu `Graphics` için geometrik dünya dönüşümünün bir kopyasını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Aşağıdaki grafik işlemlerinin önbelleğe alınmasını başlatır. Sonradan uygulanan grafik efektleri hemen uygulanmaz, bunun yerine EndUpdate tüm efektlerin bir kerede uygulanmasını sağlar. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Belirtilen renk kullanılarak grafik yüzeyi temizlenir. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Bir [`Rectangle`](../rectangle/) yapısı ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Bir [`RectangleF`](../rectanglef/) yapısı ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Dört [`Point`](../point/) yapısı tarafından tanımlanan bir Bézier eğrisi çizer. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Dört [`PointF`](../pointf/) yapısı tarafından tanımlanan bir Bézier eğrisi çizer. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Nokta temsil eden dört sıralı koordinat çiftine göre tanımlanan bir Bézier eğrisi çizer. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | [`PointF`](../pointf/) yapılarının bir dizisinden bir dizi Bézier eğrisi çizer. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | [`Point`](../point/) yapılarının bir dizisinden bir dizi Bézier eğrisi çizer. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Bir dizi [`PointF`](../pointf/) yapısı tarafından tanımlanan kapalı bir kardinal eğri çizer. Bu yöntem varsayılan 0.5 gerilimi ve Alternatif doldurma modunu kullanır. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Bir dizi [`Point`](../point/) yapısı tarafından tanımlanan kapalı bir kardinal eğri çizer. Bu yöntem varsayılan 0.5 gerilimi ve Alternatif doldurma modunu kullanır. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Belirtilen bir gerilim kullanarak bir dizi [`PointF`](../pointf/) yapısı tarafından tanımlanan kapalı bir kardinal eğri çizer. Bu yöntem varsayılan Alternatif doldurma modunu kullanır. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Belirtilen bir gerilim kullanarak bir dizi [`Point`](../point/) yapısı tarafından tanımlanan kapalı bir kardinal eğri çizer. Bu yöntem varsayılan Alternatif doldurma modunu kullanır. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Belirtilen bir dizi [`PointF`](../pointf/) yapısı üzerinden bir kardinal eğri çizer. Bu yöntem varsayılan 0.5 gerilimi kullanır. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Belirtilen bir dizi [`Point`](../point/) yapısı üzerinden bir kardinal eğri çizer. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Belirtilen bir gerilim kullanarak belirtilen bir dizi [`PointF`](../pointf/) yapısı üzerinden bir kardinal eğri çizer. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Belirtilen bir gerilim kullanarak belirtilen bir dizi [`Point`](../point/) yapısı üzerinden bir kardinal eğri çizer. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Belirtilen bir dizi [`PointF`](../pointf/) yapısı üzerinden bir kardinal eğri çizer. Çizim, dizinin başlangıcından bir kayma ile başlar. Bu yöntem varsayılan 0.5 gerilimi kullanır. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Belirtilen bir gerilim kullanarak belirtilen bir dizi [`PointF`](../pointf/) yapısı üzerinden bir kardinal eğri çizer. Çizim, dizinin başlangıcından bir kayma ile başlar. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Belirtilen bir gerilim kullanarak belirtilen bir dizi [`Point`](../point/) yapısı üzerinden bir kardinal eğri çizer. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Sınırlayıcı bir [`Rectangle`](../rectangle/) yapısı ile belirtilen bir elips çizer. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Sınırlayıcı bir [`RectangleF`](../rectanglef/) ile tanımlanan bir elips çizer. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Bir çift koordinat, bir yükseklik ve bir genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Bir çift koordinat, bir yükseklik ve bir genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Belirtilen [`Image`](./image/) öğesini, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Belirtilen [`Image`](./image/) öğesini, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Belirtilen [`Image`](./image/) öğesini, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Belirtilen görseli, özgün fiziksel boyutunu kullanarak, bir koordinat çiftiyle belirtilen konumda çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Belirtilen [`Image`](./image/) öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Belirtilen bir görseli, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Belirtilen bir görseli, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Belirtilen görseli, özgün fiziksel boyutunu kullanarak, bir koordinat çiftiyle belirtilen konumda çizer. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Belirtilen bir görseli, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Belirtilen görseli ölçeklendirmeden çizer ve gerekirse, belirtilen dikdörtgene sığacak şekilde kırpar. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | İki [`Point`](../point/) yapısını bağlayan bir çizgi çizer. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | İki [`PointF`](../pointf/) yapısını bağlayan bir çizgi çizer. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | `[`PointF`](../pointf/)` yapılarından oluşan bir diziye bağlanan bir dizi çizgi segmenti çizer. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | `[`Point`](../point/)` yapılarından oluşan bir diziye bağlanan bir dizi çizgi segmenti çizer. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | `[`GraphicsPath`](../graphicspath/)` çizer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | `[`Rectangle`](../rectangle/)` yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | `[`RectangleF`](../rectanglef/)` yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Bir koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Bir koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | `[`PointF`](../pointf/)` yapılarından oluşan bir diziyle tanımlanan bir çokgen çizer. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | `[`Point`](../point/)` yapılarından oluşan bir diziyle tanımlanan bir çokgen çizer. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | `[`Rectangle`](../rectangle/)` yapısı tarafından belirtilen bir dikdörtgen çizer. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | `[`RectangleF`](../rectanglef/)` yapısı tarafından belirtilen bir dikdörtgen çizer. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | `[`RectangleF`](../rectanglef/)` yapılarıyla belirtilen bir dizi dikdörtgen çizer. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | `[`Rectangle`](../rectangle/)` yapılarıyla belirtilen bir dizi dikdörtgen çizer. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Belirtilen [`Brush`](../brush/) ve [`Font`](../font/) nesneleriyle belirtilen konumda belirtilen metin dizesini çizer. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Belirtilen [`Brush`](../brush/) ve [`Font`](../font/) nesneleriyle belirtilen dikdörtgende belirtilen metin dizesini çizer. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Belirtilen [`Brush`](../brush/) ve [`Font`](../font/) nesneleriyle belirtilen konumda belirtilen metin dizesini çizer. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Belirtilen [`Brush`](../brush/) ve [`Font`](../font/) nesneleriyle, belirtilen [`StringFormat`](../stringformat/) biçimlendirme özniteliklerini kullanarak, belirtilen konumda belirtilen metin dizesini çizer. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Belirtilen [`Brush`](../brush/) ve [`Font`](../font/) nesneleriyle, belirtilen [`StringFormat`](../stringformat/) biçimlendirme özniteliklerini kullanarak, belirtilen dikdörtgende belirtilen metin dizesini çizer. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Belirtilen [`Brush`](../brush/) ve [`Font`](../font/) nesneleriyle, belirtilen [`StringFormat`](../stringformat/) biçimlendirme özniteliklerini kullanarak, belirtilen konumda belirtilen metin dizesini çizer. |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | BeginUpdate çağrıldıktan sonra başlatılan grafik işlemlerinin önbelleğe alınması tamamlanır. Önceki grafik işlemleri bu yöntem çağrıldığında bir kerede uygulanır. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | `[`PointF`](../pointf/)` yapılarından oluşan bir diziyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilme ve Alternatif doldurma kipini kullanır. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | `[`Point`](../point/)` yapılarından oluşan bir diziyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilme ve Alternatif doldurma kipini kullanır. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | `[`PointF`](../pointf/)` yapılarından oluşan bir diziyle tanımlanan kapalı bir kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilme kullanır. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | `[`Point`](../point/)` yapılarından oluşan bir diziyle tanımlanan kapalı bir kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilme kullanır. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Belirtilen doldurma modu ve gerilme kullanılarak, bir dizi [`PointF`](../pointf/) yapısı ile tanımlanan kapalı kardinal spline eğrisinin içini doldurur. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Belirtilen doldurma modu ve gerilme kullanılarak, bir dizi [`Point`](../point/) yapısı ile tanımlanan kapalı kardinal spline eğrisinin içini doldurur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | [`Rectangle`](../rectangle/) yapısı ile belirtilen sınırlayıcı dikdörtgen tarafından tanımlanan bir elipsin içini doldurur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | [`RectangleF`](../rectanglef/) yapısı ile belirtilen sınırlayıcı dikdörtgen tarafından tanımlanan bir elipsin içini doldurur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgen tarafından tanımlanan bir elipsin içini doldurur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgen tarafından tanımlanan bir elipsin içini doldurur. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | [`GraphicsPath`](../graphicspath/) öğesinin içini doldurur. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | [`RectangleF`](../rectanglef/) yapısı ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta diliminin içini doldurur. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | [`RectangleF`](../rectanglef/) yapısı ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta diliminin içini doldurur. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta diliminin içini doldurur. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta diliminin içini doldurur. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | [`PointF`](../pointf/) yapıları ile belirtilen bir dizi nokta ve Alternate kullanılarak tanımlanan bir çokgenin içini doldurur. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | [`Point`](../point/) yapıları ile belirtilen bir dizi nokta ve Alternate kullanılarak tanımlanan bir çokgenin içini doldurur. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | [`PointF`](../pointf/) yapıları ile belirtilen bir dizi nokta kullanılarak ve belirtilen doldurma modu ile tanımlanan bir çokgenin içini doldurur. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | [`Point`](../point/) yapıları ile belirtilen bir dizi nokta kullanılarak ve belirtilen doldurma modu ile tanımlanan bir çokgenin içini doldurur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | [`Rectangle`](../rectangle/) yapısı ile belirtilen bir dikdörtgenin içini doldurur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | [`RectangleF`](../rectanglef/) yapısı ile belirtilen bir dikdörtgenin içini doldurur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | [`RectangleF`](../rectanglef/) yapıları ile belirtilen bir dizi dikdörtgenin içlerini doldurur. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | [`Rectangle`](../rectangle/) yapıları ile belirtilen bir dizi dikdörtgenin içlerini doldurur. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | [`Region`](../region/) öğesinin içini doldurur. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | [`Matrix`](../matrix/) nesnesini, bu `Graphics` nesnesinin yerel geometrik dönüşümünü temsil eden, belirtilen [`Matrix`](../matrix/) ile, belirtilen [`Matrix`](../matrix/) önüne ekleyerek çarpar. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | [`Matrix`](../matrix/) nesnesini, bu `Graphics` nesnesinin yerel geometrik dönüşümünü temsil eden, belirtilen [`Matrix`](../matrix/) ile belirtilen sırada çarpar. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | [`Transform`](./transform/) özelliğini birim (identity) haline sıfırlar. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşümün önüne ekler. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Yerel geometrik dönüşümü belirtilen ölçeklerde büyütür. Bu yöntem ölçekleme matrisini dönüşümün önüne ekler. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen ölçeklerde, belirtilen sırada büyütür. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlarda kaydırır. Bu yöntem çevirimi dönüşümün önüne ekler. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada kaydırır. |

## Örnekler

Bu örnek, Image yüzeyinde temel şekiller oluşturmak için Graphics sınıfını kullanır. İşlemi göstermek için örnek, PSD formatında yeni bir Image oluşturur ve Graphics sınıfı tarafından sunulan Draw yöntemlerini kullanarak Image yüzeyinde temel şekiller çizer, ardından PSD dosya formatına dışa aktarır.

```csharp
[C#]

//Image sınıfının bir örneğini oluşturun.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics sınıfının bir örneğini oluşturun ve başlatın.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics yüzeyini temizleyin.
    graphics.Clear(Color.Wheat);

    //Siyah renkli Pen nesnesini belirterek bir Yay çizin, 
    //Yayı çevreleyen bir Dikdörtgen, Başlangıç Açısı ve Tarama Açısı
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Mavi renkli Pen nesnesini ve koordinat noktalarını belirterek bir Bezier çizin.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Yeşil renkli Pen nesnesini ve bir dizi Nokta'yı belirterek bir Eğri çizin
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen nesnesini ve çevreleyen bir Dikdörtgeni kullanarak bir Elips çizin
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Bir Çizgi çizin 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Bir Pasta dilimi çizin
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Kırmızı renkli Pen nesnesini ve bir dizi Nokta'yı belirterek bir Çokgen çizin
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Bir Dikdörtgen çizin
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Bir SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush nesnesi ve Font kullanarak belirli bir Noktada bir Dize çizin
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // tüm değişiklikleri kaydet.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


