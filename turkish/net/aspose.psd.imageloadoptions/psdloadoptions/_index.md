---
title: "Class PsdLoadOptions"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageLoadOptions.PsdLoadOptions class. Psd yükleme seçenekleri"
type: docs
weight: 5280
url: /tr/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

Psd yükleme seçenekleri

```csharp
public class PsdLoadOptions : LoadOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | Katman değiştirilmemişse, render sırasında orijinal katman piksellerinin korunup korunmayacağını alır veya ayarlar. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Render edilmiş görüntüyle, eğri dönüşümle birlikte veya olmadan kaydedilip kaydedilmeyeceğini alır veya ayarlar. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | [`Image`](../../aspose.psd/image/) arka plan [`Color`](../../aspose.psd/color/) değerini alır veya ayarlar. |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Veri kurtarma modunu alır veya ayarlar. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Alfa kanalını yok sayma [ignore alpha channel] durumunu gösteren bir değeri alır veya ayarlar. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | PSD metin katmanı sabit genişliğinin UpdateText işlemi yürütülürken yok sayılıp sayılmayacağını gösteren bir değeri alır veya ayarlar. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | [load effects resource] (varsayılan olarak kaynak yüklenmez) durumunu gösteren bir değeri alır veya ayarlar. Bu seçenek ayarlandığında yalnızca desteklenen efektler son birleştirilmiş görüntüye işlenir. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | [use read only mode] durumunu gösteren bir değeri alır veya ayarlar. Bu, Adobe Photoshop ile aynı uyumluluk için desteklenen salt okunur moddur. Bu seçenek ayarlandığında, katmanlara uygulanan tüm değişiklikler son görüntüye kaydedilmez. Tüm veri ImageData bölümünden alınır, bu nedenle Photoshop ile aynı olur. Varsayılan olarak, yüklenen tüm görüntüler Adobe Photoshop ile aynı uyumlu değildir. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | PSD görüntüsü yüklenirken kullanılan salt okunur modu alır veya ayarlar. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | [use disk for load effects resource] (varsayılan olarak efekt kaynağını yüklemek için disk kullanılır, ancak bu değer false olarak ayarlanırsa bellek yeterli olduğunda kullanılabilir) durumunu gösteren bir değeri alır veya ayarlar. |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri alır veya ayarlar. |

## Örnekler

Aşağıdaki örnek, belge dönüştürme ilerlemesinin doğru ve istisna olmadan çalıştığını gösterir.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### Ayrıca Bakınız

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


