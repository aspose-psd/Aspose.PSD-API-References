---
title: "Sınıf RawColor"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor sınıfı. Raw Color Sınıfı, herhangi bir kanal sayısı, renk modu ve bit derinliğine sahip renkleri depolamaya yardımcı olur. Lütfen bazı iç sınıfların RawColor'ı yerel formatına dönüştürmede sorun yaşayabileceğini unutmayın; bu nedenle API size CMYK rengi sağlıyorsa, sağlanan formatı kullanmak daha güvenilirdir. Ayrıca Raw Color'ın dönüştürülebileceği bazı durumlar da olabilir."
type: docs
weight: 1650
url: /tr/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class, herhangi bir kanal sayısı, herhangi bir renk modu ve herhangi bir bit derinliğiyle renkleri depolamaya yardımcı olur. Lütfen unutmayın, bazı iç sınıflar RawColor'ı yerel formatına dönüştürürken sorun yaşayabilir, bu nedenle API size CMYK rengi sağlıyorsa, verilen formatı kullanmak daha güvenilirdir. Ayrıca, Raw Color'ın dönüştürülebileceği bazı durumlar da olabilir.

```csharp
public sealed class RawColor
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | `RawColor` sınıfının yeni bir örneğini başlatır. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Önceden tanımlı renk modlarını kullanarak piksel veri formatından `RawColor` sınıfının yeni bir örneğini başlatır |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Renk için izlenecek mod. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Rengin bileşenlerini alır. Her bileşen ayrı bir kanaldır ve popüler olmayan bir renk şeması kullanıyorsanız, her kanalla ayrı ayrı çalışmak daha iyidir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Belirtilen Nesnenin bu örnek ile eşit olup olmadığını belirler. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Rengi mümkünse int olarak alır. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Rengi mümkünse long olarak alır. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Raw Color'ın bit derinliğini alır. Örneğin, kanal/bileşen başına 8 bit olan ARGB renk için toplam 32 bit derinlik, kanal/bileşen başına 16 bit olan tam ARGB renk için ise 64'tür. Bit derinliği, kanalların bit derinliklerinin toplamından elde edilir. Farklı kanalların farklı bit derinliklerine sahip olması mümkündür. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Renk modunun adını alır. Renk modu adı, kanallar/bileşen adlarından oluşur. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Geçerli nesnenin karma kodunu al. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Mümkünse int argümanından tüm kanallara veri ayarlar. |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Mümkünse int argümanından tüm kanallara veri ayarlar. |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | `==` operatörünü uygular. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | `!=` operatörünü uygular. |

## Örnekler

Aşağıdaki kod, eski Color yapısı yerine RawColor sınıfının desteğini gösterir.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


