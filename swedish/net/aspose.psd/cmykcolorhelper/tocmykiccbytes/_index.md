---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD för .NET API‑referens"
description: "CmykColorHelper-metoden. Konverterar RGB till CMYK med anpassade ICC-profiler"
type: docs
weight: 120
url: /sv/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

Konverterar RGB till CMYK med anpassade ICC-profiler.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | Int32[] | RGB-färgerna presenteras som 32‑bitars heltalsvärden. |
| startIndex | Int32 | Startindexet för RGB-färgen. |
| längd | Int32 | Antalet RGB-pixlar att konvertera. |
| rgbIccStream | Ström | RGB-profilströmmen. |
| cmykIccStream | Ström | CMYK-profilströmmen. |

### Returvärde

CMYK-färgerna presenteras som en byte-array.

### Se även

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


