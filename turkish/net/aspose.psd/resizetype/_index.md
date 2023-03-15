---
title: Enum ResizeType
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ResizeType Sıralama. Yeniden boyutlandırma türünü belirtir.
type: docs
weight: 5370
url: /tr/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Yeniden boyutlandırma türünü belirtir.

```csharp
public enum ResizeType
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| None | `0` | Yeniden boyutlandırma işlemi sırasında pikseller korunmaz. |
| LeftTopToLeftTop | `1` | Yeni görüntünün sol üst noktası, orijinal görüntünün sol üst noktasıyla çakışacaktır. Gerekirse kırpma gerçekleşir. |
| RightTopToRightTop | `2` | Yeni görüntünün sağ üst noktası, orijinal görüntünün sağ üst noktasıyla çakışacaktır. Gerekirse kırpma gerçekleşir. |
| RightBottomToRightBottom | `3` | Yeni görüntünün sağ alt noktası, orijinal görüntünün sağ alt noktasıyla çakışacaktır. Gerekirse kırpma gerçekleşir. |
| LeftBottomToLeftBottom | `4` | Yeni görüntünün sol alt noktası, orijinal görüntünün sol alt noktasıyla çakışacaktır. Gerekirse kırpma gerçekleşir. |
| CenterToCenter | `5` | Yeni görüntünün merkezi, orijinal görüntünün merkeziyle çakışacaktır. Gerekirse kırpma gerçekleşir. |
| LanczosResample | `6` | a=3. ile lanczos algoritmasını kullanarak yeniden örnekleme |
| NearestNeighbourResample | `7` | En yakın komşu algoritmasını kullanarak yeniden örnekleme. |
| AdaptiveResample | `8` | Ağırlıklı ve harmanlanmış rasyonel işleve ve lanczos3 enterpolasyon algoritmalarına dayalı uyarlamalı algoritma kullanarak yeniden örnekleme. |
| BilinearResample | `9` | Bilineer enterpolasyon kullanarak yeniden örnekleme. Gerektiğinde yeniden örneklemeden önce gürültüyü gidermek için görüntü ön filtrelemesine izin verilir |
| HighQualityResample | `10` | Yüksek kaliteli yeniden örnekleme |
| CatmullRom | `11` | Catmull-Rom kübik enterpolasyon yöntemi. |
| CubicConvolution | `12` | Kübik Evrişim enterpolasyon yöntemi |
| CubicBSpline | `13` | CubicBSpline kübik enterpolasyon yöntemi |
| Mitchell | `14` | Mitchell kübik enterpolasyon yöntemi |
| SinC | `15` | Sinc (Lanczos3) kübik enterpolasyon yöntemi |
| Bell | `16` | Bell enterpolasyon yöntemi |

### Örnekler

Aşağıdaki kod, yeni bir SinC yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, bir görüntünün yeni bir Bell yeniden boyutlandırma türüyle nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, yeni bir Mitchell yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, yeni bir CatmullRom yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, yeni bir CubicBSpline yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, bir görüntünün yeni bir CubicConvolution yeniden boyutlandırma türüyle nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


