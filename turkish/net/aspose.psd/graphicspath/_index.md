---
title: "Sınıf GraphicsPath"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.GraphicsPath sınıfı. Bağlantılı çizgiler ve eğriler serisini temsil eder. Bu sınıf miras alınamaz."
type: docs
weight: 4820
url: /tr/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

Bağlantılı çizgiler ve eğriler serisini temsil eder. Bu sınıf devralınamaz.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | `GraphicsPath` sınıfının yeni bir örneğini başlatır. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | `GraphicsPath` sınıfının yeni bir örneğini başlatır. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | `GraphicsPath` sınıfının yeni bir örneğini başlatır. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | `GraphicsPath` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Nesnenin sınırlarını alır veya ayarlar. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Yol şekillerini alır. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Bu `GraphicsPath` içindeki şekillerin içlerinin nasıl doldurulacağını belirleyen bir [`FillMode`](../fillmode/) enum değerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Yeni bir şekil ekler. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Yeni şekiller ekler. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Belirtilen `GraphicsPath`'i bu yola ekler. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Belirtilen `GraphicsPath`'i bu yola ekler. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Bu grafik yolunun derin bir kopyasını oluşturur. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Bu yoldaki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Belirtilen dönüşümü uygular ve ardından bu `GraphicsPath` içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Bu `GraphicsPath` içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Belirtilen noktanın, belirtilen [`Pen`](../pen/) ile çizildiğinde bu `GraphicsPath`'in konturunun içinde (altında) olup olmadığını gösterir. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Belirtilen noktanın, belirtilen [`Pen`](../pen/) ile çizildiğinde bu `GraphicsPath`'in konturunun içinde (altında) olup olmadığını gösterir. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Belirtilen noktanın, belirtilen [`Pen`](../pen/) ile çizildiğinde bu `GraphicsPath`'in konturunun içinde (altında) olup olmadığını gösterir. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Belirtilen noktanın, belirtilen [`Pen`](../pen/) ile çizildiğinde bu `GraphicsPath`'in konturunun içinde (altında) olup olmadığını gösterir. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Belirtilen noktanın, belirtilen [`Pen`](../pen/) ile ve belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `GraphicsPath`'in konturunun içinde (altında) olup olmadığını gösterir. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Belirtilen noktanın, belirtilen [`Pen`](../pen/) ile ve belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `GraphicsPath`'in konturunun içinde (altında) olup olmadığını gösterir. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Belirtilen noktanın, belirtilen [`Pen`](../pen/) ile ve belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `GraphicsPath`'in konturunun içinde (altında) olup olmadığını gösterir. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Belirtilen noktanın, belirtilen [`Pen`](../pen/) ile ve belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `GraphicsPath`'in konturunun içinde (altında) olup olmadığını gösterir. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Belirtilen noktanın bu `GraphicsPath` içinde olup olmadığını gösterir. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Belirtilen noktanın bu `GraphicsPath` içinde olup olmadığını gösterir. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Belirtilen noktanın bu `GraphicsPath` içinde olup olmadığını gösterir. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Belirtilen noktanın bu `GraphicsPath` içinde olup olmadığını gösterir. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Belirtilen noktanın bu `GraphicsPath` içinde olup olmadığını gösterir. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Belirtilen noktanın bu `GraphicsPath` içinde olup olmadığını gösterir. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Belirtilen noktanın, belirtilen [`Graphics`](../graphics/) görünür kırpma bölgesinde bu `GraphicsPath` içinde olup olmadığını gösterir. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Belirtilen noktanın, belirtilen [`Graphics`](../graphics/) kullanılarak bu `GraphicsPath` içinde olup olmadığını gösterir. |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Bir şekli kaldırır. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Şekilleri kaldırır. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Grafik yolunu boşaltır ve [`FillMode`](../fillmode/) değerini Alternate olarak ayarlar. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Bu `GraphicsPath`'in her şeklinin figür, şekil ve nokta sırasını tersine çevirir. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümünü bu `GraphicsPath`'e uygular. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümünü bu `GraphicsPath`'e uygular. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümünü bu `GraphicsPath`'e uygular. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümünü bu `GraphicsPath`'e uygular. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Yola ek bir kontur ekler. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Bu `GraphicsPath`'e ek bir kontur ekler. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Bu `GraphicsPath`'i, bu yol belirtilen kalemle çizildiğinde doldurulan alanı çevreleyen eğrilerle değiştirir. |

## Örnekler

Bu örnekler, bir Görüntü yüzeyinde Şekiller oluşturmak ve manipüle etmek için GraphicsPath ve Graphics sınıflarını kullanır. Örnek, yeni bir Görüntü oluşturur ve GraphicsPath sınıfının yardımıyla yollar çizer. Sonunda, Graphics sınıfı tarafından sunulan DrawPath yöntemi, yolları yüzeye render etmek için çağrılır. Son olarak görüntü Tiff dosya formatına dışa aktarılır.

```csharp
[C#]

//Image sınıfının bir örneğini oluşturun.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics sınıfının bir örneğini oluşturun ve başlatın.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics yüzeyini temizleyin.
    graphics.Clear(Color.Wheat);

    //GraphicsPath sınıfının bir örneğini oluşturun.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure sınıfının bir örneğini oluşturun.
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Figure nesnesine Şekiller ekleyin.
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Figure nesnesini GraphicsPath'e ekleyin.
    graphicspath.AddFigure(figure);

    //Siyah renkli Pen nesnesiyle yolu çizin.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions sınıfının bir örneğini oluşturun ve çeşitli özelliklerini ayarlayın.
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // tüm değişiklikleri kaydet.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Ayrıca Bakınız

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


