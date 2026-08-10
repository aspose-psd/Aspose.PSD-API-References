---
title: "Enum WarpStyles"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Enum Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles. Jenis-jenis gaya warp yang didukung"
type: docs
weight: 4020
url: /id/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Jenis gaya warp yang didukung.

```csharp
public enum WarpStyles
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Gaya ini diatur ketika lapisan tanpa deformasi |
| Custom | `1` | Gaya dengan pergerakan titik secara acak |
| Arc | `2` | Gaya busur warp |
| ArcUpper | `3` | Gaya Busur Atas warp |
| ArcLower | `4` | Gaya Busur Bawah warp |
| Arch | `5` | Gaya Lengkungan warp |
| Bulge | `6` | Gaya Membengkak warp |
| Flag | `7` | Gaya Bendera warp |
| Fish | `8` | Gaya Ikan warp |
| Rise | `9` | Gaya Naik warp |
| Wave | `10` | Gaya Gelombang warp |
| Twist | `11` | Tipe Putar warp |
| Squeeze | `12` | Tipe Peras warp |
| Inflate | `13` | Jenis pembesaran warp |

## Contoh

Kode berikut menunjukkan cara memanipulasi WarpSettings untuk melakukan transformasi warp pada SmartObjectLayer dan TexLayer.

```csharp
[C#]

string sourceFile = "smart_without_warp.psd";

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
    AllowWarpRepaint = true
};

string[] outputImageFile = new string[4];
string[] outputPsdFile = new string[4];

for (int caseIndex = 0; caseIndex < outputImageFile.Length; caseIndex++)
{
    outputImageFile[caseIndex] = "export_" + caseIndex + ".png";
    outputPsdFile[caseIndex] = "export_" + caseIndex + ".psd";

    using (PsdImage img = (PsdImage)Image.Load(sourceFile, opt))
    {
        foreach (Layer layer in img.Layers)
        {
            if (layer is SmartObjectLayer)
            {
                var smartLayer = (SmartObjectLayer)layer;
                smartLayer.WarpSettings = GetWarpSettingsByIndex(smartLayer.WarpSettings, caseIndex);
            }

            if (layer is TextLayer)
            {
                var textLayer = (TextLayer)layer;

                if (caseIndex != 3)
                {
                    textLayer.WarpSettings = GetWarpSettingsByIndex(textLayer.WarpSettings, caseIndex);
                }
            }
        }

        img.Save(outputPsdFile[caseIndex], new PsdOptions());
    }

    using (PsdImage img = (PsdImage)Image.Load(outputPsdFile[caseIndex], opt))
    {
        img.Save(outputImageFile[caseIndex],
            new PngOptions() { CompressionLevel = 9, ColorType = PngColorType.TruecolorWithAlpha });
    }
}

WarpSettings GetWarpSettingsByIndex(WarpSettings warpParams, int caseIndex)
{
    switch (caseIndex)
    {
        case 0:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 20;
            break;
        case 1:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Vertical;
            warpParams.Value = 10;
            break;
        case 2:
            warpParams.Style = WarpStyles.Flag;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 30;
            break;
        case 3:
            warpParams.Style = WarpStyles.Custom;
            warpParams.MeshPoints[2].Y += 70;
            break;
    }

    return warpParams;
}
```

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


