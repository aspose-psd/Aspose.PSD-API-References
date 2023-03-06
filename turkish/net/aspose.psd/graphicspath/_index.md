---
title: Class GraphicsPath
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.GraphicsPath sınıf. Bir dizi bağlantılı çizgiyi ve eğriyi temsil eder. Bu sınıf miras alınamaz.
type: docs
weight: 4320
url: /tr/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Bir dizi bağlantılı çizgiyi ve eğriyi temsil eder. Bu sınıf miras alınamaz.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Yeni bir örneğini başlatır.`GraphicsPath` sınıf. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Yeni bir örneğini başlatır.`GraphicsPath` sınıf. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Yeni bir örneğini başlatır.`GraphicsPath` sınıf. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Yeni bir örneğini başlatır.`GraphicsPath` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Nesnenin sınırlarını alır veya ayarlar. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Yol rakamlarını alır. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Alır veya ayarlar[`FillMode`](../fillmode/) Bu sistemdeki şekillerin içlerinin nasıl olduğunu belirleyen numaralandırma`GraphicsPath` dolu. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Yeni bir rakam ekler. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Yeni rakamlar ekler. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Belirtileni ekler`GraphicsPath` bu yola. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Belirtileni ekler`GraphicsPath` bu yola. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Bu grafik yolunun derin bir klonunu gerçekleştirir. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Bu yoldaki her bir eğriyi bir bağlı çizgi parçaları dizisine dönüştürür. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Belirtilen dönüşümü uygular ve ardından bu eğrideki her eğriyi dönüştürür`GraphicsPath` bağlı çizgi segmentleri dizisine. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Buradaki her eğriyi dönüştürür`GraphicsPath` bağlı çizgi segmentleri dizisine. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Belirtilen noktanın bu ana hattın içinde (altında) bulunup bulunmadığını belirtir.`GraphicsPath` belirtilen ile çizildiğinde[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Belirtilen noktanın bu ana hattın içinde (altında) bulunup bulunmadığını belirtir.`GraphicsPath` belirtilen ile çizildiğinde[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Belirtilen noktanın bu ana hattın içinde (altında) bulunup bulunmadığını belirtir.`GraphicsPath` belirtilen ile çizildiğinde[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Belirtilen noktanın bu ana hattın içinde (altında) bulunup bulunmadığını belirtir.`GraphicsPath` belirtilen ile çizildiğinde[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Belirtilen noktanın bu ana hattın içinde (altında) bulunup bulunmadığını belirtir.`GraphicsPath` belirtilen ile çizildiğinde[`Pen`](../pen/) ve belirtilen kullanarak[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Belirtilen noktanın bu ana hattın içinde (altında) bulunup bulunmadığını belirtir.`GraphicsPath` belirtilen ile çizildiğinde[`Pen`](../pen/) ve belirtilen kullanarak[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Belirtilen noktanın bu ana hattın içinde (altında) bulunup bulunmadığını belirtir.`GraphicsPath` belirtilen ile çizildiğinde[`Pen`](../pen/) ve belirtilen kullanarak[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Belirtilen noktanın bu ana hattın içinde (altında) bulunup bulunmadığını belirtir.`GraphicsPath` belirtilen ile çizildiğinde[`Pen`](../pen/) ve belirtilen kullanarak[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Belirtilen noktanın bunun içinde olup olmadığını gösterir.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Belirtilen noktanın bunun içinde olup olmadığını gösterir.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Belirtilen noktanın bunun içinde olup olmadığını gösterir.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Belirtilen noktanın bunun içinde olup olmadığını gösterir.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Belirtilen noktanın bunun içinde olup olmadığını gösterir.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Belirtilen noktanın bunun içinde olup olmadığını gösterir.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Belirtilen noktanın bunun içinde olup olmadığını gösterir.`GraphicsPath` belirtilenin görünür klip bölgesinde[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Belirtilen noktanın bunun içinde olup olmadığını gösterir.`GraphicsPath` , belirtilen kullanarak[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Bir rakamı kaldırır. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Rakamları kaldırır. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Grafik yolunu boşaltır ve[`FillMode`](../fillmode/) ileAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Bunun her şeklindeki şekillerin, şekillerin ve noktaların sırasını tersine çevirir`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Buna bir dikdörtgen ve bir paralelkenar tarafından tanımlanan bir çarpıtma dönüşümü uygular.`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Buna bir dikdörtgen ve bir paralelkenar tarafından tanımlanan bir çarpıtma dönüşümü uygular.`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Buna bir dikdörtgen ve bir paralelkenar tarafından tanımlanan bir çarpıtma dönüşümü uygular.`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Buna bir dikdörtgen ve bir paralelkenar tarafından tanımlanan bir çarpıtma dönüşümü uygular.`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Yola ek bir taslak ekler. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Ek bir taslak ekler.`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Bunu değiştirir`GraphicsPath` bu yol belirtilen kalem tarafından çizildiğinde doldurulan alanı çevreleyen eğrilerle. |

### Örnekler

Bu örnekler, bir Image yüzeyinde Figures oluşturmak ve bunları değiştirmek için GraphicsPath ve Graphics sınıfını kullanır. Örnek yeni bir Image oluşturur ve GraphicsPath sınıfının yardımıyla yolları çizer. Sonunda, yolları yüzeyde işlemek için Graphics sınıfı tarafından sunulan DrawPath yöntemi çağrılır. Son olarak görüntü, Tiff dosya biçiminde dışa aktarılır.

```csharp
[C#]

//Görüntünün bir örneğini oluştur 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics sınıfının bir örneğini oluştur ve başlat
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafik yüzeyini temizle
    graphics.Clear(Color.Wheat);

    // GraphicsPath sınıfının bir örneğini oluşturun
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    // Figure sınıfının bir örneğini oluştur
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Şekil nesnesine Şekiller ekleyin
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // Figure nesnesini GraphicsPath'e ekle
    graphicspath.AddFigure(figure);

    //Siyah renkli Kalem nesnesiyle yol çizin
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Bir TiffOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // tüm değişiklikleri kaydet.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Ayrıca bakınız

* class [ObjectWithBounds](../objectwithbounds/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


