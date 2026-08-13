---
title: "ImageOptionsBase.DefaultReplacementFont"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ImageOptionsBase özelliği. Sistem içinde bulunmayan PSD dosyasındaki mevcut katman yazı tipinin rastera dışa aktarılırken metin çizmek için kullanılacak varsayılan yedek yazı tipini alır veya ayarlar. Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName"
type: docs
weight: 20
url: /tr/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
{{< psd/tize >}}
## ImageOptionsBase.DefaultReplacementFont property

Varsayılan yedekleme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizerken kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Property Value

Varsayılan yedek yazı tipi.

## Örnekler

Aşağıdaki örnek, varsayılan yedek yazı tipini değiştirmek için DefaultReplacementFont özelliğinin nasıl kullanılacağını gösterir.

```csharp
[C#]

// Lütfen Konstantin Fontu yüklemeyin, çünkü bu test yüklü olmayan bir yazı tipini değiştirmelidir.
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
{
    // Bu şekilde farklı çıktılar için farklı yazı tipleri kullanabilirsiniz.
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Ayrıca Bakınız

* class [ImageOptionsBase](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


