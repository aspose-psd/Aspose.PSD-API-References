---
title: "IColorConverter"
second_title: "Java için Aspose.PSD API Referansı"
description: "Renk dönüştürücüsü."
type: docs
weight: 116
url: /tr/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

Renk dönüştürücüsü.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Geçilen verileri çıktı biçimine dönüştürür. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Geçilen verileri çıktı biçimine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Kaynak format. |
| veri | byte[] | Kaynak veri. |
| offset | int | Veri kopyalamanın başlaması gereken bayt cinsinden ofset. |
| bitStart | int | Bit başlangıcı. Not: bu değer byte hizalı bir değer değildir, bunun yerine kopyalamanın başlaması gereken gerçek bittir. |
| samplesCount | int | Örnek sayısı. |
| linesCount | int | Satır sayısı. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Hedef format. |
| outputData | byte[] | Çıktı verileri. |
| outputOffset | int | Veri kopyalamanın başlaması gereken çıktı ofseti. |

**Returns:**
int - Dönüştürülen bayt sayısı.
