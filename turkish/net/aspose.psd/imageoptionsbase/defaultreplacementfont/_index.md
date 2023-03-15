---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD for .NET API Referansı
description: ImageOptionsBase mülk. Varsayılan yedek yazı tipini alır veya ayarlar PSD dosyasındaki mevcut katman yazı tipi sistemde sunulmuyorsa taramaya dışa aktarırken metin çizmek için kullanılacak yazı tipi. Varsayılan yazı tipinin uygun adını almak için bir sonraki kod parçacığı kullanılabilir  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily familys  col.Families string defaultFontName  familys0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /tr/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

Varsayılan yedek yazı tipini alır veya ayarlar (PSD dosyasındaki mevcut katman yazı tipi sistemde sunulmuyorsa, taramaya dışa aktarırken metin çizmek için kullanılacak yazı tipi). Varsayılan yazı tipinin uygun adını almak için bir sonraki kod parçacığı kullanılabilir : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familys = col.Families; string defaultFontName = familys[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Mülk değeri

Varsayılan değiştirme yazı tipi.

### Örnekler

Aşağıdaki örnek, varsayılan değiştirme yazı tipini değiştirmek için DefaultReplacementFont özelliğinin nasıl kullanılacağını gösterir.

```csharp
[C#]

// Lütfen Konstantining Font'u kurmayın, çünkü bu test kurulu olmayan yazı tipini değiştirmelidir.
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // Bu şekilde farklı çıktılar için farklı yazı tipleri kullanabilirsiniz. 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Ayrıca bakınız

* class [ImageOptionsBase](../)
* ad alanı [Aspose.PSD](../../imageoptionsbase/)
* toplantı [Aspose.PSD](../../../)


