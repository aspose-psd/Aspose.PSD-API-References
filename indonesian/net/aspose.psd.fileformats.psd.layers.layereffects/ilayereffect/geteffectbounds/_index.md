---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode ILayerEffect. Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan masukan"
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan masukan.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layerBounds | Rectangle | Batas piksel lapisan. |
| globalAngle | Int32 | Sudut global untuk menghitung sudut cahaya global. |

### Nilai Kembalian

Batas piksel efek berdasarkan batas piksel lapisan masukan.

## Contoh

Menunjukkan cara mendapatkan batas lapisan dengan efek dan mengekspornya dengan ukuran yang tepat.

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // Untuk menyimpan dalam batas PsdImage pada lokasi lapisan asli

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### Lihat Juga

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


