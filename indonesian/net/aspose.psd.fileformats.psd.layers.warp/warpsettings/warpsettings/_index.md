---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Konstruktor WarpSettings. Menginisialisasi instance baru dari kelas WarpSettings."
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Menginisialisasi instance baru dari kelas [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| meshPoints | PointF[] | Titik mesh dari warp |
| batas | Rectangle | Batas gambar warp |

## Contoh

Kode berikut menunjukkan dukungan properti WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Dapatkan pengaturan warp
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Atur ukuran baru
    // Untuk Photoshop nilai dapat berada di antara 1 dan 50 dan Anda tidak dapat menyimpan file PSD dengan benar.
    warpSettings.GridSize = new Size(100, 100);

    // Atur nilai yang valid
    warpSettings.GridSize = new Size(3, 3);

    // Render file contoh dengan kisi x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Lihat Juga

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Menginisialisasi instance baru dari kelas [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| meshPoints | PointF[] | Titik mesh dari warp |
| batas | Rectangle | Batas gambar warp |
| style | WarpStyles | Gaya warp |

## Contoh

Kode berikut menunjukkan dukungan properti WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Dapatkan pengaturan warp
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Atur ukuran baru
    // Untuk Photoshop nilai dapat berada di antara 1 dan 50 dan Anda tidak dapat menyimpan file PSD dengan benar.
    warpSettings.GridSize = new Size(100, 100);

    // Atur nilai yang valid
    warpSettings.GridSize = new Size(3, 3);

    // Render file contoh dengan kisi x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Lihat Juga

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Menginisialisasi instance baru dari kelas [`WarpSettings`](../).

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | Item PS dengan pengaturan warp |
| batas | Rectangle | Batas gambar warp |

### Lihat Juga

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Menginisialisasi instance baru dari kelas [`WarpSettings`](../).

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| placedResource | PlacedResource | Sumber daya dengan pengaturan warp |

### Lihat Juga

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


