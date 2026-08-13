---
title: "Sınıf TiffOptions"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageOptions.TiffOptions sınıfı. Tiff dosya formatı seçenekleri. Genişlik ve yükseklik etiketlerinin, görüntü oluşturulurken genişlik ve yükseklik parametreleriyle üzerine yazılacağını, bu nedenle doğrudan belirtilmelerine gerek olmadığını unutmayın. Birçok seçeneğin varsayılan bir değer döndürdüğünü, bunun bu seçeneğin etiket değeri olarak açıkça ayarlandığı anlamına gelmediğini unutmayın. Etiketi doğrulamak için Tags property veya ilgili IsTagPresent method kullanın."
type: docs
weight: 5460
url: /tr/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

tiff dosya formatı seçenekleri. Genişlik ve yükseklik etiketlerinin, görüntü oluşturulurken genişlik ve yükseklik parametreleriyle üzerine yazılacağını, bu nedenle doğrudan belirtmenize gerek olmadığını unutmayın. Birçok seçeneğin varsayılan bir değer döndürdüğünü, bunun bu seçeneğin etiket değeri olarak açıkça ayarlandığı anlamına gelmediğini unutmayın. Etiketin mevcut olduğunu doğrulamak için Tags özelliğini veya ilgili IsTagPresent yöntemini kullanın.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | `TiffOptions` sınıfının yeni bir örneğini başlatır. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | `TiffOptions` sınıfının yeni bir örneğini başlatır. Varsayılan olarak küçük uçlu (little endian) düzen kullanılır. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | `TiffOptions` sınıfının yeni bir örneğini başlatır. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | `TiffOptions` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Alfa depolama seçeneğini alır veya ayarlar. Belirtilmemiş (Unspecified) dışındaki seçenekler, 3'ten fazla [`SamplesPerPixel`](./samplesperpixel/) tanımlandığında kullanılır. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Sanatçıyı alır veya ayarlar. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Piksel başına bit sayısını alır. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Örnek başına bit sayısını alır veya ayarlar. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Tiff bayt sırasını gösteren bir değeri alır veya ayarlar. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Renk haritasını alır veya ayarlar. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Sıkıştırılmış görüntü kalitesini alır veya ayarlar. Jpeg sıkıştırmasıyla birlikte kullanılır. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Sıkıştırmayı alır veya ayarlar. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Telif hakkını alır veya ayarlar. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Tarih ve saati alır veya ayarlar. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | Varsayılan bellek tahsis sınırını alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedekleme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizerken kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Belgenin adını alır veya ayarlar. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | EXIF IFD'ye işaretçiyi alır veya ayarlar. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Faks t4 seçeneklerini alır veya ayarlar. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | TIFF dosya standardını alır veya ayarlar. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Byte bit doldurma sırasını alır veya ayarlar. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Yarı ton ipuçlarını alır veya ayarlar. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Icc profil akışını alır veya ayarlar. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Görüntü açıklamasını alır veya ayarlar. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Görüntü uzunluğunu alır veya ayarlar. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Görüntü genişliğini alır veya ayarlar. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Mürekkep adlarını alır veya ayarlar. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Ek örneklerin mevcut olup olmadığını gösteren bir değeri alır. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Görüntünün döşeli olup olmadığını gösteren bir değeri alır. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | `TiffOptions`'in doğru yapılandırılıp yapılandırılmadığını gösteren bir değeri alır. Başarısızlık nedenini bulmak için Validate metodunu kullanın. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Maksimum örnek değerini alır veya ayarlar. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Minimum örnek değerini alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Yönlendirmeyi alır veya ayarlar. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Sayfa adını alır veya ayarlar. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Sayfa numarası etiketini alır veya ayarlar. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Fotometrik değeri alır veya ayarlar. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Planar yapılandırmayı alır veya ayarlar. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | LZW sıkıştırması için öngörücüyü alır veya ayarlar. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Bileşenlerin önceden çarpılmış olması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Çözünürlük birimini alır veya ayarlar. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Şerit başına satır sayısını alır veya ayarlar. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Örnek formatını alır veya ayarlar. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Piksel başına örnekleri alır. Bu özellik değerini değiştirmek için [`BitsPerSample`](./bitspersample/) özellik ayarlayıcısını kullanın. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Tarayıcı üreticisini alır veya ayarlar. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Tarayıcı modelini alır veya ayarlar. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Maksimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Minimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Yazılım tipini alır veya ayarlar. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Şerit bayt sayılarını alır veya ayarlar. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Şerit ofsetlerini alır veya ayarlar. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Bu alt dosyada bulunan veri türünün genel bir göstergesini alır veya ayarlar. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Etiketleri alır veya ayarlar. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Hedef yazıcıyı alır veya ayarlar. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Eşikleme değerini alır veya ayarlar. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Karoların bayt sayılarını alır veya ayarlar. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Karol uzunluğunu alır veya ayarlar. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Karol ofsetlerini alır veya ayarlar. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Karol genişliğini alır veya ayarlar. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Toplam sayfaları alır. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Geçerli etiket sayısını alır. Bu, toplam etiket sayısı değil, korunabilecek etiketlerin sayısıdır. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Görüntü yazarını alır veya ayarlar, Windows Explorer tarafından kullanılır. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Görüntü üzerindeki yorumu alır veya ayarlar, Windows Explorer tarafından kullanılır. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Görüntü konusunu alır veya ayarlar, Windows Explorer tarafından kullanılır. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | x konumunu alır veya ayarlar. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır veya ayarlar. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır veya ayarlar. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | x çözünürlüğünü alır veya ayarlar. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | YCbCrCoefficients değerini alır veya ayarlar. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | y konumunu alır veya ayarlar. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | y çözünürlüğünü alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Yeni bir etiket ekler. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Etiketleri ekler. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Etiketin örneğini türüne göre alır. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Etiketin seçeneklerde bulunup bulunmadığını belirler. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Etiketi kaldırır. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Seçeneklerin geçerli bir etiket kombinasyonuna sahip olup olmadığını doğrular. |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Geçerli etiket sayısını alır. |

## Örnekler

Bu örnek, dışa aktarma amaçları için SaveOptions ad alanındaki farklı sınıfların kullanımını gösterir. Psd türünde bir görüntü Image örneğine yüklenir ve ardından çeşitli formatlara dışa aktarılır.

```csharp
[C#]

//Image sınıfının bir örneğine mevcut bir görüntüyü yükle
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Varsayılan seçenekleri kullanarak BMP dosya formatına dışa aktar
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Varsayılan seçenekleri kullanarak JPEG dosya formatına dışa aktar
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Varsayılan seçenekleri kullanarak JPEG 2000 dosya formatına dışa aktar
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Varsayılan seçenekleri kullanarak PNG dosya formatına dışa aktar
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Varsayılan seçenekleri kullanarak TIFF dosya formatına dışa aktar
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

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

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


