---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD for .NET API Referansı"
description: "IColorConverter yöntemi. Geçilen verileri çıktı formatına dönüştürür"
type: docs
weight: 10
url: /tr/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

Geçilen verileri çıktı formatına dönüştürür.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Kaynak format. |
| veri | Byte[] | Kaynak veri. |
| offset | Int32 | Veri kopyalamanın başlaması gereken bayt cinsinden ofset. |
| bitStart | Int32 | Bit başlangıcı. Bu değerin bayt hizalı bir değer olmadığını, bunun yerine kopyalamanın başlaması gereken gerçek bit olduğunu unutmayın. |
| samplesCount | Int32 | Örnek sayısı. |
| linesCount | Int32 | Satır sayısı. |
| destFormat | PixelDataFormat | Hedef format. |
| outputData | Byte[] | Çıktı verisi. |
| outputOffset | Int32 | Veri kopyalamanın başlaması gereken çıktı ofseti. |

### Dönüş Değeri

Dönüştürülen bayt sayısı.

### Ayrıca Bakınız

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


