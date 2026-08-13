---
title: "Class StringFormat"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.StringFormat class. Metin yerleşim bilgilerini, hizalama yönü ve sekme durakları gibi öğeleri, üç nokta ekleme, ulusal rakam ikamesi ve OpenType özellikleri gibi görüntü manipülasyonlarını kapsüller. Bu class kalıtılamaz."
type: docs
weight: 6200
url: /tr/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

Metin yerleşim bilgilerini (hizalama, yönelim ve sekme durakları gibi), görüntü manipülasyonlarını (üç nokta ekleme ve ulusal rakam ikamesi gibi) ve OpenType özelliklerini kapsüller. Bu sınıf miras alınamaz.

```csharp
public sealed class StringFormat : DisposableObject
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Yeni bir `StringFormat` nesnesi başlatır. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Belirtilen mevcut `StringFormat` nesnesinden yeni bir `StringFormat` nesnesi başlatır. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Belirtilen [`StringFormatFlags`](../stringformatflags/) enumarasyonu ve dil ile yeni bir `StringFormat` nesnesi başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Genel bir varsayılan `StringFormat` nesnesi alır. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Genel bir tipografik `StringFormat` nesnesi alır. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Dikey düzlemde metin hizalama bilgilerini alır veya ayarlar. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | Özel karakter tanımlayıcısını alır veya ayarlar. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Yerel rakamlar batı rakamlarıyla değiştirildiğinde kullanılan dili alır veya ayarlar. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Rakam değiştirme için kullanılacak yöntemi alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını alır. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Biçimlendirme bilgilerini içeren bir [`StringFormatFlags`](../stringformatflags/) enum değerini alır veya ayarlar. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Bu `StringFormat` nesnesi için [`HotkeyPrefix`](../hotkeyprefix/) nesnesini alır veya ayarlar. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Yatay düzlemde satır hizalamasını alır veya ayarlar. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Sekme durakları arasındaki mesafelerin, [`PageUnit`](../graphics/pageunit/) özelliğiyle belirtilen birimlerdeki dizisini alır. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Bu `StringFormat` nesnesi için [`StringTrimming`](../stringtrimming/) enum değerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Bu `StringFormat` nesnesinin derin bir kopyasını oluşturur. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | Nesnelerin eşit olup olmadığını kontrol eder. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | Geçerli nesnenin karma kodunu al. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Bu `StringFormat` nesnesi için sekme duraklarını ayarlar. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Bu `StringFormat` nesnesini insan tarafından okunabilir bir dizeye dönüştürür. |

### Ayrıca Bakınız

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


