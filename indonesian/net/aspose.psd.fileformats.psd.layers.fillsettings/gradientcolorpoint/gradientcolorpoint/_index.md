---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD untuk Referensi .NET API
description: GradientColorPoint konstruktor. Menginisialisasi instance baru dariGradientColorPoint kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

Menginisialisasi instance baru dari[`GradientColorPoint`](../) kelas.

```csharp
public GradientColorPoint()
```

### Lihat juga

* class [GradientColorPoint](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* perakitan [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

Menginisialisasi instance baru dari[`GradientColorPoint`](../) kelas.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| color | Color | Titik warna pada gradien. |
| location | Int32 | Lokasi titik warna pada gradien. |
| medianPointLocation | Int32 | Lokasi titik gradien median. |

### Contoh

Contoh berikut menunjukkan cara membuat/mengedit objek efek GradientOverlayEffect di lapisan.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// Membuat/Mendapatkan dan mengedit efek gradien overlay dalam sebuah layer.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // Cari GradientOverlayEffect dalam sebuah layer.
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
        // Anda dapat membuat GradientOverlayEffect baru jika tidak ada.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // Tambahkan sedikit transparansi pada efeknya.
    gradientOverlayEffect.Opacity = 200;

    // Ubah mode campuran efek gradien.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // Mendapatkan objek GradientFillSettings untuk mengonfigurasi pengaturan overlay gradien.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // Mengatur gradien baru dengan dua warna.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // Mengatur kemiringan gradien pada sudut 80 derajat.
    settings.Angle = 80;

    // Menskalakan efek gradien hingga 150%.
    settings.Scale = 150;

    // Menyetel jenis gradien.
    settings.GradientType = GradientType.Linear;

    // Jadikan gradien buram dengan menyetel opacity menjadi 100% di setiap titik transparansi.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### Lihat juga

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* perakitan [Aspose.PSD](../../../)


