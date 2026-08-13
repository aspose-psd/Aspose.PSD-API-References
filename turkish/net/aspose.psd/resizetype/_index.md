---
title: "Enum ResizeType"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ResizeType enum. Yeniden boyutlandırma tipini belirtir."
type: docs
weight: 5900
url: /tr/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

Yeniden boyutlandırma tipini belirtir.

```csharp
public enum ResizeType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | `0` | Yeniden boyutlandırma işlemi sırasında pikseller korunmaz. |
| LeftTopToLeftTop | `1` | Yeni görüntünün sol üst noktası, orijinal görüntünün sol üst noktasıyla aynı olacaktır. Gerekirse kırpma gerçekleşir. |
| RightTopToRightTop | `2` | Yeni görüntünün sağ üst noktası, orijinal görüntünün sağ üst noktasıyla aynı olacaktır. Gerekirse kırpma gerçekleşir. |
| RightBottomToRightBottom | `3` | Yeni görüntünün sağ alt noktası, orijinal görüntünün sağ alt noktasıyla aynı olacaktır. Gerekirse kırpma gerçekleşir. |
| LeftBottomToLeftBottom | `4` | Yeni görüntünün sol alt noktası, orijinal görüntünün sol alt noktasıyla aynı konumda olacaktır. Gerekirse kırpma yapılacaktır. |
| CenterToCenter | `5` | Yeni görüntünün merkezi, orijinal görüntünün merkeziyle aynı konumda olacaktır. Gerekirse kırpma yapılacaktır. |
| LanczosResample | `6` | a=3 ile lanczos algoritması kullanılarak yeniden örnekleme yapılır. |
| NearestNeighbourResample | `7` | En yakın komşu algoritması kullanılarak yeniden örnekleme yapılır. |
| AdaptiveResample | `8` | Ağırlıklı ve karıştırılmış rasyonel fonksiyon ve lanczos3 interpolasyon algoritmalarına dayalı uyarlamalı algoritma kullanılarak yeniden örnekleme yapılır. |
| BilinearResample | `9` | Bilinear interpolasyon kullanılarak yeniden örnekleme yapılır. Gerektiğinde yeniden örneklemeden önce gürültüyü kaldırmak için görüntü ön filtrelemesine izin verilir. |
| HighQualityResample | `10` | Yüksek kaliteli yeniden örnekleme |
| CatmullRom | `11` | Catmull-Rom kübik interpolasyon yöntemi. |
| CubicConvolution | `12` | Kübik Konvolüsyon interpolasyon yöntemi |
| CubicBSpline | `13` | CubicBSpline kübik interpolasyon yöntemi |
| Mitchell | `14` | Mitchell kübik interpolasyon yöntemi |
| SinC | `15` | Sinc (Lanczos3) kübik interpolasyon yöntemi |
| Bell | `16` | Bell interpolasyon yöntemi |

## Örnekler

İşte aşağıdaki kod, yeni SinC yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni Bell yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni Mitchell yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni CatmullRom yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni CubicBSpline yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni CubicConvolution yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


