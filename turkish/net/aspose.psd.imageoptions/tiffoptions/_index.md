---
title: Class TiffOptions
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ImageOptions.TiffOptions sınıf. Tiff dosyası formatı seçenekleri. Görüntü oluşturulurken genişlik ve yükseklik etiketlerinin üzerine genişlik ve yükseklik parametrelerinin yazılacağını unutmayın bu nedenle bunları doğrudan belirtmeye gerek yoktur. Birçok seçeneğin varsayılan bir değer döndürdüğünü unutmayın ancak bu bu seçenek açıkça bir etiket değeri olarak ayarlanır. Etiketin var olduğunu doğrulamak için Etiketler özelliğini veya karşılık gelen IsTagPresent yöntemini kullanın.
type: docs
weight: 4940
url: /tr/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

Tiff dosyası formatı seçenekleri. Görüntü oluşturulurken genişlik ve yükseklik etiketlerinin üzerine genişlik ve yükseklik parametrelerinin yazılacağını unutmayın, bu nedenle bunları doğrudan belirtmeye gerek yoktur. Birçok seçeneğin varsayılan bir değer döndürdüğünü unutmayın, ancak bu, bu seçenek açıkça bir etiket değeri olarak ayarlanır. Etiketin var olduğunu doğrulamak için Etiketler özelliğini veya karşılık gelen IsTagPresent yöntemini kullanın.

```csharp
public class TiffOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Yeni bir örneğini başlatır.`TiffOptions` sınıf. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Yeni bir örneğini başlatır.`TiffOptions` sınıf. Varsayılan olarak küçük endian kuralı kullanılır. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Yeni bir örneğini başlatır.`TiffOptions` sınıf. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Yeni bir örneğini başlatır.`TiffOptions` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Alfa depolama seçeneğini alır veya ayarlar. dışındaki seçeneklerUnspecified 3'ten fazla olduğunda kullanılır[`SamplesPerPixel`](./samplesperpixel/) tanımlanmış. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Sanatçıyı alır veya ayarlar. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Piksel başına bitleri alır. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Örnek başına bitleri alır veya ayarlar. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Tiff bayt sırasını gösteren bir değer alır veya ayarlar. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Renk haritasını alır veya ayarlar. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Sıkıştırılmış görüntü kalitesini alır veya ayarlar. Jpeg sıkıştırmasıyla kullanılır. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Sıkıştırmayı alır veya ayarlar. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Telif hakkını alır veya ayarlar. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Tarih ve saati alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedek yazı tipini alır veya ayarlar (PSD dosyasındaki mevcut katman yazı tipi sistemde sunulmuyorsa, taramaya dışa aktarırken metin çizmek için kullanılacak yazı tipi). Varsayılan yazı tipinin uygun adını almak için bir sonraki kod parçacığı kullanılabilir : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familys = col.Families; string defaultFontName = familys[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Belgenin adını alır veya ayarlar. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | İşaretçiyi EXIF IFD'ye getirir veya ayarlar. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Faks t4 seçeneklerini alır veya ayarlar. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | TIFF dosya standardını alır veya ayarlar. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Bayt bit doldurma sırasını alır veya ayarlar. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [tam çerçeve]. olup olmadığını gösteren bir değer alır veya ayarlar. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Yarım ton ipuçlarını alır veya ayarlar. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Icc profil akışını alır veya ayarlar. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Görüntü açıklamasını alır veya ayarlar. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Görüntü uzunluğunu alır veya ayarlar. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Görüntü genişliğini alır veya ayarlar. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Mürekkep adlarını alır veya ayarlar. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Ekstra örneklerin mevcut olup olmadığını gösteren bir değer alır. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Görüntünün döşenip döşenmediğini gösteren bir değer alır. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | olup olmadığını gösteren bir değer alır.`TiffOptions` uygun şekilde yapılandırılmıştır. Hata nedenini bulmak için Validate yöntemini şu şekilde kullanın. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Maksimum örnek değerini alır veya ayarlar. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Minimum numune değerini alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Yönü alır veya ayarlar. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Sayfa adını alır veya ayarlar. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Sayfa numarası etiketini alır veya ayarlar. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Fotometrik değeri alır veya ayarlar. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Düzlemsel yapılandırmayı alır veya ayarlar. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | LZW sıkıştırması için öngörücüyü alır veya ayarlar. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Bileşenlerin önceden çoğaltılması gerekip gerekmediğini belirten bir değer alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Çözünürlük birimini alır veya ayarlar. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Şerit başına satırları alır veya ayarlar. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Örnek formatı alır veya ayarlar. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Piksel başına örnekleri alır. Bu özellik değerini değiştirmek için[`BitsPerSample`](./bitspersample/) özellik ayarlayıcı. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Tarayıcı üreticisini alır veya ayarlar. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Tarayıcı modelini alır veya ayarlar. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Maksimum örnek değerini alır veya ayarlar. Değer, örnek verilerle en iyi eşleşen bir alan türüne sahiptir (Byte, Short veya Long türü). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Minimum numune değerini alır veya ayarlar. Değer, örnek verilerle en iyi eşleşen bir alan türüne sahiptir (Byte, Short veya Long türü). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Yazılım türünü alır veya ayarlar. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | . içinde görüntü oluşturmak için kaynağı alır veya ayarlar |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Şerit bayt sayılarını alır veya ayarlar. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Şerit ofsetlerini alır veya ayarlar. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Bu alt dosyada bulunan veri türünün genel bir göstergesini alır veya ayarlar. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Etiketleri alır veya ayarlar. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Hedef yazıcıyı alır veya ayarlar. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Eşiği alır veya ayarlar. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Döşeme bayt sayılarını alır veya ayarlar. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Döşeme uzunluğunu ayarlar. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Döşeme ofsetlerini alır veya ayarlar. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Döşeme genişliğini ayarlar. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Toplam sayfaları alır. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Geçerli etiket sayısını alır. Bu, toplam etiket sayısı değil, korunabilecek etiketlerin sayısıdır. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör tarama seçeneklerini alır veya ayarlar. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Windows Gezgini tarafından kullanılan görüntü yazarını alır veya ayarlar. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Windows Gezgini tarafından kullanılan, görüntüye ilişkin yorumu alır veya ayarlar. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Windows Gezgini tarafından kullanılan özne görüntüsünü alır veya ayarlar. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | x konumunu alır veya ayarlar. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır veya ayarlar. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır veya ayarlar. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | x çözünürlüğünü alır veya ayarlar. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | YCbCrKatsayılarını alır veya ayarlar. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | y konumunu alır veya ayarlar. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | y çözünürlüğünü alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Yeni bir etiket ekler. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Etiketleri ekler. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Türe göre etiket örneğini alır. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Seçeneklerde etiket olup olmadığını belirler. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Etiketi kaldırır. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Seçeneklerin geçerli bir etiket kombinasyonuna sahip olup olmadığını doğrular |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Geçerli etiket sayısını alır. |

### Örnekler

Bu örnek, dışa aktarma amacıyla SaveOptions Ad Alanından farklı sınıfların kullanımını gösterir. Psd türünde bir görüntü, Image örneğine yüklenir ve ardından çeşitli formatlara dışa aktarılır.

```csharp
[C#]

//Mevcut bir görüntüyü Image sınıfının bir örneğine yükleyin
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Varsayılan seçenekleri kullanarak BMP dosya biçimine aktar
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Varsayılan seçenekleri kullanarak JPEG dosya biçimine aktar
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Varsayılan seçenekleri kullanarak JPEG 2000 dosya biçimine aktarın
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Varsayılan seçenekleri kullanarak PNG dosya biçimine aktar
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Varsayılan seçenekleri kullanarak TIFF dosya biçimine aktar
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

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

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* ad alanı [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* toplantı [Aspose.PSD](../../)


