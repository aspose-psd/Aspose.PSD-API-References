---
title: Class ResolutionInfoResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Resources.ResolutionInfoResource sınıf. Çözünürlük bilgisi source
type: docs
weight: 3880
url: /tr/net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---
## ResolutionInfoResource class

Çözünürlük bilgisi source

```csharp
public sealed class ResolutionInfoResource : ResourceBlock
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ResolutionInfoResource](resolutioninforesource/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/datasize/) { get; } | Kaynak veri boyutunu bayt cinsinden alır. |
| [HDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hdpi/) { get; set; } | Yatay DPI. |
| [HeightDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/heightdisplayunit/) { get; set; } | Boy görüntüleme birimini alır veya ayarlar. |
| [HResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hresdisplayunit/) { get; set; } | Yatay çözünürlük için görüntüleme birimleri. Bu yalnızca kullanıcı arabirimini etkiler; çözünürlük hala piksel/inç. olarak PSD file dosyasında saklanır |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/minimalversion/) { get; } | Gereken minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Boyutu çift yapmak için doldurulmuş Pascal dizesi (boş ad iki bayt 0'dan oluşur). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Verileri dahil olmak üzere kaynak bloğu boyutunu bayt cinsinden alır. |
| [VDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vdpi/) { get; set; } | Dikey DPI. |
| [VResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vresdisplayunit/) { get; set; } | Dikey çözünürlük için görüntüleme birimleri. |
| [WidthDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/widthdisplayunit/) { get; set; } | Genişlik görüntüleme birimini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

### Ayrıca bakınız

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* toplantı [Aspose.PSD](../../)


