---
title: IColorConverter.Convert
second_title: Aspose.PSD for .NET API Referansı
description: IColorConverter yöntem. Aktarılan verileri çıktı biçimine dönüştürür.
type: docs
weight: 10
url: /tr/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

Aktarılan verileri çıktı biçimine dönüştürür.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Kaynak biçimi. |
| data | Byte[] | Kaynak veri. |
| offset | Int32 | Veri kopyalamanın başlaması gereken bayt cinsinden uzaklık. |
| bitStart | Int32 | Bit başlangıcı. Bu değerin bayt hizalı bir değer olmadığını, bunun yerine kopyalamanın başlaması gereken gerçek bit olduğunu unutmayın. |
| samplesCount | Int32 | Numuneler sayılır. |
| linesCount | Int32 | Satır sayısı. |
| destFormat | PixelDataFormat | Hedef biçimi. |
| outputData | Byte[] | Çıkış verileri. |
| outputOffset | Int32 | Veri kopyalamanın başlaması gereken çıkış ofseti. |

### Geri dönüş değeri

Dönüştürülen bayt sayısı.

### Ayrıca bakınız

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* ad alanı [Aspose.PSD](../../icolorconverter/)
* toplantı [Aspose.PSD](../../../)


