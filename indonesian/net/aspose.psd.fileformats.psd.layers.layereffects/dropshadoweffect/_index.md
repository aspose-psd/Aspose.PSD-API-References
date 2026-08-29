---
title: "Kelas DropShadowEffect"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect. Efek Lapisan Drop Shadow."
type: docs
weight: 2310
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
{{< psd/tize >}}
## DropShadowEffect class

Efek lapisan Drop Shadow.

```csharp
public class DropShadowEffect : IShadowEffect
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Mendapatkan atau mengatur sudut dalam derajat. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Mendapatkan atau mengatur mode perpaduan. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Mendapatkan atau mengatur warna. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Mendapatkan atau mengatur jarak dalam piksel. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Mendapatkan tipe efek |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [knocks out]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Mendapatkan atau mengatur noise. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Mendapatkan atau mengatur nilai blur dalam piksel. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Mendapatkan atau mengatur intensitas sebagai persentase. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use this angle in all of the layer effects]. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/geteffectbounds/)(Rectangle, int) | Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan masukan. |

## Contoh

Kode berikut menunjukkan dukungan untuk properti PsdImage.GlobalAngle untuk mengubah nilai sudut global.

```csharp
[C#]

// Ketika properti DropShadowEffect.UseGlobalLight bernilai 'true', objek DropShadowEffect menggunakan nilai sudut dari properti PsdImage.GlobalAngle.

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

### Lihat Juga

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


