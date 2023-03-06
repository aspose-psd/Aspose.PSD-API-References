---
title: Class StringFormat
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.StringFormat sınıf. Metin düzeni bilgilerini hizalama yönlendirme ve sekme durakları gibi görüntüleme manipülasyonlarını üç nokta ekleme ve ulusal rakam değiştirme gibi ve OpenType özelliklerini kapsüller. Bu sınıf miras alınamaz.
type: docs
weight: 5670
url: /tr/net/aspose.psd/stringformat/
---
## StringFormat class

Metin düzeni bilgilerini (hizalama, yönlendirme ve sekme durakları gibi), görüntüleme manipülasyonlarını (üç nokta ekleme ve ulusal rakam değiştirme gibi) ve OpenType özelliklerini kapsüller. Bu sınıf miras alınamaz.

```csharp
public sealed class StringFormat : DisposableObject
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Yeni bir başlatır`StringFormat` nesne. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Yeni bir başlatır`StringFormat` belirtilen mevcut nesneden`StringFormat` nesne. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Yeni bir başlatır`StringFormat` belirtilen nesne[`StringFormatFlags`](../stringformatflags/) numaralandırma ve dil. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Genel bir varsayılan alır`StringFormat` nesne. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Genel bir tipografi alır`StringFormat` nesne. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Dikey düzlemde metin hizalama bilgilerini alır veya ayarlar. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Batı rakamları yerine yerel rakamlar kullanıldığında kullanılan dili alır veya ayarlar. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Rakam değiştirme için kullanılacak yöntemi alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Bir metin satırının başı ile ilk sekme durağı arasındaki boşluk sayısını alır. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Alır veya ayarlar[`StringFormatFlags`](../stringformatflags/) biçimlendirme bilgilerini içeren numaralandırma. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Şunu alır veya ayarlar:[`HotkeyPrefix`](../hotkeyprefix/) bunun için itiraz`StringFormat` nesne. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Yatay düzlemde çizgi hizalamasını alır veya ayarlar. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | tarafından belirtilen birimlerde sekme durakları arasındaki mesafelerin bir dizisini alır.[`PageUnit`](../graphics/pageunit/) özellik. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Şunu alır veya ayarlar:[`StringTrimming`](../stringtrimming/) Bunun için numaralandırma`StringFormat` nesne. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Bunun derin bir klonunu oluşturur`StringFormat` nesne. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Bunun için sekme duraklarını ayarlar`StringFormat` nesne. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Bunu dönüştürür`StringFormat` okunabilir bir dizeye itiraz. |

### Ayrıca bakınız

* class [DisposableObject](../disposableobject/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


