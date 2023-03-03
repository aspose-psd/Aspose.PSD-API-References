---
title: Class DropShadowEffect
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect kelas. Efek Lapisan Bayangan Jatuh
type: docs
weight: 2120
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

Efek Lapisan Bayangan Jatuh

```csharp
public class DropShadowEffect : IShadowEffect
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Mendapatkan atau mengatur sudut dalam derajat. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Mendapat atau menyetel mode campuran. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Mendapat atau mengatur warna. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Mendapat atau mengatur jarak dalam piksel. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Mendapat jenis efek |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini terlihat. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [tersingkir]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Mendapat atau mengatur kebisingan. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Mendapat atau mengatur opacity. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Mendapat atau menyetel nilai buram dalam piksel. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Mendapat atau menetapkan intensitas sebagai persen. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [gunakan sudut ini di semua efek lapisan]. |

### Contoh

Kode berikut menunjukkan dukungan untuk properti PsdImage.GlobalAngle untuk mengubah nilai sudut global.

```csharp
[C#]

// Ketika properti DropShadowEffect.UseGlobalLight 'benar', maka objek DropShadowEffect menggunakan nilai sudut dari properti PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

Kode berikut menunjukkan penggunaan properti Opacity dari DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Contoh dengan Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Contoh dengan Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Lihat juga

* interface [IShadowEffect](../ishadoweffect/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* perakitan [Aspose.PSD](../../)


