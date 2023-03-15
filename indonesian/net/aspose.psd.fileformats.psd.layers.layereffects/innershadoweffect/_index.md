---
title: Class InnerShadowEffect
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect kelas. Efek Lapisan Bayangan Dalam
type: docs
weight: 2160
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

Efek Lapisan Bayangan Dalam

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Mendapatkan atau mengatur sudut dalam derajat. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Mendapat atau menyetel mode campuran. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Mendapat atau mengatur warna. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Mendapat atau mengatur jarak dalam piksel. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Mendapat jenis efek |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini terlihat. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Mendapat atau mengatur kebisingan. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Mendapat atau mengatur opacity. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Mendapat atau menyetel nilai buram dalam piksel. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Mendapat atau menetapkan spread (choke) sebagai persentase. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [gunakan sudut ini di semua efek lapisan]. |

### Contoh

Kode berikut menunjukkan cara mengubah pengaturan Efek Lapisan Inner Shadow.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### Lihat juga

* interface [IShadowEffect](../ishadoweffect/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* perakitan [Aspose.PSD](../../)


