---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "GradientColorPoint konstruktor. Menginisialisasi instance baru dari kelas GradientColorPoint"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

Menginisialisasi instance baru dari kelas [`GradientColorPoint`](../).

```csharp
public GradientColorPoint()
```

### Lihat Juga

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Menginisialisasi instance baru dari kelas [`GradientColorPoint`](../).

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| warna | Warna | Titik warna pada gradien. |
| lokasi | Int32 | Lokasi titik warna pada gradien. |
| medianPointLocation | Int32 | Lokasi titik gradien median. |

## Contoh

Contoh berikut menunjukkan cara membuat/mengedit objek efek GradientOverlayEffect dalam lapisan.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Membuat/Mendapatkan dan mengedit efek overlay gradien dalam lapisan.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Cari GradientOverlayEffect dalam lapisan.
    foreach (ILayerEffect effect in layerBlendOptions.Effects)
    {
        gradientOverlayEffect = effect as GradientOverlayEffect;
        if (gradientOverlayEffect != null)
        {
            break;
        }
    }

    if (gradientOverlayEffect == null)
    {
        // Anda dapat membuat GradientOverlayEffect baru jika belum ada.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Tambahkan sedikit transparansi pada efek.
    gradientOverlayEffect.Opacity = 200;

    // Ubah mode perpaduan efek gradien.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Mendapatkan objek GradientFillSettings untuk mengkonfigurasi pengaturan overlay gradien.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // Mengatur gradien baru dengan dua warna.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Mengatur kemiringan gradien pada sudut 80 derajat.
    settings.Angle = 80;

    // Skala efek gradien hingga 150%.
    settings.Scale = 150;

    // Mengatur tipe gradien.
    settings.GradientType = GradientType.Linear;

    // Buat gradien menjadi tidak tembus pandang dengan mengatur opasitas menjadi 100% pada setiap titik transparansi.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Lihat Juga

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


