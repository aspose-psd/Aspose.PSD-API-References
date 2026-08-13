---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PattResourceData yöntemi. Desenin piksel tamponunu ve hedef boyutunu ayarlar, Width / Height günceller ve varsayılan sıkıştırma modu 0 kullanarak kaydetmek için verileri depolar."
type: docs
weight: 110
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

Desenin piksel tamponunu ve hedef boyutunu ayarlar, [`Width`](../width/) / [`Height`](../height/) günceller ve varsayılan sıkıştırma modu (0) kullanarak kaydetmek için verileri depolar.

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | Int32[] | `0xAARRGGBB` formatında 32-bit pikseller. |
| bounds | Rectangle | Desenin piksel sınırları. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Piksel dizisi uzunluğu sınır alanına eşit olmalıdır. |

### Ayrıca Bakınız

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


