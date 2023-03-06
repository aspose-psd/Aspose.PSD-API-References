---
title: Class PsdLoadOptions
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions sınıf. Psd yükleme seçenekleri
type: docs
weight: 4770
url: /tr/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Psd yükleme seçenekleri

```csharp
public class PsdLoadOptions : LoadOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Çarpıtma dönüşümü olsun ya da olmasın, işlenen görüntüyle kaydedilip kaydedilmeyeceğini ayarlar. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Şunu alır veya ayarlar:[`Image`](../../aspose.psd/image/) arka plan[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Veri kurtarma modunu alır veya ayarlar. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | [alfa kanalını yoksay]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | UpdateText işlemi yürütülürken PSD metin katmanı sabit genişliğinin göz ardı edilip edilmeyeceğini gösteren bir değer alır veya ayarlar. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | [yükleme efektleri kaynağı] (varsayılan olarak kaynak yüklenmemiş) olup olmadığını belirten bir değer alır veya ayarlar. Bu seçenek ayarlandığında yalnızca desteklenen efektler nihai birleştirilmiş görüntüye dönüştürülür. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | [salt okunur modu kullan] olup olmadığını belirten bir değer alır veya ayarlar. Bu, Adobe Photoshop ile aynı uyumluluk için desteklenen salt okunur moddur. Bu seçenek ayarlandığında, katmanlar için uygulanan tüm değişiklikler nihai görüntüye kaydedilmeyecektir. Tüm veriler ImageData bölümünden kullanılır, bu nedenle Photoshop ile aynıdır. Varsayılan olarak, yüklenen tüm görüntüler Adobe Photoshop uyumlu ile aynı değildir. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | [Yük efektleri kaynağı için disk kullan] olup olmadığını gösteren bir değer alır veya ayarlar (varsayılan olarak efekt kaynağını yüklemek için disk kullanılır, ancak bu değer yanlış olarak ayarlanarak yeterliyse bellek kullanılabilir). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | ICC profil dönüştürmesinin uygulanıp uygulanmayacağını belirten bir değer alır veya ayarlar. |

### Örnekler

Aşağıdaki örnek, belge dönüştürme ilerlemesinin doğru ve istisnasız çalıştığını göstermektedir.

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

### Ayrıca bakınız

* class [LoadOptions](../../aspose.psd/loadoptions/)
* ad alanı [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* toplantı [Aspose.PSD](../../)


