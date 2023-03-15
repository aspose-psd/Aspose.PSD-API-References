---
title: Class TiffDataType
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Tiff.TiffDataType sınıf. Tiff veri türü.
type: docs
weight: 4210
url: /tr/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

Tiff veri türü.

```csharp
public abstract class TiffDataType : IComparable
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Ek veri boyutunu bayt cinsinden alır (12 baytın etiket verilerini sığdırmak için yeterli olmaması durumunda). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Öğe sayısını alır. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Ek veri boyutunu bayt cinsinden alır (12 baytın etiket verilerini sığdırmak için yeterli olmaması durumunda). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Etiket kimliği tamsayı gösterimini alır. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Etiket verilerinin geçerli olup olmadığını gösteren bir değer alır. Geçerli etiket, korunabilecek verileri içerir. Geçersiz etiket depolanamaz. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Etiket kimliğini alır. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Etiket türünü alır. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Bu veri türünün içerdiği değeri alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Etiket verilerini okur. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Geçerli örneği aynı türden başka bir nesneyle karşılaştırır ve geçerli örneğin diğer nesneyle sıralama düzeninde aynı konumda olup olmadığını gösteren bir tamsayı döndürür. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Bu örneğin derin bir klonunu gerçekleştirir. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | a döndürürString bu örneği temsil eder. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Ek etiket verilerini yazar. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Etiket verilerini yazar. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* toplantı [Aspose.PSD](../../)


