---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD for .NET API Referansı"
description: "WarpSettings yapıcı. WarpSettings sınıfının yeni bir örneğini başlatır"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

[`WarpSettings`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| meshPoints | PointF[] | Çarpıtmanın ağ noktaları |
| bounds | Rectangle | Çarpıtma görüntüsünün sınırları |

## Örnekler

Aşağıdaki kod, WarpSettings.GridSize özelliğinin desteğini gösterir.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Çarpıtma ayarlarını al
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Yeni boyutu ayarla
    // Photoshop için değer 1 ile 50 arasında olabilir ve PSD dosyasını doğru şekilde kaydedemezsiniz.
    warpSettings.GridSize = new Size(100, 100);

    // Geçerli değeri ayarla
    warpSettings.GridSize = new Size(3, 3);

    // x3 ızgara ile örnek dosyayı oluştur
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Ayrıca Bakınız

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

[`WarpSettings`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| meshPoints | PointF[] | Çarpıtmanın ağ noktaları |
| bounds | Rectangle | Çarpıtma görüntüsünün sınırları |
| style | WarpStyles | Çarpıtmanın stili |

## Örnekler

Aşağıdaki kod, WarpSettings.GridSize özelliğinin desteğini gösterir.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Çarpıtma ayarlarını al
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Yeni boyutu ayarla
    // Photoshop için değer 1 ile 50 arasında olabilir ve PSD dosyasını doğru şekilde kaydedemezsiniz.
    warpSettings.GridSize = new Size(100, 100);

    // Geçerli değeri ayarla
    warpSettings.GridSize = new Size(3, 3);

    // x3 ızgara ile örnek dosyayı oluştur
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Ayrıca Bakınız

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

[`WarpSettings`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | Çarpıtma ayarlarıyla PS öğeleri |
| bounds | Rectangle | Çarpıtma görüntüsünün sınırları |

### Ayrıca Bakınız

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

[`WarpSettings`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| placedResource | PlacedResource | Çarpıtma ayarlarına sahip kaynak |

### Ayrıca Bakınız

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


