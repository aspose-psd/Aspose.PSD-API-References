---
title: CmykColorHelper.ToCmykIccBytes
second_title: Aspose.PSD för .NET API-referens
description: CmykColorHelper metod. Konverterar RGB till CMYK med hjälp av anpassade ICCprofiler.
type: docs
weight: 120
url: /sv/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

Konverterar RGB till CMYK med hjälp av anpassade ICC-profiler.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | Int32[] | RGB-färgerna presenteras som 32-bitars heltalsvärden. |
| startIndex | Int32 | Startindex för RGB-färg. |
| length | Int32 | Antalet RGB-pixlar som ska konverteras. |
| rgbIccStream | Stream | RGB-profilströmmen. |
| cmykIccStream | Stream | CMYK-profilströmmen. |

### Returvärde

CMYK-färgerna presenteras som en byte-array.

### Se även

* class [CmykColorHelper](../)
* namnutrymme [Aspose.PSD](../../cmykcolorhelper/)
* hopsättning [Aspose.PSD](../../../)


