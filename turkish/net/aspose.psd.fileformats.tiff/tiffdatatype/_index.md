---
title: "Sınıf TiffDataType"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Tiff.TiffDataType sınıfı. TIFF veri tipi"
type: docs
weight: 4710
url: /tr/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

tiff veri tipi.

```csharp
public abstract class TiffDataType : IComparable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Etiket verisini sığdırmak için 12 bayt yetersiz olduğunda ek veri boyutunu bayt olarak alır. |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Eleman sayısını alır. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Etiket verisini sığdırmak için 12 bayt yetersiz olduğunda ek veri boyutunu bayt olarak alır. |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Etiket kimliğinin tam sayı temsilini alır. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Etiket verisinin geçerli olup olmadığını gösteren bir değer alır. Geçerli etiket, korunabilecek verileri içerir. Geçersiz etiket saklanamaz. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Etiket kimliğini alır. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Etiket tipini alır. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Bu veri tipinin içerdiği değeri alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Etiket verisini okur. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Mevcut örneği aynı türdeki başka bir nesneyle karşılaştırır ve mevcut örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu belirten bir tam sayı döndürür. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Bu örneğin derin bir kopyasını oluşturur. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Bu örneği temsil eden bir String döndürür. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Ek etiket verilerini yazar. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Etiket verilerini yazar. |

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


